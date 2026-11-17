# GPS Tracker map packages

Offline regional map packages for the GPS Tracker walking app. Each package is a single vector
MBTiles file that the app downloads (or imports) and shows without a network connection.

The packages and a `catalogue.json` describing them are attached to this repository's
[Releases](https://github.com/bazza801/gps-tracker-maps/releases); nothing large is committed here.

## Regions

Scotland is covered by 25 overlapping regions (neighbours overlap by a few kilometres, so a walk near an
edge is on one map). Download only the ones you need.

| Region | Size | Area |
|---|---|---|
| Glen Coe & Ben Nevis | 31 MB | Glen Coe, the Aonach Eagach, Ben Nevis, the Mamores and Fort William. |
| Cairngorms | 83 MB | Cairngorms National Park, from Aviemore to Braemar and Glen Shee. |
| Galloway & Dumfries | 86 MB | The Galloway Hills, the Merrick, the Solway coast and Dumfries. |
| Southern Uplands & Borders | 126 MB | The Moffat and Tweedsmuir hills, the Ettrick Forest, the Borders, the Berwickshire coast and the northern Cheviots. |
| Ayrshire & Arran | 121 MB | Arran's Goatfell ridges, Bute, the Ayrshire coast and hills. |
| Glasgow, Edinburgh & the Pentlands | 177 MB | The Campsie Fells, the Pentland Hills, Glasgow, Edinburgh and East Lothian. |
| Loch Lomond & the Trossachs | 99 MB | Ben Lomond, the Arrochar Alps, the Trossachs and the Crianlarich hills. |
| Cowal & Kintyre | 68 MB | The Cowal hills, Loch Fyne, Knapdale and the Kintyre peninsula. |
| Islay & Jura | 17 MB | The Paps of Jura, Islay and Colonsay. |
| Mull, Oban & Lorn | 70 MB | Ben More on Mull, Iona, Coll, Tiree, Oban, Ben Cruachan and Glen Etive's southern hills. |
| Highland Perthshire | 119 MB | Ben Lawers, Schiehallion, Ben Alder, Rannoch, Glen Lyon and the Ochils. |
| Fife & Dundee | 71 MB | The Lomond Hills, the Fife coast and Dundee. |
| Angus Glens & Aberdeenshire | 114 MB | The Angus glens, Mount Keen, Bennachie, Royal Deeside's east end and Aberdeen. |
| Moray & Speyside | 37 MB | The Moray coast, Speyside and the Ladder Hills. |
| Ardnamurchan, Moidart & Knoydart | 73 MB | Ardgour, Morvern, Ardnamurchan, Moidart, Morar and Knoydart. |
| Kintail, Glen Affric & the Great Glen | 85 MB | The Five Sisters, Glen Shiel, Glen Affric, Loch Ness and the Great Glen. |
| Creag Meagaidh, Monadhliath & Inverness | 74 MB | Creag Meagaidh, Laggan, the Monadhliath hills and Inverness. |
| Skye & the Small Isles | 56 MB | The Cuillin, Trotternish, Raasay, Rum, Eigg and Canna. |
| Torridon & Wester Ross | 67 MB | Torridon, Applecross, the Fisherfield Forest, An Teallach and Ullapool. |
| Easter Ross & the Black Isle | 68 MB | Strathconon, Ben Wyvis, the Black Isle and the Dornoch Firth. |
| Assynt & Sutherland | 70 MB | Suilven, Coigach, Assynt, Ben Hope, Ben Loyal and Cape Wrath. |
| Caithness & East Sutherland | 25 MB | Morven, the Flow Country, the Caithness coast and John o' Groats. |
| Outer Hebrides | 82 MB | Lewis, Harris, the Uists, Benbecula and Barra. |
| Orkney | 15 MB | Mainland Orkney, Hoy and the northern and southern isles. |
| Shetland | 27 MB | Mainland Shetland, Unst, Yell and Fair Isle. |

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
