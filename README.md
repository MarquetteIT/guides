# Marquette Transportation — Public Field Guides

Static reference guides for field equipment, published via GitHub Pages. No build step —
plain HTML/CSS, fonts self-hosted under each guide's `assets/fonts/`.

## CamPi Camera

- [Mounting Card](https://marquetteit.github.io/guides/campi/mounting-guide.html) — clamp the RAM Tough-Claw to a handrail, aim the camera, confirm power.
- [Status Light Reference](https://marquetteit.github.io/guides/campi/status-light-reference.html) — what the red status light's blink pattern means.

## Editing

Each guide folder (e.g. `campi/`) is self-contained: its own HTML pages, a shared
`assets/<name>-guide.css` stylesheet, and `assets/fonts/`. Edit the HTML/CSS directly — no
build tools required. Push to `main`; GitHub Pages serves it within a minute or two.
