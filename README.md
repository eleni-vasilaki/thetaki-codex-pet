# Thetaki

Thetaki is an animated custom pet for Codex Desktop: a tiny olive-green scholar with bright curious eyes, a beloved blue book, and warm academic charm.

| Left-side Thetaki | Right-side Thetaki |
| --- | --- |
| ![Thetaki facing inward from the left](previews/left-side-idle.gif) | ![Thetaki facing inward from the right](previews/right-side-idle.gif) |

## Choose the placement

### Left-side Thetaki

Use this package when Thetaki sits on the left side of the window. The idle sequence faces screen-right, inward toward the workspace.

The repository root contains this package.

### Right-side Thetaki

Use this package when Thetaki sits on the right side of the window. Its idle sequence faces screen-left, inward toward the workspace.

The right-side package mirrors the six idle animation frames and the neutral idle pose without reversing their timing. Every other animation—including focused reading, hover, movement, reactions, and directional gaze—remains identical to Left-side Thetaki.

It is stored in `right-side/`.

These are two placement variants of the same design, not numbered releases.

## Install

Clone or download this repository.

To install Left-side Thetaki:

```bash
mkdir -p "$HOME/.codex/pets/thetaki"
cp pet.json spritesheet.webp "$HOME/.codex/pets/thetaki/"
```

To install Right-side Thetaki:

```bash
mkdir -p "$HOME/.codex/pets/thetaki-right"
cp right-side/pet.json right-side/spritesheet.webp "$HOME/.codex/pets/thetaki-right/"
```

The packages have distinct identifiers, so both may be installed together and selected separately from the pets menu.

## Package

Each placement variant is a validated Codex v2 pet package containing:

- `pet.json` — Thetaki's package manifest
- `spritesheet.webp` — the `1536 × 2288` animated atlas using `192 × 208` cells

`spriteVersionNumber: 2` identifies the Codex 8×11 atlas format; it is not a Thetaki release number.

Thetaki is an independent community-created character.
