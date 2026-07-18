# Kaiju Forge

An AI-assisted 2D sprite studio for [Titan Sandbox](https://fabianb14.github.io/TitanSandbox/).
Paint, generate, and animate custom kaiju skins — then send them straight into
the game.

**Use it:** https://fabianb14.github.io/kaiju-forge/

## Features

- **Part editor** — paint each of the 9 rig parts (torso, head, jaw, arm, leg,
  3 tail segments, wings) for any of the 7 kaiju: brush/eraser with softness,
  fill, drag-gradient, speckle texture brush, outline & glow effects, HSL
  adjust, image import with drag/scale/stamp, undo/redo, proportion guides.
- **Gemini AI** — paste your Google AI Studio key (stored only in your
  browser): generate a part from a description, or send your current drawing
  with an instruction ("make the fins glow blue") and get an edited version
  back as a draggable object. Style presets + green-screen background removal.
- **Live rig preview** — the assembled kaiju animates with the game's rig
  (idle / walk / roar / turn) while you edit.
- **VFX lab** — particle emitter designer with presets, live preview, and
  vfx.json export.
- **SFX lab** — synthesize roars, klaxons, lasers and booms; play and export
  as .wav.
- **Send to Titan Sandbox** — one tap hands your painted parts to the game
  through shared browser storage (both apps live on the same domain). Open
  the game and your kaiju is wearing them. Or export a `sprites.zip` that
  drops into the game repo's `sprites/` folder.
- Projects autosave locally and export/import as `.kaijuforge` files.

## Development

- `main` — default branch, deployed to GitHub Pages on every push.
- `fabian-branch` — working branch.

## Legal

Only create and ship art you have the rights to. The forge itself contains no
third-party characters or trademarks.
