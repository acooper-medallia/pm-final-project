# Competitive Analysis & Journey Map

> **Module 2 · Lab 2 — ★ Deliverable 2.** Repo file `02-discovery/competitive-and-journey.md` — part of your submission.
> Do the lab in the **Module 2 · Exercise 2 Guide** (linked from the Module 2 deck), then click **⬇ Download .md** — it saves as this exact file. Commit it here.
> It becomes the **Competitive Analysis & Journey Map** slide of your Module 6 final deck. Builds on your `ai-synthesis.md` and your Module 1 `problem-hook.md`.

## Responses

- **Role, who are you solving for?:** The frontline last-mile delivery driver on RouteLogic Velocity (B2B): a driver working a 30–60+ stop route on an Android phone, often one-handed at the doorstep, sometimes in rural or low-signal areas. They use roughly 5% of the product, but they use it all day.
- **Goal, what is this user ultimately trying to achieve?:** Finish every stop on the route quickly and correctly, with each delivery recorded and proven the moment it happens, so that dispatch, the warehouse, and the customer see an accurate status without the driver having to follow up.
- **Friction, the main barrier (moment of misery) stopping them:** At the doorstep, closing out a stop is slow and unreliable. "Mark delivered" takes 3 taps across 3 screens (BUG-2055), and the proof-of-delivery photo then fails silently on weak signal about 35% of the time (BUG-2061). The driver can't tell whether the delivery was recorded, so they stop trusting the app as the system of record.
- **External tools the user is forced to use:** SMS/text messages to the dispatcher (to report deliveries), the dispatcher's WhatsApp group (the "real system" for route changes), phone calls to the office (to recover stops after a crash), a paper manifest (backup kept by 5 of 7 focus-group drivers), and phone screenshots of the route (offline backup).
- **The process, the 3–5 manual steps they take:**
  1. Before leaving, screenshot the route and print or carry a paper manifest in case the app crashes or loses signal.
  2. At the doorstep, tap through 3 screens to mark the stop delivered, with a package in one hand.
  3. Take the POD photo. With no success confirmation, retake it up to 3 times "to be safe."
  4. Text the dispatcher to confirm the delivery, because neither of them trusts the app's status (the dashboard lags 20–60 min).
  5. Check WhatsApp for route changes, since in-app reassignments arrive 8–15 min late with no push notification.
- **Core frustration, where the process feels most "broken":** Standing at the doorstep after the photo upload: the driver has done everything the app asked and still doesn't know whether it worked. That uncertainty pushes them to retake photos and text dispatch, which makes the app a duplicate of the real system rather than the system itself.
- **The evidence, a quote or behavior from the research:** *"To mark a stop delivered I tap through three screens. In the rain, at a doorstep, with a package in one hand. I've started just texting my dispatcher instead."* (UXR-01, driver, 3 yrs). This is backed by UXR-07: *"Drivers don't know if it worked, so they retake three times,"* and by UXR-12, where 5 of 7 drivers keep a paper manifest and all 7 rank core-action speed above any new feature.
- **Journey map, a shareable link or the map file you committed:** [`02-discovery/journey-map.html`](journey-map.html)
