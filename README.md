# Lab 4 — Astro SSG (Static Only)

This repo is the migrated landing page using **Astro** as a Static Site Generator (SSG).

## Requirements covered

- Static output only (no SSR)
- No React/Vue/etc. integrations
- GitHub Pages-ready via `site` + `base` in `astro.config.mjs`
- Clean structure: `src/layouts`, `src/components`, `src/pages`, `public`

## Setup

```bash
npm install
```

## Run locally (dev)

```bash
npm run dev
```

Astro will print the local URL (usually `http://localhost:4321`).

## Build (static)

```bash
npm run build
```

The static site output will be in `dist/`.

## Preview the build

```bash
npm run preview
```

## GitHub Pages config

Edit `astro.config.mjs`:

- `site`: `https://<your-username>.github.io`
- `base`: `/<repo-name>/`

Example:

- `site: 'https://sanduta.github.io'`
- `base: '/lab4-ssg/'`
