# Wavelength

A lightweight, mobile-friendly music player for listening to tracks by Globalboy Collin and collaborators. The app is built with plain HTML, CSS, and JavaScript, and uses Ghana local time (Africa/Accra) for its greeting.

## Features

- Browse featured tracks and the full music library
- Search tracks by song or artist
- Play, pause, skip, and seek through tracks
- See playback progress in the expanded player
- Get a greeting based on the current time in Ghana
- Responsive layout with mobile safe-area support

## Run locally

No build tools or package installation are required. Download or clone the repository, then open `index.html` in a browser.

For best results, run it from a local static web server. For example, with Python installed:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Publish with GitHub Pages

1. Push the project files to a GitHub repository.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch you want to publish and the repository root (`/`) as the folder, then save.
5. Open the published URL shown in the Pages settings.

Keep `index.html`, `index.css`, `manifest.json`, the image files, and the `audio/` folder in the published repository so the app's styles and media load correctly.

## Project files

- `index.html` — app layout, track list, player logic, and Ghana-time greeting
- `index.css` — responsive styling
- `audio/` — music files used by the player
- `cover.jpg` — artwork displayed in the player
- `manifest.json` and `icon.png` — web app metadata and icon


