# Cayo Calc V19 — Dev8

GitHub Pages deployment package for the tested Cayo Calc V19 Dev8 build.

## Files

- `index.html` — Cayo Calc V19 Dev8
- `service-worker.js` — cache bumped to `cayo-calc-v2` so installed PWAs pick up Dev8
- `README.md` — project/deployment notes

Keep the existing `manifest.webmanifest` and icon files in the repository unchanged.

## Deploy

Replace the existing `index.html`, `service-worker.js`, and `README.md` with the files in this package. Leave the existing manifest and icons in place.

Then commit/push the changes and allow GitHub Pages to redeploy.
