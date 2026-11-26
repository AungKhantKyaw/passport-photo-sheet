# passport-photo-sheet

Browser-based passport/ID photo maker: crop to 35×45 mm with head-size guides, then export a 300 DPI 6×4" print sheet. No uploads, runs locally.

**Live demo:** https://aungkhantkyaw.github.io/passport-photo-sheet

## Features

- Crop to 35×45 mm (413×531 px at 300 DPI)
- Head-size guides for the 70–80% range, plus centre and eye lines
- Zoom, pan and level-tilt controls (drag, scroll, pinch or arrow keys)
- Optional backdrop lightening, plus brightness and contrast
- Export a single photo or a 6×4" sheet (6-up or 8-up) with crop marks and a kiosk trim guide
- JPEG output tagged as 300 DPI
- Runs entirely in your browser; photos are never uploaded

## Usage

1. Open the live demo, or open `index.html` locally.
2. Upload a photo (JPG or PNG; HEIC is not supported by most browsers).
3. Adjust zoom, pan and tilt so the head sits between the green and amber ovals.
4. Choose the grid layout and sheet background.
5. Download the 6×4" sheet or the single photo.

## Printing

- Print at 100% scale, with no "fit to page" or "shrink to fit".
- Measure one printed photo. It should be 35×45 mm.
- Many photo kiosks trim about 3 mm from the edges, so keep the red guide in mind when choosing 6-up or 8-up.

## Disclaimer

The head-size ovals and the backdrop helper are guides, not an official compliance check. Passport and visa rules vary by country, so check your issuer's requirements before submitting. A real plain, light wall is the safest backdrop.

## License

MIT. See [LICENSE](LICENSE).
