# Envision Campus Explorer

An interactive 3D web explorer of Envision's two campuses:

- **Wichita Campus** (2301 S Water Street) with the S. Water St. Development Project phase overlay
- **Dallas Campus** (1801 Valley View Lane, Farmers Branch)

## Running it

The explorer is a single self-contained file, `index.html`. There is no build step.

- Locally: open `index.html` in a browser, or serve the folder (`python3 -m http.server`).
- Deploy: any static host. On Vercel, the repo deploys as-is with no configuration, serving `index.html` at the root.

It loads Three.js (r128) and Montserrat from CDNs at runtime, so an internet connection is required on first load.

## Controls

- Drag to orbit, pinch or scroll to zoom, on-screen buttons or arrow keys to move the camera.
- Tap a marker to visit a location, tap again to zoom closer.
- The Locations list mirrors every marker as a keyboard-accessible button.
- Tour autoplays through the locations. Motion toggles ambient animation (and respects reduced-motion preferences).
- Phases (Wichita only) shows the development project zones and move-in dates.
