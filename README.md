# Superbar website

The static site for Superbar, a Windows 7 style taskbar for macOS. Plain HTML, CSS, and JavaScript with no build step. Every picture is a real screenshot from Superbar's snapshot mode.

- `index.html` the page
- `assets/` styles, script, and screenshots
- `.github/workflows/pages.yml` deploys to GitHub Pages on every push to `main` (Settings > Pages > Source: GitHub Actions)

Preview locally:

```bash
python3 -m http.server 8765
```
