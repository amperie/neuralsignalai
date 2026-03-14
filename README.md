# NeuralSignal AI Website

Hugo site scaffold for deployment on Cloudflare Pages from a GitHub repository.

## Local development

Install Hugo extended, then run:

```powershell
npm run dev
```

## Tooling

This repo installs local CLI dependencies through npm:

- `hugo-bin`
- `wrangler`

Useful commands:

```powershell
npm run build
npm run cf:login
npm run cf:pages:create
npm run cf:deploy
```

## Cloudflare Pages settings

- Framework preset: `Hugo`
- Build command: `hugo`
- Build output directory: `public`

## Site structure

- `hugo.toml`
- `content/_index.md`
- `layouts/index.html`
- `static/styles.css`
- `static/app.js`
