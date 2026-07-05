# Brand assets

This folder is where the EnsinoLibre logo files live once they are added. Other files in this org (the profile page, per-repo READMEs) already reference the exact paths below, so dropping in files with these names is enough to make the logos appear everywhere.

## Files needed

| File | Used for | Format | Notes |
|------|----------|--------|-------|
| `ensinolibre-wordmark.png` | Light-mode wordmark, shown in READMEs | PNG, transparent background | Roughly 880×200px (2x for a 440px display width) |
| `ensinolibre-wordmark-dark.png` | Dark-mode wordmark, shown in READMEs | PNG, transparent background | Same dimensions as above, light-colored text/mark for dark backgrounds |
| `ensinolibre-icon.svg` | Favicon, small in-app mark, README badges | SVG | The leaf/book mark alone, no wordmark, square canvas |
| `ensinolibre-avatar.png` | GitHub org avatar (uploaded in org settings, not referenced by any README) | PNG, square | 512×512px minimum, GitHub requires PNG or JPG for org avatars, SVG is not accepted there |

## Brand colors to use

Pull these from [`design-system`](https://github.com/ensinolibre/design-system):

- Primary teal: `#1f6f5c` (light backgrounds) / `#4bb298` (dark backgrounds)
- Wordmark text: warm neutral dark `#22221e` on light, `#fffdf7` on dark

## Source

If you have the original logo file (vector source, Figma, or similar), export the four files above at the specs listed and commit them directly to this folder. No other changes are needed. Once these files exist, the pictures in [`profile/README.md`](../profile/README.md) and this repo's own `README.md` will render automatically.
