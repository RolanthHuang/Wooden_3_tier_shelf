# Wooden 3 Tier Shelf

[Open the interactive 3D viewer](https://rolanthhuang.github.io/Wooden_3_tier_shelf/)

A photo-guided reconstruction of a three-tier wooden shelf. Rotate and zoom the model to inspect the slatted shelves, support rails, corner posts, and fasteners against a neutral studio background.

## Controls

- Drag to rotate.
- Scroll or use the + / − buttons to zoom.
- Right-drag to pan. On touch screens, use one finger to rotate and two fingers to zoom or pan.
- Select perspective, front, side, back, top, or underside views.
- Toggle automatic rotation; dragging or selecting a view stops it.

## Implementation

The viewer uses Three.js r180, TSL node materials, and a renderer configured with `forceWebGL: true` to use the WebGL2 backend. Geometry and procedural wood textures are included in `index.html`; no external assets or CDN requests are needed.

Open `index.html` in a modern browser with WebGL2 and graphics acceleration enabled, or visit the GitHub Pages link above. The app stops continuous rendering when idle and pauses when hidden.

## Reconstruction limits

The model was built from five reference photographs. Dimensions, joints, and grain are approximations; it is not a measured CAD model or a photogrammetry scan. Each shelf contains nine inner slats, plus the side frame rails. Original reference photographs are not included in this repository.

Three.js is distributed under the MIT license; see [THREE-LICENSE.txt](THREE-LICENSE.txt).
