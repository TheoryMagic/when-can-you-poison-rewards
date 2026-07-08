# When Can You Poison Rewards? — website package v16

This package keeps the supplied `index.html` unchanged and only updates the experiment figure asset.

## What changed

- Replaced `assets/attackable-HC-composite-full.png` with a new combined result figure generated from the uploaded attackable and intrinsically robust HalfCheetah PDFs.
- Kept the current HTML structure and text unchanged.
- Removed unused assets; the package only includes files referenced by `index.html`.
- Kept the four multi-frame GIFs used by the behavior overview:
  - `before-attack.gif`
  - `target-policy.gif`
  - `attack-success.gif`
  - `intrinsic-robustness.gif`

## Upload to GitHub Pages

Upload these items to the repository root:

- `index.html`
- `README.md`
- `assets/`

For a clean update, delete the old `assets/` folder first, then upload this package's `assets/` folder.
