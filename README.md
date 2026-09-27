# Project Lattice map packages

Public, versioned offline map packages for Project Lattice. The Android source
repository remains private; this repository contains only the small verified
catalog, attribution/provenance documentation and GitHub Release assets.

Release `v1.0.0` contains:

- Germany Base (`BASE_ORIENTATION`, PMTiles v3, Shortbread 1.0, zoom 0–10)
- Berlin Detail (`DETAIL_SHORTBREAD`, PMTiles v3, Shortbread 1.0, zoom 0–14)
- the immutable version-1 JSON catalog and SHA-256 list

The maps derive from OpenStreetMap data through the VersaTiles snapshot dated
2026-06-08. © OpenStreetMap contributors. Data is available under the Open
Database License (ODbL): <https://opendatacommons.org/licenses/odbl/1-0/>.
The generated map packages must retain this attribution.

The Project Lattice app selects packages locally. Catalog and asset requests do
not contain a GPS position, H3 index, route, account identity or gameplay data.
