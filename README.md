# Starfall assets

Data assets for Starfall / Allegro 0.1 Preview. This repository contains the asset
manifest; binary packs belong to the `assets-v1` GitHub release.

Upload every ZIP from the adjacent `release` folder as an attachment to that release.
Upload this folder's `manifest.json`, `.gitignore`, and README to the repository.
The Lua script itself is not included.

## Files

- `css-realistic-v1.zip`: 26 original firing WAVs, flattened for `csgo/sound/HERE SOUNDS/`.
- `models-*.zip`: 68 reviewed packs, with paths relative to `csgo/`.
- `manifest.json`: catalog, weapon mappings, archive and file SHA-256/CRC32 values.

Stock game models are referenced in the catalog and are not redistributed.
The Warzone SSG08 pack uses the corrected `models/starfal/` namespace.
Model source URLs are recorded per pack. Sounds are from the supplied
CSS Realistic Weapons Sounds archive; audio bytes are unchanged.

This is a publication bundle, not yet a connected Lua downloader. Configure the
repository URL in the downloader after publication. Local cached assets should
remain usable if downloading fails.
