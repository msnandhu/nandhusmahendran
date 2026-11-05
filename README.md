# Nandhu S. Mahendran — Portfolio

Personal portfolio of **Nandhu S. Mahendran**, Founder & CEO of Blunar Co, Zeshin, Med Blunar and HodoMate (Ramanathapuram, Tamil Nadu).

The home screen is a live title sequence drawn in code on an HTML canvas: dust and light, the Blunar Co logo forming from gold sparks, a glitch, the Zeshin logo built by a laser scan, a shockwave, and a dot-scan portrait that shoots up from the bottom and locks in line by line. No video files; it adapts to any screen size.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The whole site: markup, styles and the animation script |
| `assets/portrait-map.png` | Tone map the animation samples to place the portrait's particles |
| `assets/portrait.jpg` | Dot-scan portrait used in the About section |
| `assets/blunar-white.png`, `assets/zeshin-white.png` | Logos used in the intro and the Companies section |

## Run locally

The animation reads image pixels, so open it through a local server rather than double-clicking the file:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publish with GitHub Pages

Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
The site will be live at `https://msnandhu.github.io/nandhusmahendran/` within a minute or two.
