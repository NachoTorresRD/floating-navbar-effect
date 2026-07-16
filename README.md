# Floating Navbar Effect

![Vista previa](assets/preview.svg)

Barra de navegación flotante que se compacta al desplazarse, marca la sección activa y ofrece menú móvil accesible.

## Características

- Estado visual al hacer scroll.
- Sección activa mediante `IntersectionObserver`.
- Menú móvil con Escape, clic exterior y retorno de foco.
- Navegación por anclas y teclado.

## Demo en vivo

[floating-navbar-effect.netlify.app](https://floating-navbar-effect.netlify.app)

## Instalación

Clona el repositorio, entra en `floating-navbar-effect` y abre `index.html`.

## Estructura del proyecto

Navegación y secciones en `index.html`, responsive en `style.css`, estados en `script.js` y SVG en `assets/`.

## Cómo personalizarlo

Añade anclas y secciones con IDs coincidentes; adapta `rootMargin` para cambiar cuándo se activa cada enlace.

## Accesibilidad

Usa `nav`, `aria-current`, `aria-expanded`, cierre con Escape, objetivos táctiles y foco visible.

## Rendimiento

El estado de scroll usa un frame pendiente y la sección activa se resuelve sin cálculos continuos.

## Licencia y créditos

[MIT](LICENSE). Creado por [Nacho Torres](https://github.com/NachoTorresRD) para [NTDESWEB](https://www.ntdesweb.com) con [NT-SKILL SUPREME](https://github.com/NachoTorresRD/nt-skill-supreme).

[Ver en GitHub](https://github.com/NachoTorresRD/floating-navbar-effect) · [Trabajar con NTDESWEB](https://www.ntdesweb.com)
