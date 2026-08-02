# NeoFeoda map data

Static map payload for [NeoFeoda](https://t.me/neofeodabot) — a world of real
districts. Served via CDN (jsDelivr / raw.githubusercontent) as a mirror tier.

- `data/tiles/districts.NNN.part` — one PMTiles archive split into ≤19 MiB
  byte chunks (`manifest.json` describes sizes; concatenation restores the archive)
- `data/wd-index.json` — search index (districts + provinces)
- `data/state.json` — world state snapshot
- `data/moscow.geojson`, `data/boundary.json` — Moscow districts

## Data sources & licenses

- © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors (ODbL) — district boundaries
- © [geoBoundaries](https://www.geoboundaries.org) CGAZ (CC-BY 4.0)
- [Natural Earth](https://www.naturalearthdata.com) (public domain) — provinces
- City population data: [GeoNames](https://www.geonames.org) (CC-BY 4.0)

Derived database released under ODbL terms.
