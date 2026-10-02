# Parallax

Built by Girish Lade — [ladestack.in](https://ladestack.in)

A scroll-driven **parallax layer effect** demo: background layers move at different
speeds as you scroll, creating depth and motion on a landing-page-style layout.

## Features

- Multi-layer parallax — 4 depth layers (`data-parallax-layer`) animated with
  GSAP ScrollTrigger timelines at different speeds (70 / 55 / 40 / 10 yPercent)
- Butter-smooth scrolling via Lenis, synced to GSAP's ticker
- Scrub-linked animation — scroll position drives the timeline directly
- Single-page demo layout, no build step, no dependencies to install

## Tech stack

- HTML5, CSS3, vanilla JavaScript
- [GSAP](https://greensock.com/gsap/) + ScrollTrigger (CDN)
- [Lenis](https://lenis.darkroom.engineering/) smooth scroll (CDN)

## Quick start

No build needed — just open it:

```bash
# any static server works, e.g.
npx serve .
```

Then visit the served URL. Or open `index.html` directly in a browser.

## Project structure

```
Parallax/
├── index.html   # markup + embedded base styles
├── styles.css   # layout, layers, theme styles
├── script.js    # GSAP ScrollTrigger parallax timelines + Lenis wiring
└── LICENSE
```

## Deploy notes

Plain static site — deploy anywhere (GitHub Pages, Cloudflare Pages, Netlify).
This repo is served via GitHub Pages.

## Credits

Parallax technique inspired by [Osmo](https://osmo.supply/) cloneables.
