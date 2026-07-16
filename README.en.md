# Floating Navbar Effect

![Preview](assets/preview.svg)

A floating navigation bar that compacts on scroll, highlights the active section, and provides an accessible mobile menu.

## Features

- Visual scrolled state.
- Active section through `IntersectionObserver`.
- Mobile menu with Escape, outside click, and focus return.
- Anchor and keyboard navigation.

## Live demo

[floating-navbar-effect.netlify.app](https://floating-navbar-effect.netlify.app)

## Installation

Clone the repository, enter `floating-navbar-effect`, and open `index.html`.

## Project structure

Navigation and sections in `index.html`, responsive styling in `style.css`, state logic in `script.js`, and SVG assets.

## Customization

Add anchors and matching section IDs; adapt `rootMargin` to change active-link timing.

## Accessibility

Uses `nav`, `aria-current`, `aria-expanded`, Escape closing, touch targets, and visible focus.

## Performance

Scroll state uses one pending frame and active sections need no continuous geometry calculations.

## License and credits

[MIT](LICENSE). Created by [Nacho Torres](https://github.com/NachoTorresRD) for [NTDESWEB](https://www.ntdesweb.com) with [NT-SKILL SUPREME](https://github.com/NachoTorresRD/nt-skill-supreme).

[View on GitHub](https://github.com/NachoTorresRD/floating-navbar-effect) · [Work with NTDESWEB](https://www.ntdesweb.com)
