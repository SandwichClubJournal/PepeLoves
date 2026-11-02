# PepeLoves

A cheerful, responsive landing page built with plain HTML, CSS, and JavaScript-free interactions. No package installation or build step is required.

## Run locally

Open `index.html` in a browser, or start a local web server from the repository root:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Build

There is no compilation step. The deployable site is the repository root; the GitHub Pages workflow publishes these static files.

## Deploy to GitHub Pages

1. In the repository's **Settings → Pages**, choose **GitHub Actions** as the build and deployment source.
2. Push to the `main` branch, or run the **Deploy PepeLoves to GitHub Pages** workflow manually from the Actions tab.
3. After the first successful workflow, GitHub Pages will show the published site URL in **Settings → Pages**.

The workflow in `.github/workflows/pages.yml` publishes the repository root and requires no third-party build dependencies.

## Project structure

- `index.html` — page content and accessible navigation
- `styles.css` — responsive layout, colors, and motion preferences
- `favicon.svg` — lightweight site icon
- `.github/workflows/pages.yml` — automated GitHub Pages deployment
