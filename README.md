# Pacific Blue

Marketing site for Pacific Blue, an Australian 100% renewable energy company.

## Live site

[pacificblue.com.au](https://pacificblue.com.au) — hosted preview: [lobzyjay.github.io/Pacific-blue](https://lobzyjay.github.io/Pacific-blue)

## Stack

Single-file HTML/CSS/JS — no build step, no dependencies beyond CDN.

| Library | Version | Purpose |
|---|---|---|
| Three.js | r128 | 3D wind turbine scene |
| GLTFLoader | r128 | Embedded GLB model |
| Lenis | 1.0.42 | Smooth scroll |

## Features

- Immersive 3.5s black starfield loading screen with orbital animation
- Three.js wind turbine with scroll-driven blade speed, fog, and starfield
- Sticky 3D section that locks below the header while scrolling through phases
- Bidirectional scroll animations — every section resets and replays on re-entry
- Hero entrance animation triggered after loader, replay on scroll back
- Bento grid with animated number counters that reset on scroll-away
- Footer ambient rising-particle canvas
- Mobile-first responsive: 1280 / 960 / 768 / 480 / 380px breakpoints
- Phone mockup tile reorders to bottom on mobile

## Development

No build step. Open `index.html` directly in a browser, or serve locally:

```bash
npx serve .
# or
python3 -m http.server 8080
```
