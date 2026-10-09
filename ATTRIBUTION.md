# Attribution

| Data | Source | Licence |
|---|---|---|
| Airports, runways, frequencies, navaids | [OurAirports](https://ourairports.com) | Public domain |
| ILS (US): localizer, glide slope, DME, markers | FAA National Airspace System Resources (NASR), cycle in `manifest.json` | US government work, public domain |
| Runway ends, displaced thresholds, marking class, approach lights, PAPI / VASI, REIL, centre line and touchdown zone lights, edge light intensity (US): `E` records | FAA National Airspace System Resources (NASR) APT data, cycle in `manifest.json` | US government work, public domain |
| Magnetic declination of every airport (`A` records: epoch 2026.0 and yearly change) | World Magnetic Model 2025 (NOAA NCEI / British Geological Survey), computed with the `pygeomag` package | Public domain (US government work) |
| Elevation atlases `dem/` (zoom 0 .. 14: whole earth at zoom 0 .. 5, around the plan airports and the LIME - EPLL corridor in more detail; 4 x 4 Mapterhorn tiles per PNG, heights rounded to 1 m, 0.25 m at zoom 12 and above) | [Mapterhorn](https://mapterhorn.com) terrain tiles, built from Copernicus GLO-30 and national open elevation models; the full list of sources, producers and licences is [mapterhorn.com/attribution](https://mapterhorn.com/attribution) (machine readable: [attribution.json](https://download.mapterhorn.com/attribution.json)) | Open licences of each source (CC BY 4.0, Open Government Licences, Copernicus), attribution required: see their list |
| Airport ground graphs `gnd/`: taxiways, taxilanes, runway lines, stands, gates, holding positions, aprons, terminals, hangars of 9 airports (M4-T13) | [OpenStreetMap](https://www.openstreetmap.org) contributors, `aeroway=*` read through the Overpass API; the files are a derived database, see `gnd/LICENSE.md` | ODbL 1.0, (c) OpenStreetMap contributors, [openstreetmap.org/copyright](https://www.openstreetmap.org/copyright) |
| Lake / glacier / urban raster (inside the world, not hosted here) | [Natural Earth](https://www.naturalearthdata.com) 1:10m lakes, glaciated areas, urban areas | Public domain |

The data is converted to a compact text format. Check the original sources for anything safety related; this is for a game.
