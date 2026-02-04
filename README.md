# hytopia-audio-assets

Game audio assets + generator recipes.

## Structure

- `sfx/` – exported sound effects (WAV/OGG)
- `meta/` – JSON recipes (preset, seed, params, engine version)

## Notes

- Binary audio files are stored using **Git LFS** (`*.wav`, `*.ogg`).
- Prefer short, game-ready one-shots (avoid multi-second tails unless intentional).
