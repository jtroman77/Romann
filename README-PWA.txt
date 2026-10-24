# Romann Matrix PWA

## Files
- `index.html` — existing Matrix dashboard with PWA metadata and service-worker registration
- `manifest.json` — install name, standalone display, icons and GitHub Pages-relative scope
- `sw.js` — app-shell cache only; Deriv API/WebSocket traffic is not cached
- `icons/` — 192px and 512px app icons

## Publish to GitHub Pages
Upload/commit all files and folders into the repository root (`Romann`), replacing `index.html` with this version. Keep the folder structure exactly as shown.

Website: https://jtroman77.github.io/Romann/

## Install on Android
1. Open the website in Chrome after GitHub Pages has deployed the files.
2. Open Chrome's ⋮ menu.
3. Choose **Install app** or **Add to Home screen** (wording may vary).
4. Launch Matrix from the home screen.

Notes:
- PWA installation does not make the trading engine run in the background after Android suspends/closes the app.
- Live trading requires internet and a valid Deriv connection. Do not assume trades can be safely managed offline.
- Test on a Deriv demo account before using a real account.
