# Hypertrophy Mesocycle Tracker PWA

This package converts the original HTML tracker into a Progressive Web App.

## Files

- `index.html` — the tracker app
- `manifest.webmanifest` — app name, icons, theme, install metadata
- `service-worker.js` — offline caching
- `icons/` — app icons

## Important

PWA installation and service workers do not work from `file://` URLs.

Use one of these options:

1. Host the folder with GitHub Pages, Netlify, Vercel, Cloudflare Pages, or any HTTPS static host.
2. For local testing on a computer, run a local server from this folder:
   ```bash
   python3 -m http.server 8080
   ```
   Then open:
   ```text
   http://localhost:8080
   ```

## Install on Pixel / Android Chrome

1. Open the hosted URL in Chrome.
2. Tap the browser menu.
3. Tap `Install app` or `Add to Home screen`.
4. Open it from your home screen.

## Data storage

The tracker stores data in browser local storage on the device. Export JSON backups periodically from the Export / Import tab.
