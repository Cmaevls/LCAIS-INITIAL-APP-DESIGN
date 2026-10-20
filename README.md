# LCAIS UI Demo

User interface demonstration for **LCAIS: Low-Cost Autonomous Irrigation System for Small-Scale Agricultural Areas in Tangkalan, Mamburao, Occidental Mindoro**.

This page shows how the LCAIS screens could look. **All readings are simulated.** The real device makes every decision on its ESP32 and shows its readings on its own screen, without internet.

## What the demo shows

- **Sign in:** demo only. Type any username and password. Nothing is saved or sent anywhere.
- **Home:** what the system is doing right now, the water tank, refill pump and river intake status, soil moisture with the start and stop levels, the checks from the system flowchart, a soil moisture chart, and a copy of the device screen.
- **Log:** every time a pump starts, stops, or is held back, and why.
- **Settings:** start and stop watering levels, refill time limit, and sensor calibration.
- **Device:** views of the initial design and where the water goes (river → strainer → refill pump and filter → tank → irrigation pump and valve → drip line).

## Demo controls

After signing in, tap **Demo data** at the top of the app. You can:

- make the soil dry
- start or stop rain
- use up the tank water
- make the river level low (the refill stops after the time limit and the app asks you to check the river intake)
- change the speed, pause, or reset

These buttons are for the demo only. They are not part of the app.

## Files

The whole demo is one file, `index.html`. The HTML, CSS, JavaScript, and the pictures of the device are all inside it. No libraries, no build step, and no internet connection needed.

## Run it

- **On your computer:** download `index.html` and open it in a browser.
- **On GitHub Pages:** https://cmaevls.github.io/LCAIS-INITIAL-DESIGN-UI/

## Credits

LCAIS thesis proposal, BS Computer Engineering, STI College Batangas.
Christine Mae M. Aviles, Lourd Martin A. Bicol, and Alexis D. De Jesus.
