# moonbeamechoes.com

Landing page for **Moonbeam Echoes**, a game by Human Signal Games. Hosted on
GitHub Pages at [moonbeamechoes.com](https://moonbeamechoes.com) and links to the
[itch.io page](https://humansignalgames.itch.io/moonbeam-echoes).

## Structure

- `index.html` — single-page site (all CSS inline, no build step)
- `favicon.svg` — moon + ROYGBIV prism icon
- `CNAME` — custom domain for GitHub Pages (`moonbeamechoes.com`)
- `.nojekyll` — disables Jekyll processing

## Local preview

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

Pushes to `main` publish automatically once GitHub Pages is enabled
(Settings → Pages → Deploy from branch → `main` / root). See the DNS and Pages
setup notes in the project instructions.
