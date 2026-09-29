# Xingrui Chen — Portfolio

Personal portfolio: https://xingruichen794-sketch.github.io/

A static English website covering robotics, mechanical design, and experimental research. Includes six project pages, publications, supporting reports, and a downloadable résumé.

## Editing

- Homepage: `index.html`
- Project pages: `projects/<project>/index.html`
- Styles: `portfolio.css`
- Images, fonts, and PDFs: `assets/`

Preview locally with `python3 -m http.server 8000`, then open http://localhost:8000.

GitHub Pages publishes from the root of `main`. The `.nojekyll` file keeps the site as plain static files. No build step or external services are required.

Content and media belong to their respective authors. Font licenses are included in `assets/`.

## Supporting PDFs

Large PDF links currently point to the existing public portfolio. To host them here, upload these files to `assets/`, keeping these names, then replace each original-site PDF URL in the HTML with `/assets/<filename>`:

- `assets/Any-ttach-Workshop-Manuscript.pdf`
- `assets/CEER.pdf`
- `assets/Formula-SAE-Front-Wing-Paper.pdf`
- `assets/Learn-Imagine-and-Paint.pdf`
- `assets/Robot-Assisted-Stone-Dusting.pdf`
- `assets/SO101-Drawing-Technical-Report.pdf`
