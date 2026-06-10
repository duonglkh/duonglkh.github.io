# hidev-io.github.io

> Source of [hidev-io.github.io](https://hidev-io.github.io) — personal site of **Hidev** (Hung Duong).

Built with [Astro 5](https://astro.build) · [Keystatic](https://keystatic.com) CMS in dev · GitHub Pages deploy via Actions.

## Develop

```bash
npm install
npm run dev
# → http://localhost:4321/
# → http://localhost:4321/keystatic   (admin UI, dev only)
```

## Build

```bash
npm run build       # output to dist/
npm run preview     # serve dist/ locally
```

## Deploy

Push to `main` → `.github/workflows/deploy.yml` builds + publishes to GitHub Pages.

## Structure

- `src/pages/` — routes
- `src/components/` — Astro + a few React (dev-only) components
- `src/content/` — collections (`courses`, `projects`, `extensions`, `tokenTools`, `shorts`)
- `src/styles/global.css` — cosmic theme tokens, animations, layout variants
- `public/` — static assets (avatar, QR codes, claude-roadmap.html)

## License

Code: MIT · Content: All rights reserved unless stated otherwise.
