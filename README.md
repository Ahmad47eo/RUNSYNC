# RUNSYNC 🌲

**Nature-powered virtual running. Free, browser-first, open source.**

RUNSYNC is an early browser prototype for scenic routes, workout sessions, missions, XP, and future community races.

## Try it
1. Open `index.html` in a modern browser, or enable GitHub Pages for this repository.
2. Choose a route.
3. Start and pause a local timer.
4. XP and session totals are stored in your browser's local storage.

An internet connection is needed for the illustrative route photography. The core interface and timer are local.

## Current prototype
- Responsive, nature-inspired dashboard
- Three scenic route cards
- Local session timer
- XP, levels, missions and browser-local progress
- Race-mode preview
- Explicitly disabled treadmill integration

## Roadmap
- [ ] Real route playback / video sync
- [ ] Optional account and cloud progress
- [ ] Multiplayer races and leaderboards
- [ ] Accessibility and localization
- [x] Add FitShow compatibility research panel and official-source checklist (device integration still unconfirmed)
- [ ] Device safety review before any hardware connection

## FitShow compatibility research and treadmill safety

This version does **not** connect to Bluetooth, scan for devices, read treadmill telemetry, or control speed. FitShow compatibility for the exact 3Q second-generation model is **unconfirmed**. The model label previously shared as “YXTOO3” may be uncertain, so verify the model from the treadmill's rating label or manual.

What official FitShow sources establish:
- FitShow describes Bluetooth smart-fitness hardware and app/software development services: https://www.fitshow.com/
- FitShow describes its app for treadmills and other indoor fitness equipment: https://www.fitshow.com/fitshowApp
- FitShow offers OEM/SDK services, but access and device compatibility must be confirmed with the vendor: https://www.fitshow.com/oemApp
- FitShow says its hardware can work with apps supporting FTMS; that is not proof that this specific 3Q treadmill exposes FTMS.

Safe verification plan:
1. Confirm the exact treadmill model and controller/module from its label or manual.
2. Check that the official FitShow app recognizes it using the app's own device-discovery flow while the treadmill is stopped.
3. Ask FitShow support or the seller for written confirmation of this model's supported protocol and official SDK documentation.
4. Keep RUNSYNC disconnected until that evidence is available. Do not guess Bluetooth services, characteristics, payloads, or speed commands, and never test an integration while walking or running.

The RUNSYNC compatibility panel summarizes this status. No Bluetooth commands or device-control code were added. Always follow the treadmill manufacturer's safety instructions.

## Open source
Released under the MIT License. Third-party photos load from Unsplash and remain subject to their own licensing and terms; they are not covered by the project's MIT license.

## Contributing
Issues and pull requests are welcome. Please describe your browser/device and steps to reproduce bugs. Do not submit private health information, credentials, or personal data.
