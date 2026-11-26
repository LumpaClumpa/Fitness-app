# Fitness-app

A minimal, dark strength-training tracker (EU first: kg, cm, Monday weeks, data stays on your device).

**Live app:** https://lumpaclumpa.github.io/Fitness-app/ (on iPhone: Share → Add to Home Screen)

<<<<<<< HEAD
- `index.html`: the whole app in one file, no dependencies
- `manifest.webmanifest`, `sw.js`, `icons/` (app icons): app icon and offline support (bump `CACHE` in `sw.js` on every release)
- `tests/test_app.py`: end-to-end test that clicks every button (Playwright + Chromium)
=======
>>>>>>> 1cb23ff4711274e6923ca52387718506204389bd

Run the test: `python3 tests/test_app.py . /tmp/shots`

The changelog lives in the app under Settings → Changelog (`CHANGELOG` in `index.html`).
