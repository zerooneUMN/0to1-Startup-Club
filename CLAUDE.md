# 0→1 Startup Club Website

## Project Overview
Static single-page website for the 0→1 Startup Club at the University of Minnesota. Hosted via GitHub Pages at the domain specified in `CNAME`.

## Stack
- Pure HTML/CSS/JS — no build tools, no framework, no package manager
- Single file: `index.html` (contains all HTML, CSS, and JS inline)
- Assets: `assets/` (member photos, logos)
- Fonts: Google Fonts (Oswald, PT Serif)

## Development
Open `index.html` directly in a browser — no server required.

## Deployment
Push to `main` branch → GitHub Pages auto-deploys.

## Design Conventions
- Color palette: `#fffcf7` (cream background), `#1a1a1a` (near-black text)
- Typography: PT Serif (body), Oswald (headings)
- Layout: panel-based slide navigation controlled by JS
- Responsive sizing via `clamp()` and `vmin` units
- Pill-shaped buttons with hover fill effect
