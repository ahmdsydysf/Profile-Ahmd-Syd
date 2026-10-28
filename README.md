# Ahmed Sayed — portfolio

Static site, no build step. `index.html` + `img/` + `_headers`.

- Deployed by Cloudflare Pages from `main` (build command: none, output directory: `/`).
- English by default, Arabic with the toggle; every visible string has a `data-i` key and its Arabic twin in the `AR` map at the bottom of `index.html` (an `aria-label` the same way with `data-ia`).
- The look follows Orion HR: a floating glass bar with the sections as pills, a gradient banner, figures as tiles, chips with counts, pill tabs. A rail at the start (a computer) or a bottom bar (a phone) holds WhatsApp, email and light / dark; the theme is kept in `localStorage` (`pf-theme`), the language in `pf-lang`.
- Screenshots in `img/` come from preview/demo builds with sample data only.

To change text: edit `index.html` (English in the markup, Arabic in `AR`). To add a screenshot: drop it in `img/` and add a `<figure class="shot">` or `<div class="wide">` next to the others. Push to `main` and Cloudflare publishes it.
