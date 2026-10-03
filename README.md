# High Canvas

A club for wild ideas and tidal days.

Static one-page site rebuilt as clean HTML/CSS from the original Framer-published
version — no builder runtime, no lock-in. Hosts anywhere static files are served
(GitHub Pages, Netlify, Cloudflare Pages, any web server).

## Structure

```
index.html        markup
css/style.css     all styles (responsive: desktop / tablet ≤810px / mobile ≤560px)
assets/           images and the Americaine display font (woff2)
```

Libre Baskerville is loaded from Google Fonts; everything else is local.

## Local preview

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

## GitHub Pages

This repo deploys from `main` / root. Enable it in **Settings → Pages →
Deploy from a branch**. The site goes live at
`https://highcanvas.github.io/high-canvas/`.
