# PixelScale – Free Online Floor Plan Measuring Tool

**Measure distances and areas on floor plans, blueprints, maps and images – free, in your browser, no upload, no sign-up.**

<a href="https://bohannjein.github.io/pixelscale/"><img src="assets/open-tool.svg" alt="Open PixelScale – measure floor plans online" height="56"></a>

PixelScale is a free online tool to measure square footage and room sizes from a floor plan image. Upload a floor plan (JPG or PNG), calibrate the scale once against a known length, and every click becomes a real-world measurement in metres, centimetres, square metres, feet, inches or square feet. Export the annotated plan with all measurements as a PDF.

Everything runs locally in your browser. Your floor plan is never uploaded to a server, and there is no account, no tracking and no cost.

## What you can do with PixelScale

- **Measure a floor plan online** – get the real length of walls, rooms and distances from any plan image.
- **Calculate area from a floor plan** – draw room outlines and get the area in m² or ft², including a total for all rooms.
- **Measure square footage of an apartment or house** – ideal for checking listing sizes, planning flooring, paint or furniture.
- **Measure distances on images and maps** – works with blueprints, site plans, sketches, screenshots and scanned drawings.
- **Scale a drawing** – calibrate using the plan's scale bar or any known dimension (e.g. a door width).

## Features

- **Scale calibration** – click two points on a known distance (e.g. a 0–4 m scale bar), enter its real length, done.
- **Distance measurement** – continuous polylines; keep clicking to measure along walls or paths.
- **Area measurement** – polygons with automatic m² / ft² calculation and a running total.
- **Snapping** – points lock onto existing points so rooms connect exactly.
- **Groups** – organise measurements by floor, apartment or room type; each group has its own colour and subtotal.
- **Metric and imperial units** – switch between m / cm / m² and ft / in / ft² at any time.
- **PDF export** – one-page A4 landscape PDF with the annotated plan and a colour-coded measurement list.
- **Dark and light mode** – follows your system setting, with a manual toggle.
- **English and German** interface.
- **Private by design** – image and measurements are saved only in your browser (`localStorage`) and survive a reload.
- **Works offline** – a single static `index.html` with no dependencies and no external requests.

## How to measure a floor plan in 4 steps

1. Open [PixelScale](https://bohannjein.github.io/pixelscale/) and drag your floor plan onto the page, or click **Choose image**.
2. Click **Calibrate**, click both ends of a known distance on the plan, enter its real length and press **OK**.
3. Choose **Distance** or **Area** and click the points. Double-click or right-click to finish a measurement.
4. Rename groups and measurements if you like, then click **Export PDF**.

## Controls

| Action | Input |
| --- | --- |
| Place point | Left click (snaps to nearby points) |
| Finish & save measurement | Double-click or right-click |
| Discard current measurement | Esc |
| Pan | Shift + drag, or middle mouse button |
| Zoom | Mouse wheel or the zoom buttons |

## FAQ

### How do I calculate the area of a room from a floor plan?
Calibrate the plan with a known length, switch to **Area**, click the corners of the room and double-click to close the shape. PixelScale calculates the area in m² or ft² and sums all rooms automatically.

### Can I measure a floor plan without a scale bar?
Yes. Use any dimension you know, for example a labelled wall length, a standard door width (about 0.8–0.9 m) or a known furniture size.

### Is my floor plan uploaded anywhere?
No. The image is processed entirely in your browser. Nothing is sent to a server.

### Is PixelScale free?
Yes, completely free, with no account and no ads.

### Which file types are supported?
Any image your browser can open, such as JPG, PNG, WebP or GIF. For PDF plans, take a screenshot or export the page as an image first.

### How accurate are the measurements?
Accuracy depends on the calibration and the image resolution. Zoom in on the ends of the reference line before calibrating for the best result.

## Deutsch: Grundriss online ausmessen

PixelScale ist ein kostenloses Online-Tool, um **Grundrisse auszumessen** und die **Wohnfläche bzw. Quadratmeter aus einem Grundriss zu berechnen** – direkt im Browser, ohne Upload und ohne Anmeldung. Grundriss als Bild laden, Maßstab einmal kalibrieren und anschließend Strecken in Metern und Flächen in m² messen. Mehrere Räume lassen sich in Gruppen ordnen, die Gesamtfläche wird automatisch summiert, und das Ergebnis kann als PDF exportiert werden. Die Oberfläche ist auf Deutsch umschaltbar.

<a href="https://bohannjein.github.io/pixelscale/"><img src="assets/open-tool-de.svg" alt="Grundriss jetzt online messen mit PixelScale" height="56"></a>

## Notes & limits

- The PDF is a single page; if a very long measurement list would overflow, it is truncated (the plan image is always complete).
- Stored images are downscaled to a 2400 px maximum edge to fit the browser storage quota.

## Self-hosting

PixelScale is one static HTML file. Download `index.html` and open it locally, or host it on GitHub Pages or any web server.

## License

Do whatever you like with it.
