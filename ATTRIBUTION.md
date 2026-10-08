# Attribution

| Data | Source | Licence |
|---|---|---|
| Airports, runways, frequencies, navaids | [OurAirports](https://ourairports.com) | Public domain |
| ILS (US): localizer, glide slope, DME, markers | FAA National Airspace System Resources (NASR), cycle in `manifest.json` | US government work, public domain |
| Runway ends, displaced thresholds, marking class, approach lights, PAPI / VASI, REIL, centre line and touchdown zone lights, edge light intensity (US): `E` records | FAA National Airspace System Resources (NASR) APT data, cycle in `manifest.json` | US government work, public domain |
| Magnetic declination of every airport (`A` records: epoch 2026.0 and yearly change) | World Magnetic Model 2025 (NOAA NCEI / British Geological Survey), computed with the `pygeomag` package | Public domain (US government work) |
| Elevation (planned) | [Mapterhorn](https://mapterhorn.com) | Open licences, see their attribution list |

The data is converted to a compact text format. Check the original sources for anything safety related; this is for a game.
