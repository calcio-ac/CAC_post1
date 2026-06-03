# CAC_post1 — Travel Fatigue vs. World Cup Performance

Interactive companion to Calcio AC post #01.

**Question:** Does the team that flies more lose more?
**Data:** Group-stage travel distances for every team at the 2014, 2018, 2022 World Cups, plus a 2026 preview.

## Live site
Once GitHub Pages is enabled for this repo (Settings → Pages → branch `main`, root `/`), the site is live at:

`https://calcio-ac.github.io/CAC_post1/`

## Structure
```
CAC_post1/
├── data/        # source xlsx + generated data.json
├── images/      # Insta / LinkedIn images
├── web/         # the interactive site (index.html, vanilla JS + Plotly)
└── index.html   # redirect to /web/
```

## Headline stats (2014–2022 combined)
- Teams above **3.5%** of total group-stage travel → **65% crashed out in the group stage**
- Group-stage exits avg travel: **3.33%** · Semi-finalists avg: **2.84%**
- 2026 most-fatigued team: **Bosnia & Herzegovina (5.08%)**

## Stack
Static HTML + Plotly.js (CDN). No build step. Deploys free on GitHub Pages.

## Palette
`#0277B6` Team A · `#D90429` Team B · `#09D69F` Box · `#FFD166` BG · `#FFFFFF` / `#000000`
Font: Courier New (monospace).
