# Saeed Anwar — Web Development Portfolio

A lightweight single-page portfolio for freelance web design and development projects. The site is built with plain HTML, CSS, and JavaScript, so it has no build step or installation requirements.

## Run locally

Open `index.html` in a browser, or serve the folder with any static web server:

```bash
python -m http.server 8000
```

Then visit: http://localhost:8000

## Deploy

Because this is a static site, it can be deployed to any static host such as Vercel, Netlify, or GitHub Pages. Keep the project images alongside `index.html` so the previews continue to load correctly.

## Files

- `index.html` — page structure, styling, and light JavaScript interactions.
- `motorforge.webp` and `roofing.webp` — large project preview images.
- `saeed-photo.png` and `*-shot.jpg` — supporting imagery for the page.
- `favicon.svg` — browser icon used for the site.
- `site.webmanifest` — installable web app metadata.

## Notes

- The page uses Google Fonts with system-font fallbacks.
- The scroll-reveal effects are decorative and do not block content access.
- The contact section highlights email and profile links for prospective clients.
