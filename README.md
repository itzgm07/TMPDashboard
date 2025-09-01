
# Staffing Dashboard (Vite + React + TypeScript + Recharts)

**Live on GitHub Pages** with one click via Actions.

## Run locally
```bash
npm ci
npm run dev
```

## Deploy to GitHub Pages
1. Push this repo to GitHub (branch `main`).
2. Go to **Settings → Pages → Build and deployment → Source: GitHub Actions** (select it).
3. Push; the workflow `.github/workflows/deploy.yml` will build and publish to Pages automatically.
4. Open the URL shown in the **Deploy to GitHub Pages** job (something like `https://<user>.github.io/<repo>/`).

> Vite `base` is set to `./` so assets work fine on project pages.
