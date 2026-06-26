# Robert Winer, M.D.

Hugo site using the [Doks](https://themes.gohugo.io/themes/doks/) theme (Thulite).

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:1313

## Build

```bash
npm run build
```

Output is in `public/`.

## Deploy to GitHub Pages

1. In your repo: **Settings → Pages → Build and deployment → Source** → choose **GitHub Actions**.
2. Set your production baseURL: edit `config/production/hugo.toml` and replace `YOUR_GITHUB_USERNAME` with your GitHub username (so the site is served at `https://YOUR_GITHUB_USERNAME.github.io/robert-trebor-web/`).
3. Push to `main`; the workflow in `.github/workflows/pages.yml` will build and deploy.

## Content

- Home page: `content/_index.md`
- Docs, blog, etc. live under `content/` as usual for Hugo/Doks.
