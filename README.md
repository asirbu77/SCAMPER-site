# SCAMPER project page

Static site for the SCAMPER paper, served at `https://asirbu77.github.io/SCAMPER-site/`.

## Local development

```sh
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000/SCAMPER-site/>.

## Editing content

- Paper metadata (title, authors, affiliations, links): `_config.yml`
- Page content (abstract, figures, videos, BibTeX): `index.html`
- Figures: drop into `assets/figures/` (prefer SVG; PDFs work via `<object>`)
- Videos: drop into `assets/videos/` as MP4

## Deploy

Push to `main` on the `asirbu77/SCAMPER-site` repo and enable GitHub Pages in
Settings → Pages → Build from `main` branch.
