# Visual credits and production record

## Original artwork

Created with the built-in `image_gen` tool in Codex on 22 October 2026. The tool exposed `image_url` and `output_hint`; **no actual model identifier was exposed**, so no model version is asserted.

- Selected cover: `assets/cover-master.png`; exact prompt `cover-v2-prompt.txt`.
- Vehicle options: `assets/vehicle-options.png`; exact prompt `vehicle-options-final-prompt.txt`.
- Rejected first cover: `assets/cover-rejected-yellow.png`; exact prompt `cover-prompt.txt`. Do not publish.
- Art direction: Relay V2, `projects/social-and-community/visuals-v2/PROMPTS.md`. Both generation prompts carry the verbatim STYLE block. Selected images use paper-white, graphite and small emerald physical accents; no generated typography or people.
- Cover formats add original typesetting in HTML/CSS. The master artwork is unchanged. Original source files are retained. See `visuals.html` and `render.mjs`.

## Street map and interface

The app screen is an original code-authored UI concept, not a screenshot of a live product. It was rendered with MapLibre GL using OpenFreeMap's Positron style over a real Ikoyi, Lagos street map. Vehicle icons and marker placements are synthetic; no real rider data is included. Map attribution is visible within the screen and in the article credits.

- Tiles/style: https://tiles.openfreemap.org/styles/positron
- OpenFreeMap: https://openfreemap.org/quick_start/
- OpenMapTiles: https://openmaptiles.org/
- Map data: © OpenStreetMap contributors, https://www.openstreetmap.org/copyright (ODbL).
- Rendering: MapLibre GL, https://maplibre.org/ (BSD 3-Clause).
- Vehicle selector icons: original SVG paths in `visuals.html`; no third-party icon pack.

`assets/lagos-basemap-reference.png` was inspected as an existing repository reference but is not used in the final app-screen image. The final screen uses a fresh, closer street-map rendering for readability. No Google Maps image, stock photograph, Mobbin screenshot or Dribbble artwork is used.

## Fonts

Geist Regular and SemiBold from the existing Relay website assets. Source project: https://github.com/vercel/geist-font. SIL Open Font License; license included at `assets/Geist-LICENSE.txt`. Headlines, captions, interface labels and credits are typeset after generation.

## Asset integrity

`SHA256.json` records the local media and font files. Website WebP exports are encoded at quality 88; local PNG originals are preserved.
