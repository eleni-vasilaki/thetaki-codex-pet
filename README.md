# Thetaki

Thetaki is an animated custom pet for Codex Desktop: a tiny olive-green scholar with bright curious eyes, a beloved blue book, and warm academic charm.

![Thetaki dancing and reading](preview.gif)

## Choose a version

### Thetaki Version 2 — focused reading (recommended)

During active work, Thetaki keeps the book open and reads across it: left, centre, right. The body and book remain steady, and there is no blink. This makes the brief working animation feel concentrated and purposeful before Thetaki returns to the gentler idle loop.

The repository root contains this version. It is also preserved in `versions/thetaki-version-2/`.

### Thetaki Version 1 — original

The original working animation brings the book in, opens it, blinks, and closes it. It is more energetic, but the repeated book movement can feel hurried. It is preserved in `versions/thetaki-version-1/`.

## Install

Clone or download this repository. To install the recommended Thetaki Version 2:

```bash
mkdir -p "$HOME/.codex/pets/thetaki"
cp pet.json spritesheet.webp "$HOME/.codex/pets/thetaki/"
```

To install Thetaki Version 1 instead:

```bash
mkdir -p "$HOME/.codex/pets/thetaki"
cp versions/thetaki-version-1/pet.json "$HOME/.codex/pets/thetaki/pet.json"
cp versions/thetaki-version-1/spritesheet.webp "$HOME/.codex/pets/thetaki/spritesheet.webp"
```

Open Codex Desktop and select Thetaki from the pets menu.

## Package

Each version is a validated Codex v2 pet package:

- `pet.json` — Thetaki's package manifest
- `spritesheet.webp` — the final `1536 × 2288` animated atlas using `192 × 208` cells
- `preview.gif` — the hover-to-idle animation at the atlas's native cell ratio

The design names “Thetaki Version 1” and “Thetaki Version 2” are independent of `spriteVersionNumber: 2`, which identifies the Codex 8×11 atlas format and must remain unchanged.

Thetaki is an independent community-created character.
