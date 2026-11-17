# GPS Tracker map packages

Offline regional map packages for the GPS Tracker walking app. Each package is a single vector
MBTiles file that the app downloads (or imports) and shows without a network connection.

The packages and a `catalogue.json` describing them are attached to this repository's
[Releases](https://github.com/bazza801/gps-tracker-maps/releases); nothing large is committed here.

## Regions

| Region | Area |
|---|---|
| Glen Coe & Ben Nevis | Glen Coe, the Aonach Eagach, Ben Nevis, the Mamores and Fort William |
| Cairngorms | Cairngorms National Park, from Aviemore to Braemar and Glen Shee |

Packages are rebuilt roughly twice a year, or when Ordnance Survey publishes new data.

## What's in a package

- **OS Open Zoomstack**: sea, lochs, rivers and streams, woodland, green spaces, towns, buildings, roads, railways and place names.
- **OS Terrain 50**: 10 m contours and spot heights.
- **OpenStreetMap**: walking paths, tracks, bridleways and steps.

Zoom levels 9 to 14. Using a package outside the app: it's a standard MBTiles file with
Mapbox Vector Tile (PBF) tiles, readable by MapLibre and other vector tile tools.

## Licences and attribution

The packages combine data under two licences. Anyone using them must keep both attributions.

- **Ordnance Survey OS Open Zoomstack and OS Terrain 50**, under the
  [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).
  Attribution: *Contains OS data © Crown copyright and database rights [year]* (the year is
  recorded in each package's metadata).
- **OpenStreetMap data**, under the [Open Database Licence (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
  Attribution: *© OpenStreetMap contributors*.

The map packages, as databases containing OpenStreetMap data, are made available under the
**Open Database Licence (ODbL) 1.0**. The OS data within them remains under the Open Government
Licence.

This repository is not affiliated with or endorsed by Ordnance Survey or the OpenStreetMap Foundation.
