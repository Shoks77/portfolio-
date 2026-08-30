# Shoki Sakuma — Portfolio

A single-page portfolio. Static HTML/CSS/JS — no build step, no dependencies.

## Structure

```
index.html        Main site (self-contained styles + scripts)
looksmax-3d.html  LooksMax interactive design-sheet / 3D breakdown (embedded)
aureole-3d.html   Auréole × Kering interactive 3D breakdown (embedded)
media/            Images, GIFs, video, and SVG assets
```

## Run locally

Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deploy

Works as-is on any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).
For GitHub Pages: push this folder to a repo and enable Pages on the `main` branch (root).
