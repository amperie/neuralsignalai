# NeuralSignal AI Website

Static site scaffold for deployment on Cloudflare Pages from a GitHub repository.

## Repository setup

1. Initialize git if needed:
   `git init`
2. Create a GitHub repo and push this directory.
3. In Cloudflare Pages, connect the GitHub repo.

## Cloudflare Pages settings

- Framework preset: `None`
- Build command: leave blank
- Build output directory: `public`

## Local structure

- `public/index.html`
- `public/styles.css`
- `public/app.js`

## Local preview

Any static file server works. For example, from the repo root:

```powershell
python -m http.server 8000 --directory public
```

