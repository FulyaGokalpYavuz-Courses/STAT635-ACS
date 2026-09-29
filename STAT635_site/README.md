# STAT 635 Advanced Computational Statistics: course site (STAT635_site)

Preview locally: `quarto preview`
Build: `quarto render` (output in `_site/`)

## Adding a week
1. Copy `weeks/_template.qmd` to `weeks/week-02.qmd`.
2. Set `title`, `description`, and `order` (the week number).
3. It appears on the Weekly Schedule page automatically.

## Publishing
Push to `main` on GitHub. The workflow in `.github/workflows/publish.yml` publishes to GitHub Pages
(first time: run `quarto publish gh-pages` once, then set Pages to serve the `gh-pages` branch).
