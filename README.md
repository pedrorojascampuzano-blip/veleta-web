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

- `index.html` · página principal (v10, 2026-05-30)
- `assets/feed/individuales/` · fotos producto reales del feed @veletamx
- `assets/generated/` · imágenes generadas con Gemini para hero y dividers
- `assets/veleta/` · logo brand
- `assets/nuestro-barco/` · velero blanco (de la carpeta Drive "Nuestro barco")
- `veleta-pagina-v9-backup-2026-05-30.html` · respaldo de la versión anterior antes de v10

## v10 · 2026-05-30

Integra el contenido real de la carpeta Drive del cliente (brief `Contenido_pagweb_veleta.docx` + carpeta `Nuestro barco`):

- **Megamenú TIENDA** con la taxonomía real de producto (Tienda, Ropa, Estuches Nautilus, Bolsas, Accesorios).
- **Nuestro Barco** (sección 05): header cyan con velero, historia de la fundadora en primera persona (Catemaco, 18°25′N 95°5′W), tripulación de 5 con bio (canción / disfruta / sueño), y banda "hemos reutilizado" con números reales.
- **Números corregidos**: +59 materiales reutilizados, +2,000 piezas, 8 tipos de material (antes decía 188 piezas / 7 materiales, datos genéricos).
- **Diario** (sección 06): 3 artículos del blog + newsletter.
- **Footer completo** (BLOQUE 6): contacto real (navegar@veleta.com.mx, Artículo 123 #116, Centro, CDMX 06040), Tienda, Ayuda (FAQ, Stockists, T&C), Síguenos (Instagram, TikTok, YouTube).

Pendiente / a confirmar con Jimena:
- Handles de TikTok y YouTube asumidos como `@veletamx` (confirmar).
- Fotos de tripulación: la carpeta Drive tiene fotos sin etiquetar (`IMG_*.HEIC`); por ahora se usan avatares-brújula del brand. Mapear cara→nombre requiere confirmación.
- Links de Tienda/Diario apuntan a Instagram (no hay e-commerce ni blog en vivo todavía).

## Build & Deploy

Standalone HTML, abrir directo en browser o servir con cualquier static host:

```bash
open index.html
# o
python3 -m http.server 8000
```

GitHub Pages se actualiza automáticamente al push a `main`.
