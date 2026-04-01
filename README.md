# AR Compass for Amateur Radio

A browser-based augmented reality (AR) compass designed for amateur radio operators.

This tool uses a smartphone's GPS and orientation sensors to visualize the direction of a target station directly on the camera view.

## Features
- Real-time bearing calculation
- Distance estimation between stations
- Elevation / pitch adjustment for long-distance links
- AR overlay aligned with device orientation (yaw, pitch, roll)

## Platform Support
- Android devices
- Google Chrome browser (recommended)

Note:
This project relies on DeviceOrientation and camera access, which are fully supported on Android Chrome.
iOS browsers are not supported due to sensor and permission limitations.

## Use Cases
- Aiming directional antennas (Yagi, panel, etc.)
- Line-of-sight estimation
- Quick field setup without additional tools

## Tech Stack
- Web APIs (Geolocation + Device Orientation + Camera)
- JavaScript (no native app required)
- Runs directly on GitHub Pages

## Status
Experimental (v0.x)
