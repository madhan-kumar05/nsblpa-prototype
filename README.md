# NSBLPA Prototype

## Overview
Mobile-first responsive redesign of NSBLPA inspired by nfl.com & fvnsport.com. Built with semantic HTML, Tailwind CSS (CDN), and vanilla JS (ES6).

## How to run locally
1. Unzip or clone the `nsblpa-prototype/` folder.
2. Open `index.html` in any modern browser. (No server or build step required.)
3. For testing on mobile, use Chrome DevTools device toolbar or open on a device.

## Deliverables
- `index.html`, `ownership.html`, `teams.html`, `apps.html`, `contact.html`
- `assets/styles.css`, `assets/scripts.js`, logos & images
- Loom video walkthrough (link included in submission email)

## Assumptions & design decisions
- Tailwind via CDN used to meet the "Tailwind" requirement while keeping offline usability.
- Placeholder logos used where official brand assets were not provided.
- Contact form uses client-side validation only (no backend provided). Form action is a `mailto:` fallback.
- External links to team websites and Play Store apps open in new tab with `rel="noopener"`.

## Accessibility & performance
- Semantic tags (header, nav, main, footer).
- `alt` text for images; buttons and links keyboard-focusable.
- Minimal JS for interaction; images optimized.

## Assets
- Logos: `assets/logos/` (placeholders or provided assets)
- Images: `assets/images/`

