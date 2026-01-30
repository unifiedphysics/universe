# Unified Physics: Fibonacci Spiral Filaments

An interactive 3D visualization of a theoretical universe model built with [Three.js](https://threejs.org/). The simulation renders spacetime as a torus with varying cross-section, where 13 filaments spiral along the surface following the golden angle.

## Concepts

- **Spine** -- A central thread (c-thread) tracing the torus centerline, representing the core flow of spacetime.
- **13 Filaments** -- Emerge from the spine and spiral at the golden angle (137.5°). The count follows the Fibonacci sequence.
- **Pinch Point (φ Lock)** -- Where the torus cross-section collapses to near-zero. All filaments unify before spiraling back out.
- **2012 Cross-Section** -- A disc at maximum expansion representing the observable universe.

## Usage

Open either HTML file directly in a modern browser -- no build step or server required.

- **Drag** to rotate the camera
- **Scroll** to zoom in/out
- **Controls panel** (bottom-left) to adjust auto-rotation speed and toggle visibility of the spine, filaments, and cross-section disc

## Files

| File | Description |
|------|-------------|
| `model of the universe` | Main visualization (HTML + inline JS) |
| `model of universe_by someoneonearth.html` | Alternate copy of the visualization |

## Dependencies

- [Three.js r128](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js) (loaded via CDN at runtime)

## License

[MIT](LICENSE)
