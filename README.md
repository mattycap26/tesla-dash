# tesla-dash

A lightweight home dashboard for the Tesla Model 3 in-car browser, built to load fast on the Intel Atom infotainment computer.

**Live:** https://mattycap26.github.io/tesla-dash/

## What's on it

- Clock and greeting
- Weather now and the next 6 hours ([Open-Meteo](https://open-meteo.com), no API key), with car tips for cold, heat and rain
- Big launch tiles for streaming and EV sites (edit in Settings)
- Charging estimate: cost, time, range and energy for home Level 2 or V3 Supercharging, tuned for a 2021 Model 3 Performance
- Notes pad

Settings and notes are stored in the car browser's local storage. Nothing is sent anywhere except the weather and city lookups.

## Design constraints

- One `index.html`, no build step, no frameworks, no web fonts
- No blur, shadows or animation (the Atom GPU is slow)
- Touch targets at least 50 px tall
- Light, dark and auto themes

## Roadmap

- Phase 2: live car status (battery, range, climate, locks) through the Tesla Fleet API
