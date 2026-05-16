# Veleta · Upcycling moda sostenible

Sitio web para [Veleta](https://instagram.com/veletamx) · CDMX · desde 2020.

## Live

GitHub Pages: https://pedrorojascampuzano-blip.github.io/veleta-web/

## Stack

- HTML5 estándar, sin build step
- Lenis 1.0 smooth scroll
- GSAP 3.12 + ScrollTrigger plugin
- Vanilla JS para cursor-veleta y veleta gigante interactiva
- Gemini Nano Banana Pro para imágenes generadas (brújula + transiciones espuma/arena)

## Estructura

- `index.html` · página principal (v9, 2026-05-15)
- `assets/feed/individuales/` · fotos producto reales del feed @veletamx
- `assets/generated/` · imágenes generadas con Gemini para hero y dividers
- `assets/veleta/` · logo brand

## Build & Deploy

Standalone HTML, abrir directo en browser o servir con cualquier static host:

```bash
open index.html
# o
python3 -m http.server 8000
```

GitHub Pages se actualiza automáticamente al push a `main`.
