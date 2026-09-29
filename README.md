# kristin-jankowsky website

Personal academic website, built with [Quarto](https://quarto.org) and published via GitHub Pages.

## Structure
- `index.qmd` – Home (bio, research interests, news)
- `research.qmd` – Focus areas and projects
- `publications.qmd` – Publication list (edit here; bold your name with `**Jankowsky, K.**`)
- `teaching.qmd` – Courses and supervision
- `cv.qmd` – CV
- `imprint.qmd` – Imprint & privacy
- `_quarto.yml` – Navigation, site settings
- `styles.scss` – Colours and typography
- `img/` – Portrait and favicon
- `.github/workflows/publish.yml` – Renders and publishes on every push to `main`

## Deploy (once)
1. Create a repository named `KriJanko.github.io` on GitHub (public).
2. Upload all files of this folder (incl. the hidden `.github` folder) to the `main` branch.
3. In the repo: Settings → Pages → "Build and deployment" → Source: *Deploy from a branch*, Branch: `gh-pages` / root. (The branch appears after the first Action run, ~2 min.)
4. Site is live at https://krijanko.github.io

## Edit later
Edit the `.qmd` files (Markdown) in RStudio or any editor, commit, push – the site rebuilds automatically.
Local preview: `quarto preview` in this folder.
