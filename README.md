# Elisa Fazzari — academic website

Academic profile, cosmology research, publications and university teaching.

This is a Quarto website adapted from [Francesco D’Amico’s website](https://github.com/f-damico/website), retaining its page and menu structure. The original MIT licence is included in `LICENSE`.

## Edit content

| File | Content |
| --- | --- |
| `about.qmd` | Profile, portrait, education, contact and CV download |
| `projects.qmd` | Research projects and personal contributions |
| `publications.bib` | Journal bibliography |
| `publications.qmd` | Bibliography display and preprint section |
| `talks.qmd` | Talks and posters |
| `tutoring.qmd` | Teaching and mentoring |
| `foto.png` | Profile portrait |
| `docs/elisa-fazzari-academic-cv.pdf` | Downloadable short academic CV |
| `styles.css`, `light.scss`, `dark.scss` | Typography, layout and colours |
| `_quarto.yml` | Quarto configuration and menus |

The font stack is Calisto MT, Book Antiqua, Palatino Linotype, Palatino, Georgia, serif. Calisto is used on devices where it is installed; the other serif fonts are fallbacks. No commercial font files are distributed.

## Automatic publication

In the repository, choose **Settings → Pages → Source → GitHub Actions**. Enable Actions for your fork if prompted, then run **Aggiorna sito Elisa Fazzari** once. Every subsequent push to `main` rebuilds and deploys the site automatically. The workflow supports both a `website` repository and a `<username>.github.io` repository; it obtains the correct URL from GitHub Pages.

The original Scholar importer is replaced by a manual-only information workflow, so it cannot overwrite this bibliography on a schedule.

## Local preview

Install [Quarto](https://quarto.org/docs/get-started/), then run:

```bash
quarto preview
```

To generate the static site locally:

```bash
quarto render
```

The output is `_site/`. The hosted workflow uses Quarto 1.10.20.
