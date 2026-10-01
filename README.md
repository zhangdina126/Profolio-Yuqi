# YUQI — Fashion Designer · Textile & Print

Yuqi Zhang's Milan-based fashion portfolio, focused on material-led design.

## Homepage

- Soft Boundaries — SS26 graduate collection; womenswear, textile and print.
- Dedar Milano — The Garden in a Room; academic textile and surface design proposal.
- IOC × Milano Cortina 2026 × Brera — The Traces of Silence; outerwear and material research.

Il Sogno di Luce e Ombra is referenced in the biography as further work.
The original responsive layout, CSS and native expandable project cards are preserved.
Contact currently links to Instagram @kawawappa_.

## Images to supply

There are no original project photographs in this repository yet. The homepage uses explicitly labelled text covers. `form-feeling.webp` is the previous concept artwork and is no longer displayed.

Upload original images to `images/` using these suggested filenames:

| Filename | Content | Recommended export |
| --- | --- | --- |
| `soft-boundaries-cover.webp` | Strong collection photograph, preferably a landscape composition or two looks together | 2400 × 1200 px |
| `dedar-milano-cover.webp` | Textile samples, surface detail or final project presentation | 1600 × 1200 px |
| `ioc-cortina-cover.webp` | Finished cape-coat look, with its integrated scarf visible | 1600 × 1200 px |

WebP or JPEG is suitable; aim for approximately 300–800 KB per cover. These are suggested exports, not mandatory crops: retain full garments and important textile details. Supply portrait originals as well if a landscape crop would cut off the design. Cover areas vary with viewport, so leave room around the focal point.

Optional project detail images: 2–4 per project, around 1600–2000 px on the long edge. For Soft Boundaries, include embroidery/print details and development; for Dedar, textile surfaces and a presentation view; for IOC, the full silhouette and construction/material details.

Uploading alone will not change the text covers. Replace the placeholder inside each `.project-art` with an image, add descriptive alt text, and use scoped `object-fit` styling to preserve the card layout. There are currently no broken image references.

## Files and hosting

- `index.html`: homepage copy and project structure
- `style.css`: existing responsive styles, unchanged in the 1 October 2026 content update
- `.nojekyll`: static GitHub Pages marker

The site needs no build step and uses relative asset URLs. For GitHub Pages, use Settings → Pages → Deploy from a branch → `main` → `/(root)`.
