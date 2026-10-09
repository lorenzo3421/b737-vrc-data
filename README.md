# b737-vrc-data

Static data for a personal VRChat flight simulator project, served through GitHub Pages.

- `apt/` airports, runways, runway end details (US), ILS and frequencies in 5 degree cells, plus `apt/index.txt` (format version 2)
- `nav/` VOR, DME, NDB and TACAN in 5 degree cells
- `dem/` elevation atlases (2048 px PNG, 4 x 4 terrain tiles each, Terrarium encoding) and `dem/index.txt` (M4-T16)
- `gnd/` airport ground graphs (taxiways, stands, holding positions, aprons) of 8 airports from OpenStreetMap, ODbL (M4-T13)
- `manifest.json` sources, counts and file hashes

Sources and licences: [ATTRIBUTION.md](ATTRIBUTION.md). Non-commercial use.
