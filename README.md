Portfolio — Front-End Repository Overview
=========================================

This repository contains a responsive static portfolio website built with semantic HTML, Sass-based styles, and a small set of vanilla JavaScript utilities. It’s optimized for visual presentation (photography-heavy pages), simple hosting on static platforms (GitHub Pages, Netlify, Vercel), and progressive enhancement. 


Repository Structure
--------------------
- `index.html` — Main landing page
- `elements.html`, `northern.html` — Template pages and content
- `assets/` — Source assets
  - `css/` — Compiled CSS used by the site
  - `js/` — Vanilla JS utilities and initialization scripts (gallery, navigation, breakpoints)
  - `sass/` — Source SCSS files (components, layout, libs)
- `images/` — All image assets
- `webfonts/` — Font files used for the site (FontAwesome included locally)

Design & Implementation Notes
-----------------------------
- Sass organization
  - `base/`, `components/`, and `layout/` folders provide modularized styles aimed at reusability.
  - `libs/` contains helper functions/mixins for cross-browser vendor prefixes and breakpoints.
- JS utilities
  - Minimal dependency set: jQuery is used for DOM utilities and several plugins (breakpoints, scrolly/scrollex) for scroll-driven effects.

Developer Experience
--------------------
- Local server: use `python3 -m http.server` or a lightweight Node static server.
- To rebuild Sass locally:
  - Either use the included `sass` (Dart Sass) command or add a `package.json` with convenience scripts.

