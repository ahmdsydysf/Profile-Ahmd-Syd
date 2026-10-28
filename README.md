# Ahmed Sayed — portfolio

Static site, no build step. `index.html` + `img/` + `_headers`.

- Deployed by Cloudflare Pages from `main` (build command: none, output directory: `/`).
- English by default, Arabic with the toggle; every visible string has a `data-i` key and its Arabic twin in the `AR` map at the bottom of `index.html`.
- Screenshots in `img/` come from preview/demo builds with sample data only.

To change text: edit `index.html` (English in the markup, Arabic in `AR`). To add a screenshot: drop it in `img/` and add a `<figure class="shot">` or `<div class="wide">` next to the others. Push to `main` and Cloudflare publishes it.
