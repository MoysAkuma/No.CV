# No.CV

No.CV is a simple static website I built as an easy way to show my CV and professional profile.

## What this repository contains

- A one-page personal site with these sections:
	- About Me
	- Projects
	- Professional Experience
	- Contact Information
- Downloadable resumes in two languages:
	- `CV-EN.pdf`
	- `CV-ES.pdf`

## Tech stack

- HTML + CSS + Vanilla JavaScript
- Vue 3 (CDN, lightweight app mount)
- Font Awesome (social icons)
- Google Fonts (Press Start 2P)

## Project structure

- `index.html`: full portfolio/CV website
- `CV-EN.pdf`: English resume
- `CV-ES.pdf`: Spanish resume
- `.github/workflows/pages.yml`: GitHub Pages deployment workflow (GitHub Actions)
- `.nojekyll`: disables Jekyll processing for static hosting

## Run locally

This is a static site, so you can open `index.html` directly in your browser.

If you prefer a local server, use VS Code Live Server or any static server.

## Deployment (GitHub Pages)

This repo deploys using GitHub Actions (not Jekyll build container).

Required setting:

1. Go to **Settings → Pages** in the repository.
2. Set **Source** to **GitHub Actions**.
3. Push to `main` (or run the workflow manually).

## Contact

- Email: `moises.moran.dev@gmail.com`
- GitHub: `https://github.com/moysakuma`
- LinkedIn: `https://www.linkedin.com/in/moysakuma/`
