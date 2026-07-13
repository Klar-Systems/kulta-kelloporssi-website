# Helsingin Kulta- & Kellopörssi — website

Single-page site for **Helsingin Kulta- & Kellopörssi**, a traditional gold & watch
shop in Punavuori, Helsinki (Iso Roobertinkatu 9, est. 1993). Informational only —
tells about the shop, opening hours, phone and location. No products, no reviews.

## Stack
Static HTML/CSS/JS. No build step. Google Fonts (Cormorant Garamond + Jost) via CDN.
Photography in `images/` (freely-licensed, Unsplash). A small live gold-price ticker
pulls spot XAU (gold-api.com) and USD→EUR (frankfurter.dev), and hides itself if either
feed fails.

## Structure
- `index.html` — the whole page
- `images/` — hero-watch, gentleman, detail-watch, jewelry, rings, pocketwatch

## Preview
Live preview: https://preview.klarsystems.com/kulta-kelloporssi/
(served from the shared `klar-websites-previews` repo — copy `index.html` + `images/`
into `kulta-kelloporssi/` there to update it.)
