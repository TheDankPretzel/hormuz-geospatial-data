# Hormuz Geospatial Data

Research and data preparation for key locations in the Persian Gulf / Strait of Hormuz region.

## Locations Included

- **Bandar Abbas** (27.1832°N, 56.2668°E)
  - Major commercial port + naval base
  - Infrastructure noted: Shahid Rajaee Port, Naval Base (Southern Fleet HQ), 9th Tactical Air Base elements

- **Bushehr** (28.9689°N, 50.8365°E)
  - Port city with air base
  - Infrastructure: Bushehr Port, Bushehr Air Base, adjacent Nuclear Power Plant

- **Bandar Kangan** (27.8370°N, 52.0640°E)
  - Industrial port
  - Infrastructure: Kangan Port, petrochemical/gas field facilities

- **Strait of Hormuz Chokepoint** (26.5667°N, 56.2500°E)
  - Approximate center of narrowest passage (~21 nm wide)
  - Key shipping lanes; nearby islands with reported military activity

## Data Format
- `locations.json`: Structured data with coordinates (WGS84), types, infrastructure lists, and notes suitable for plotting on OSM basemaps via contextily.

## Usage Notes
Prepared for use with Python libraries such as `contextily` + `geopandas`/`matplotlib` for basemap generation. All coordinates are approximate but sufficient for regional mapping.

**Last updated**: 2026-05-28

No direct reports or raw data files were located via GitHub searches; data compiled from standard open geographic references and common strategic infrastructure mentions in public analyses.