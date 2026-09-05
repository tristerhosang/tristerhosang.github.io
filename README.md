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

GitHub Pages serves the `gh-pages` branch. A workflow on `main` runs
`npm ci && npm run build` and pushes `dist/` to `gh-pages` with
`peaceiris/actions-gh-pages`; Settings → Pages → Source must stay on
"Deploy from a branch" → `gh-pages` / root.
