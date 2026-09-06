# Everything Must Go Sale

A one-page sale listing for household and coffee gear in the DC area.
Served by GitHub Pages from the root of this repo.

- `index.html` — the whole site: markup, styles and listing data in one file.
  Prices and item copy live in the `ITEMS` array near the bottom.
- `img/` — one photo per listing. Filenames are referenced by `photo:` in `ITEMS`.

To change a price, edit that item's `price` (0 renders as "Free") and its
`note` qualifier. No build step; commit and Pages redeploys.
