# 360 Walkthrough Demo

Three.js viewer for pre-rendered 360 panoramas with move-in transitions between rooms and a day/night crossfade.

- Click the door hotspot: the camera turns to the door, glides forward, and the next room's panorama fades in from its own position, so both images stretch the way a real move would.
- Day / Night: crossfade between two renders taken from the same camera.
- Drag to look, wheel to zoom. Works on touch.

Single `index.html`, no build step. Serve the folder with any static server.

Panoramas: [Poly Haven](https://polyhaven.com) (CC0), resized to 4096x2048.
