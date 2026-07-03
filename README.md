# PixelScale]([https://www.example.com](https://bohannjein.github.io/pixelscale/))


Measure real-world distances and areas directly on floor plans, blueprints, maps, or any image — right in the browser. Calibrate once against a known length and every click becomes a real measurement. No upload, no account, no server: the image and all measurements stay in your browser via `localStorage` and survive a reload.

It's a single static `index.html` with no dependencies and no CDN calls, so it runs anywhere — GitHub Pages, any web host, or by double-clicking the file locally. Even the PDF export is generated entirely client-side.

## Features

- **Scale calibration** — draw a line over a known distance (e.g. a 0–4 m scale bar), enter its real length, done.
- **Distance & area** — distances are continuous polylines (keep clicking to extend a path); areas are polygons with automatic m²/ft² sums.
- **Snapping** — clicking near an existing point locks onto it exactly, so you can continue from or connect to previous measurements.
- **Groups** — organise measurements into named groups; each group gets its own colour, shown on the image and in the sidebar. Rename groups and individual measurements inline.
- **Units** — switch between metric (m / cm / m²) and imperial (ft / in / ft²) at any time; existing measurements convert live.
- **Languages** — English (default) and German, toggled in the header.
- **PDF export** — one-page A4 landscape PDF with the annotated plan on the left and a grouped, colour-coded measurement legend on the right.
- **Sessions** — image, scale, and measurements persist locally between visits. Nothing leaves your device.

## Controls

| Action | Input |
| --- | --- |
| Place point | Left click (snaps to nearby points) |
| Finish & save measurement | Double-click or right-click |
| Discard current measurement | Esc |
| Pan | Shift + drag, or middle mouse button |
| Zoom | Mouse wheel |

## How to use

1. Drag a floor plan / image onto the canvas, or click **Choose image**.
2. Click **⌖ Calibrate**, click the two ends of a known distance, enter its real length, press **OK**.
3. Pick **↔ Distance** or **▱ Area** and start clicking. Right-click or double-click to finish.
4. Add groups, rename them and your measurements, then hit **⤓ Export** for a PDF.

## Notes & limits

- The PDF is a single page; if a very long measurement list would overflow, it is truncated (the plan image is always complete).
- Stored images are downscaled to a 2400 px max edge to fit the browser storage quota.
- Accuracy depends on the calibration: zoom in on the scale-bar ends before calibrating for best precision.

## License

Do whatever you like with it.
