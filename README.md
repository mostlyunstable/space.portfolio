# Mayank Kumar — Personal Portfolio

A multi-page personal website with a warm editorial design, first-person writing, selected projects, and experience.

## Run locally

No build step or package installation is required. From this directory, run:

```sh
python3 -m http.server 4173
```

Open http://localhost:4173 in your browser.

## Pages

- `/` — Home
- `/story/` — About me
- `/work/` — Projects and websites
- `/work/leylegal/` — Leylegal
- `/work/originx/` — OriginX
- `/work/electralens/` — ElectraLens
- `/experience/` — Experience and education

## Editing

Each page is an `index.html` file in its corresponding directory. Shared styles live in `styles.css`; the homepage interaction lives in `main.js`. Company marks are stored locally in `assets/` and belong to their respective owners. Fonts are loaded from Google Fonts, with local fallback fonts.

## Deployment

Serve this repository as a static website from the domain root. No build command is required. Paths begin with `/`, so a subdirectory deployment (such as a default GitHub Pages project URL) requires adjusting asset and navigation paths or using a custom domain. Configure the host to serve `404/index.html` for missing pages if supported.
