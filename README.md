# tristerhosang.github.io

Trister Hosang's portfolio site, built with [Vite](https://vite.dev), React and TypeScript.

## Requirements

Node.js 22 (see `.nvmrc`; run `nvm use` if you use nvm).

## Getting started

```bash
npm install
npm run dev      # start the dev server at http://localhost:5173
npm run build    # type-check and build to dist/
npm run preview  # serve the production build locally
npm run lint     # run oxlint
```

## Deployment

Pushes to `main` build the site and publish `dist/` to GitHub Pages via
`.github/workflows/deploy.yml`. In the repository settings, under Pages, set the
source to "GitHub Actions".
