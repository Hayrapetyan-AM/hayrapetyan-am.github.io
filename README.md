# hayrapetyan-am.github.io

Personal site for **Armen Hayrapetyan** — Backend Developer (PHP / Laravel), Yerevan, Armenia.

Live at <https://hayrapetyan-am.github.io/>

## Structure

```
index.html                        single page: hero, about, skills, experience, projects, contact
css/style.css                     all styling, hand-written
images/armen.jpg                  portrait (600x600, optimised)
images/1687718897328.png          original portrait source
assets/Armen_Hayrapetyan_Backend_Developer_CV.pdf   downloadable CV
```

## Notes

- **No dependencies.** No Bootstrap, no jQuery, no CDN, no web fonts, no trackers.
  The whole page is one HTML file plus one stylesheet.
- **Static only** — served by GitHub Pages from the `master` branch root.
- Responsive down to phone widths, with a dark mode via `prefers-color-scheme`.
- Content mirrors the CV in
  [`../cv/backend-php.md`](https://github.com/Hayrapetyan-AM) so the two never drift.

## Local preview

```sh
python -m http.server 8000
# then open http://localhost:8000/
```

## Updating

Edit `index.html` directly. To refresh the downloadable CV, replace the PDF in `assets/`.

## History

This repo previously contained an unmodified TemplateMo "First Portfolio" theme, including
placeholder content (fabricated statistics, stock project images, third-party client logos and
another person's contact details in the footer). It was rebuilt from scratch on 2026-10-10.
