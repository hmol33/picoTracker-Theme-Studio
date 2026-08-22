# picoTracker-Theme-Studio

A browser-based theme editor for the [picoTracker](https://github.com/synthetos/picoTracker) — design and export `.PTT` theme files without leaving your browser.

## Try it online

Use the live editor here: <https://itsdarklikehell.github.io/picoTracker-Theme-Studio/>

## Run locally

The app is a static site. Serve the `static-app/` folder with any static web server, for example:

```bash
cd static-app
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## How it works

- **Import** an existing `.PTT` theme file to load its colors.
- **Edit / Randomize** the palette using the on-screen controls.
- **Generate** a new `.PTT` theme file to download and flash to your picoTracker.

## Project layout

- `static-app/` — the static web app (HTML/CSS/JS) published to GitHub Pages.
- `ref/` — reference screens and text used while building the preview.
