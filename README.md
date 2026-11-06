# 🌍 Earth in Motion — A Moving Perspective

**Earth has never been in the same place twice, if you measure against the galaxy.**
An interactive, offline 3D explorer of planetary orbits, the Sun's 230 km/s journey around
Sagittarius A*, and the idea underneath it all: *every motion depends on what you measure it against.*

**[▶ Live demo](https://yashaswyakella.github.io/earth-in-motion/)**

<!-- Add a screenshot: save one as screenshot.png in the repo and uncomment -->
<!-- ![Earth in Motion screenshot](screenshot.png) -->

## Features

| View | What you see |
|---|---|
| **01 · Through the galaxy** | Planets tracing Stretched, tilted helices as the Sun moves, with Sagittarius A* and the Milky Way in the background in their true direction |
| **02 · Around the Sun** | The familiar textbook view: the same motion, measured from the Sun |
| **03 · The Milky Way** | The Sun's 230-million-year orbit and its up-and-down motion through the disc, with markers for the Cambrian explosion and the dinosaurs |
| **04 · Sagittarius A*** | Real stars (S2, S38, S55) orbiting our galaxy's black hole at up to ~7,700 km/s |

Plus:
- **Live counters:** how far you've moved since opening the page, measured against Earth's axis, the Sun, the galaxy, the cosmic microwave background (CMB), Andromeda and light
- **A lifetime calculator** that turns your age into cosmic distance (nothing is stored or sent)
- **A fact-check** of the viral post that inspired the project
- Real orbital data (NASA JPL J2000 elements), physical and illustrative scales
- Touch, mouse and keyboard controls, screen-reader labels, and a reduced-motion setting
- **One self-contained HTML file:** no build step, no dependencies, works offline

## Run it

Open `index.html` in any modern browser. That's it.

Or serve it locally:
```bash
python3 -m http.server 8000
# open http://localhost:8000
```
