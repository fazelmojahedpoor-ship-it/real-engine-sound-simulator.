# Real Engine Sound Simulator V1

A lightweight browser prototype for a first-person engine and driving experience inspired by Yazd, Iran.

## Features in this prototype
- Procedural 3D road environment with Yazd-inspired mud-brick buildings, windcatchers, desert, and distant mountains.
- Motorcycle and car cockpit props, plus an exterior camera.
- Daylight/sunset toggle.
- Several selectable engine configurations.
- Throttle, clutch, braking, gear selection, RPM, speed, and engine temperature.
- Procedural Web Audio engine sound that follows RPM and throttle.
- Touchscreen and keyboard controls.

## Run it
The project uses Three.js from a CDN, so an internet connection is required.

### Easy option
Open `index.html` in a modern browser. If your browser blocks ES modules from local files, use a local server instead.

### Python local server
1. Install Python 3 if needed.
2. Open a terminal in this folder.
3. Run:
   ```bash
   python -m http.server 8000
   ```
4. Open `http://localhost:8000` in your browser.

## Controls
- W / Up Arrow: throttle
- S / Down Arrow: brake
- Hold Shift: clutch
- E: upshift
- Q: downshift
- N: neutral
- A / D: steering camera/body
- Touchscreen: hold the on-screen controls

## Important limitations
This is a playable V1 prototype, not a professional vehicle simulator. The 3D environment is procedural and inspired by Yazd rather than a geographically exact map. Engine audio is synthesized; it is not yet based on licensed recordings of actual engines. Gear ratios and vehicle dynamics are simplified. The browser must support WebGL and Web Audio. Real recordings, more accurate torque curves, wheel physics, and richer 3D assets can be added in future versions.
