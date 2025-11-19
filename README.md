Portfolio of Ruth Storm
=========================================

A visually immersive portfolio website showcasing my projects through elegant, responsive layouts and smooth interactions. Built with semantic HTML, Sass, and JavaScript, the site prioritizes user experience with fast loading, intuitive navigation, and seamless presentation across all devices.


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


