# PeachStar Codex Pet

PeachStar is a custom Codex digital pet: a chibi human girl wearing a Cinnamoroll-themed hood, with graduation and cherry-blossom details.

This repository contains the installable pet package and a larger experimental variant.

## Variants

- `pets/peachstar`: standard version.
- `pets/peachstar-large`: larger visual version scaled inside the same Codex pet frame.

## Install

Copy one pet folder into your Codex custom pet directory:

```text
C:\Users\<your-user>\.codex\pets\
```

For example:

```text
C:\Users\<your-user>\.codex\pets\peachstar
```

Restart Codex, then select `PeachStar` or `PeachStar Large` in the pet or appearance settings.

## Files

Each pet folder contains:

- `pet.json`: Codex pet manifest.
- `spritesheet.webp`: 8 x 9 sprite atlas, 192 x 208 px per cell.

## QA

Preview contact sheets are in `docs/images/`.

The generated atlas was validated as:

- format: WebP
- mode: RGBA
- size: 1536 x 1872
- validation errors: none
- validation warnings: none

