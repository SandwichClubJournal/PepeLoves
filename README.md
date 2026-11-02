# PepeLoves

A static clone of the live `#PepeLoves` site, including the landing page, social links, embedded music player, and the interactive glassmorphism layout.

## Run locally

Open `index.html` directly in a browser, or serve the repository root locally:

```powershell
& "$env:LOCALAPPDATA\Microsoft\WindowsApps\python.exe" -m http.server 8000
```

Then visit <http://localhost:8000>.

## Project structure

- `index.html` — cloned `#PepeLoves` page markup and sections
- `assets/` — local copies of the site’s CSS, JS, and imagery
- `favicon.svg` — lightweight fallback site icon
- `.github/workflows/pages.yml` — GitHub Pages deployment configuration
