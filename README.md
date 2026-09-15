# RIFT Innovation Lab — Website

Static marketing site for **RIFT Innovation Lab** — an engineering & venture studio
turning concepts into market-ready ventures across East Africa.

## Pages
- `index.html` — homepage (hero, Why Kenya, approach, ecosystem, model, portfolio,
  value, expertise, selected work, **impact**, team, contact)
- `imv-origin.html` — case study: IMV Origin × Toyota
- `smart-cold.html` — case study: SMART-COLD

Each page is fully self-contained (CSS, JS and images are inlined), so there is no
build step and no external asset folder.

## Run locally
Just open `index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy
Static hosting — point the publish directory at the repository root.
- **Netlify:** connect this repo (publish directory `.`, no build command) for
  continuous deploys on every push, or drag the folder onto the Deploys tab.

## Tech
Hand-written HTML/CSS/vanilla JS. Fonts: Inter + JetBrains Mono (Google Fonts).
Brand palette: navy `#222b3e`, teal `#2f8f86`, sage `#cddfda`, sand `#e7dfd4`, cream `#f8f6f3`.
