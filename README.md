# Guernsey land use

A weekly series of maps from The Quarry tracing how Guernsey's land has changed since 2015, built from the States of Guernsey planning register and Digimap.

Live at https://landuse.thequarry.media

| Path | Map |
|---|---|
| `/` | Series index |
| `/fields/` | Fields into gardens: 830 applications to turn fields or farmland into garden |
| `/access/` | Hedges, banks and driveways: 2,132 applications for vehicle accesses and hedge or earth bank removal |
| `/oldbuildings/` | New homes from old buildings: 223 applications to turn packing sheds, barns and outbuildings into homes |

Each map is one `index.html` (Leaflet, CARTO tiles) reading `data/*.json` beside it, with a CSV of the same data for download. Add `?embed=1` for a map-only version to iframe in Ghost; inside an iframe that happens automatically.

Data collected from the planning register on 3 November 2026. Each page explains how applications were selected and located.
