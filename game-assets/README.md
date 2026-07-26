# Game Assets

This directory contains browser-ready assets generated from `../素材`.
The original source files are intentionally left unchanged.

## Layout

- `backgrounds/`: full-screen background, kept opaque and uncropped
- `characters/player/`: player swim and rise animation frames
- `characters/summon/`: YYB summon animation frames
- `enemies/`: three-frame enemy animations
- `effects/`: bullet and bomb animation frames
- `ui/`: chest, choice panel, and heart states
- `world/`: dragon gate and wave obstacles; `wave-variants-sheet.png` is a
  reference collage rather than a regular frame grid
- `manifest.json`: paths and processed pixel dimensions

All foreground PNG files have a real alpha channel and tight transparent bounds.
Regenerate them with `python tools/prepare_assets.py`.
