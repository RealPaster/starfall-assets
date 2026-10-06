# Starfall assets

Data assets for Starfall. This repository contains the asset
manifest; binary packs belong to the `assets-v1` GitHub release.
THE PRODUCTS WONT BE INCLUDED HERE.

## Files

- `css-realistic-v1.zip`: 26 original firing WAVs, flattened for `csgo/sound/HERE SOUNDS/`.
- `models-*.zip`: 68 reviewed packs, with paths relative to `csgo/`.
- `manifest.json`: catalog, weapon mappings, archive and file SHA-256/CRC32 values.

## Installation

Starfall downloads the selected model pack or CSS Realistic sound pack on Apply.
A background Windows worker verifies a pinned manifest and SHA-256 checksums
before installation. Archives are cached in `csgo/starfall_cache/assets-v1/`
for offline reuse and repair. A failed install preserves current profiles.
