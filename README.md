# Quincy Property Watch

Live dashboard: **https://6agentkk9.github.io/quincy-property-watch/**

Tracks 6,000–10,000 SF industrial / warehouse buildings **for sale** near Quincy, MA (Braintree, Weymouth, Milton, Randolph, Holbrook, Avon, Canton, Dorchester) with **60+ parking** and **>10 ft** clear height.

## How it stays current

- A Grok automation (`Quincy Property Watch – Daily Check`) runs at **1:00 AM ET**.
- It re-searches LoopNet, Crexi, Cityfeet, Showcase, Jack Conway / MLS, and broker sites.
- It rewrites project files, then **pushes this repo’s `index.html`** so GitHub Pages updates.
- There is no separate JSON to load on the public site — data is embedded in `index.html`.

## Last published snapshot

- Check date: **Tue Sep 15, 2026 1:20am ET**
- Strict matches: **0**
- Tracked listings: **14**
- Best size + ceiling + sale near-misses: **13 Robbie Rd, Avon** and **8 Carver Cir, Canton**
- Special watches: **27 Glendale Rd** (lodge / meeting hall, sale language but no price) and **100 Quarry Hills Dr** (city-leased Granite Links campus; draft lease prohibits warehousing)

Always verify any listing with the broker before acting.
