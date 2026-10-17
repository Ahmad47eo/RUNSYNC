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
- [ ] Investigate official FitShow integration for the exact 3Q second-generation treadmill model
- [ ] Device safety review before any hardware connection

## Treadmill safety
This version does **not** connect to Bluetooth, read treadmill telemetry, or control speed. FitShow compatibility for the exact 3Q model has not been verified. Do not send undocumented Bluetooth commands or test integrations while using a treadmill. Hardware integration requires official documentation and safe, stationary testing first. Always follow the manufacturer's safety instructions.

## Open source
Released under the MIT License. Third-party photos load from Unsplash and remain subject to their own licensing and terms; they are not covered by the project's MIT license.

## Contributing
Issues and pull requests are welcome. Please describe your browser/device and steps to reproduce bugs. Do not submit private health information, credentials, or personal data.
