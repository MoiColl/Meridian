# Meridian — Countries · Capitals · Flags

A single self-contained HTML geography trainer: flashcards, a zoomable clickable
world map, a sortable country/capital list, and six quiz modes covering flags,
capitals, and country locations. Available in English and Spanish.

**[Play it live](#)** — *(replace this with your GitHub Pages URL once deployed
— see below)*

## Features

- **Learn**
  - Flashcards (country ⇄ capital ⇄ flag), with a "known" pile you can set
    aside and bring back later
  - Map Explorer — pan, zoom, and click any country for its flag/capital/region
  - Weak Spots — a heat-mapped view of the countries you miss most, ranked and
    clickable
  - List View — every country, capital, and flag in one sortable table
- **Quiz** — Flag → Country, Country → Flag, Capital → Country, Country →
  Capital, Locate on Map, and a Mixed Sprint, each with optional Timed,
  Survival, and typed-answer modes
- Adaptive sampling: every country is cycled through before any repeats, and
  countries you get right drop out of rotation for the rest of the run
- 198 countries, real flags, and 50m-resolution map borders — all bundled
  offline, no network requests after the page loads
- English / Spanish toggle, including translated country and capital names

## Running it

It's one HTML file with everything embedded (data, flags, map geometry). Just
open `index.html` in a browser — locally, from a USB stick, wherever. No build
step, no server, no dependencies.

## Deploying to GitHub Pages

If you're reading this because you just cloned/downloaded this repo and want
your own copy live:

```bash
# from inside the project folder
git init
git add index.html README.md LICENSE
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Source → Deploy from a branch → `main` /
`(root)` → Save**. It'll be live at
`https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Credits

Built with [Claude](https://claude.ai).

Data and assets are bundled from the following sources, each under its own
license:

- **Map borders**: [Natural Earth](https://www.naturalearthdata.com/) (public
  domain, 1:50m Cultural Vectors — Admin 0 Countries)
- **Country/capital/region data**:
  [mledoze/countries](https://github.com/mledoze/countries)
  ([ODbL](https://github.com/mledoze/countries/blob/master/LICENSE))
- **Flags**: [flag-icons](https://github.com/lipis/flag-icons) by Panayiotis
  Lipiridis (MIT)
- **Spanish country names**:
  [i18n-iso-countries](https://github.com/michaelwittig/node-i18n-iso-countries)
  (MIT)
- **Fonts**: Space Grotesk, IBM Plex Sans, IBM Plex Mono via Google Fonts (SIL
  Open Font License)

## License

The code in this repository (`index.html`) is released under the MIT License
— see [LICENSE](LICENSE). The embedded third-party data and assets above
remain under their own respective licenses.
