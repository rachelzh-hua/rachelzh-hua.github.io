# Rachel Hua — portfolio site

A [Quarto](https://quarto.org) website scaffolded with your real GitHub projects.

## Files

| File | What it is |
|------|-----------|
| `_quarto.yml` | Site config: title, navbar, theme |
| `index.qmd` | Home / about page |
| `projects.qmd` | Project grid (genomics pipelines + reanalysis portals) |
| `cv.qmd` | CV page (placeholder — fill in) |
| `styles.scss` / `styles.css` | Theme colors + project-card styling |
| `profile.jpg` | **Add** a square headshot (or remove the `image:` line in `index.qmd`) |

## Preview locally

1. Install Quarto: <https://quarto.org/docs/get-started/>
2. From this folder:

   ```bash
   quarto preview        # live-reloading local preview
   quarto render         # build static site into _site/
   ```

## Publish to GitHub Pages (free)

```bash
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/rachelzh-hua/rachelzh-hua.github.io.git
git push -u origin main
```

Then either:

- **Easiest:** run `quarto publish gh-pages` (handles the build + branch), or
- In the repo Settings → Pages, set the source and let Quarto's
  [GitHub Pages guide](https://quarto.org/docs/publishing/github-pages.html) do the rest.

Naming the repo `rachelzh-hua.github.io` makes it your root user site at
`https://rachelzh-hua.github.io`.

## To do

- [ ] Add `profile.jpg`
- [ ] Fill in `cv.qmd` (education, publications) or link a `cv.pdf`
- [ ] Uncomment Scholar / ORCID / LinkedIn links in `index.qmd`
- [ ] Update `site-url` in `_quarto.yml` if you use a custom domain
