# Rachel Hua — portfolio site

A single-page portfolio, styled to match my data-portal design system
(zinc-dark, purple accent, Inter + JetBrains Mono). Live at
**https://rachelzh-hua.github.io**.

## Files

| File | What it is |
|------|-----------|
| `index.html` | The entire site — self-contained, no build step, no dependencies |
| `.github/workflows/publish.yml` | Deploys the repo to GitHub Pages on every push to `main` |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll) |

## Edit it

Everything lives in `index.html` — content, styles, and the theme toggle.
Just edit and push; the site redeploys automatically in ~30s.

Common tweaks:

- **Add a headshot** — drop an image in the repo and add an `<img>` in the hero.
- **Publications / CV** — add a `<section id="cv">` (copy an existing section as a template) or link a `cv.pdf`.
- **Social links** — the header and footer hold GitHub + email; add Scholar / ORCID / LinkedIn the same way.

## Preview locally

Just open `index.html` in a browser — no server needed.

## Deploy

Handled automatically by GitHub Actions. To publish manually you can also run
any static host (Netlify, Vercel) pointed at this repo.
