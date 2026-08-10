# Secondhand King

A browser-based indie game prototype about turning a beggar into a wealthy secondhand trader.

You inspect used items, decide whether the seller price is below a hidden reference price, travel to the trade location in first person, and return home if an anomaly appears. The anomaly prototype includes people standing on their heads, inspired by Exit 8-style contradiction spotting. The trade flow borrows the inspection-pressure feeling of Papers, Please.

## Features

- Low-poly 3D item inspection with scratches, dents, stains, and labels.
- Computer seller and player-style seller modes.
- First-person route segment with anomaly detection and a bad ending.
- ESC chat screen with cancel, postpone, and continue actions.
- Profit loop with daily rice cost and upgrades for items, clothing, and buildings.
- GitHub Pages deploy workflow included.

## Run Locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite.

## Build

```bash
npm run build
```

The production build is written to `dist/`.

## GitHub Upload

Upload this project folder to a GitHub repository, including:

- `.github/workflows/deploy.yml`
- `assets/`
- `src/`
- `index.html`
- `package.json`
- `package-lock.json`
- `vite.config.js`

Do not upload `node_modules/`, `.npm-cache/`, or `dist/`.

For GitHub Pages, go to the repository settings and set Pages to use GitHub Actions. The included workflow builds and deploys the game automatically after pushing to `main`.

## QA Shortcut

Add `?forceAnomaly=1` to the URL to force the headstand-people anomaly during the route segment.
