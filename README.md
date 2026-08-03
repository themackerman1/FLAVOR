# FLAVOR

A single-page GitHub Pages app.

## Files

- `index.html` — complete app
- `icon.svg` — browser favicon and visible app tile
- `icon-192.png` / `icon-512.png` — installable app icons
- `apple-touch-icon.png` — iPhone/iPad home-screen icon
- `manifest.webmanifest` — installable web-app metadata

## GitHub Pages

Upload every file in this folder to the root of your GitHub repository, then enable GitHub Pages from the `main` branch and `/ (root)` folder.

## Latest changes

- Removed the Total Damage summary card.
- Share output now includes only the six-digit code and emoji/classification.
- Music button labels are START MUSIC / STOP MUSIC.
- Browser page title is FLAVOR.

- Replaced numbered score buttons with glowing pixel equalizer blocks.
- Added subtle block pulse, stronger CRT scanlines/bloom, and animated gas crime code digits.


Latest tweak: reduced selected block pulse by approximately 50% for a subtler CRT arcade effect.

## 256-classification system

The final classification is now derived deterministically from the complete six-digit FLAVOR code rather than only the summed score.

- 256 unique classification names
- 256 unique descriptions
- Stable result: the same six-digit code always produces the same classification
- Shared output remains only the score code and emoji/classification
