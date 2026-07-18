# moonbeamechoes.com

Landing page for **Moonbeam Echoes**, a game by Human Signal Games. Hosted on
GitHub Pages at [moonbeamechoes.com](https://moonbeamechoes.com) and links to the
[itch.io page](https://humansignalgames.itch.io/moonbeam-echoes).

## Structure

Only the `docs/` folder is published to the website. Everything else in this
repo (including this README) stays private to the repo and is **not** served.

- `docs/index.html` — single-page site (all CSS inline, no build step)
- `docs/favicon.svg` — moon + ROYGBIV prism icon
- `docs/CNAME` — custom domain for GitHub Pages (`moonbeamechoes.com`)
- `docs/.nojekyll` — disables Jekyll processing
- everything at the repo root — internal files, not published

## Local preview

Serve the `docs/` folder:

```bash
cd docs && python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

Pushes to `main` publish automatically once GitHub Pages is enabled
(Settings → Pages → Deploy from branch → `main` / `docs`). See the DNS and Pages
setup notes in the project instructions.
