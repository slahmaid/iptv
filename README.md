# IPTV Streaming Landing Page

A responsive, conversion-focused marketing landing page for an IPTV streaming
service. Built with plain HTML, CSS, and a small amount of vanilla JavaScript —
no build step or dependencies required.

## Features

- Sticky-free responsive header with a mobile hamburger menu
- Hero section with animated call-to-action
- Infinite logo marquee of partner networks
- Alternating feature highlights
- Customer reviews grid
- Pricing plans with anchored pricing and secure-payment badges
- About section with key stats
- Accordion FAQ
- Smooth-scroll in-page navigation
- Fully responsive down to small mobile devices

## Project structure

```
.
├── index.html              # Page markup
├── css/
│   └── styles.css          # All styles
├── assets/
│   └── images/             # Logo and section imagery
│       ├── logo.webp
│       ├── hero.jpeg
│       ├── features-1.jpeg
│       └── features-2.jpeg
└── README.md
```

## Running locally

This is a static site, so no installation is needed. Either open `index.html`
directly in a browser, or serve it with a simple static server:

```bash
# Python 3
python -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Customization

- Text/copy: edit `index.html`.
- Colors, spacing, and layout: edit `css/styles.css`. The brand accent color is
  `rgb(161, 255, 20)`.
- Images: replace the files in `assets/images/` (keep the same names, or update
  the `src` paths in `index.html`).

## Notes

The pricing figures, statistics, review quotes, and payment badges are sample
content. Verify all claims and only display payment brands you actually accept
before publishing.
