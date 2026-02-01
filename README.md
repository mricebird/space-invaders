# Cosmic Blasterz 🚀

Classic Space Invaders-style arcade game built with **HTML5 Canvas**.

Play here: https://mricebird.github.io/cosmic-blasterz/

## Features
- Fast arcade gameplay
- Highscore + replay/ghost-style elements (if enabled)
- PWA-ready (manifest + service worker)

## How to run locally
Option A (simplest):
- Open `index.html` in your browser

Option B (recommended – local server):
- `python3 -m http.server 8080`
- Open `http://localhost:8080`

## Project structure
- `index.html` – entry point
- `play/` – game assets / runtime (if used)
- `service-worker.js` – offline/PWA support
- `manifest.json` – PWA manifest

## Security note
Player names / highscores must always be rendered as text (avoid HTML injection).

## License
MIT (add a LICENSE file if you want this to be fully explicit).
