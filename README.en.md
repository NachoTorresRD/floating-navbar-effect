# Floating Navbar Effect

![Preview](assets/preview.svg)

A floating navigation bar that morphs while transforming three scenes inside one capture-ready block.

## Features

- Scene changes through click, wheel, or keyboard.
- Spring-like active indicator.
- Mobile menu with Escape, outside click, and focus return.
- Complete keyboard navigation.

## Live demo

[navbar.ntdesweb.dev](https://navbar.ntdesweb.dev/)

## More effect demos

- [Spotlight Card](https://spotlight.ntdesweb.dev/)
- [3D Product Card](https://card3d.ntdesweb.dev/)
- [Before/After Image Slider](https://fxpreview.ntdesweb.dev/)

## Installation

Clone the repository, enter `floating-navbar-effect`, and open `index.html`.

## Project structure

Navigation and sections in `index.html`, responsive styling in `style.css`, state logic in `script.js`, and SVG assets.

## Customization

Add entries to the `content` array, matching `data-scene` buttons, and their visual scene articles.

## Accessibility

Uses `nav`, `aria-current`, `aria-expanded`, Escape closing, touch targets, and visible focus.

## Performance

Scene transitions animate only `transform` and `opacity`, with a short wheel lock to prevent skips.

## License and credits

[MIT](LICENSE). Created by [Nacho Torres](https://github.com/NachoTorresRD) for [NTDESWEB](https://www.ntdesweb.com) with [NT-SKILL SUPREME](https://github.com/NachoTorresRD/nt-skill-supreme).

[View on GitHub](https://github.com/NachoTorresRD/floating-navbar-effect) · [Work with NTDESWEB](https://www.ntdesweb.com)
