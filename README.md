# Gallagher Brickwork & Building Services Ltd — Premium Homepage (Demo)

A premium, mobile-first, GitHub Pages-ready homepage redesign for **Gallagher Brickwork & Building Services Ltd**, family-run builders in Guildford, Surrey (est. 2007).

> **Note:** This is a design demo with `noindex` applied so it does not compete with the live website in search results.

## Features

- Mobile-first responsive design (360px → 1440px+), no horizontal overflow
- Sticky header with full-screen mobile navigation
- Floating "Call Now" button + back-to-top (safe-area aware)
- FAQ accordion, scroll-reveal animations, smooth anchor scrolling
- Original business photography and brand colours (deep navy + brick red)
- Real contact details: 01483 566009 · info@gbbs.direct · 83 Stoughton Road, Guildford, GU1 1LH

## Structure

```
index.html
css/style.css
js/script.js
assets/images/   (original project photography)
assets/logo/     (logo.svg)
.nojekyll
```

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy (GitHub Pages)

Settings → Pages → Source: `main` branch, `/ (root)`. The site loads from `index.html` with relative paths.
