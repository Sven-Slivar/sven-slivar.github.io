# Sven Slivar — Portfolio

Personal portfolio and CV. Each project has a small playable minigame that resolves into real gameplay footage.

**Live:** https://sven-slivar.github.io

## Pages

| Page | File |
|---|---|
| Home | `index.html` (phones are redirected to `home-mobile.html`) |
| Parry Simulator | `parry-simulator.html` |
| Sundress Murder | `sundress-murder.html` |
| Johnny, is it still you? | `johnny.html` |
| CV, printable | `cv.html` |

## Stack

Static HTML, CSS and vanilla JavaScript. No build step and no backend.
Pages render through a small runtime (`support.js`) on React 18, with React and Babel bundled in `vendor/`, so there are no external script dependencies.

## Run locally

```sh
python3 -m http.server
```

Open http://localhost:8000. The pages need a local server; opening the files directly from the folder won't work.

## Deploy

Hosted on GitHub Pages from the `main` branch root. Push to `main` to publish.

## License

Code, text, images and video © 2026 Sven Slivar. All rights reserved.
