# Islands of the Salish Sea

A vintage-inspired cartographic study of Washington's Salish Sea islands, created by **Brittne Valdivia** for **30 Day Map Challenge 2026 — Day 3: Polygons**.

![Islands of the Salish Sea: colored island polygons with shaded terrain, a map key, and a north arrow](images/salish-sea-map.png)

## About the map

This project brings GIS processing and visual design together to explore the island landscapes of the Pacific Northwest. A muted coastal palette, shaded relief, and atlas-inspired typography emphasize island shapes and terrain.

## Tools and process

- **QGIS** provided the environment for spatial processing, styling, and the final print layout.
- **QuickOSM** brought in **OpenStreetMap island polygons** to define the island outlines.
- **USGS 3D Elevation Program (3DEP) digital elevation models** supplied terrain information for hillshade generation.
- **Hillshade** adds depth and makes the islands' topography visible beneath their colors.
- **Rule-based symbology** assigns individual island colors and supports the map key.
- The finished composition was exported as a PNG for sharing.

## Data credits and attribution

Island polygons: **© OpenStreetMap contributors**. OpenStreetMap data is available under the [Open Database License (ODbL)](https://www.openstreetmap.org/copyright).

Elevation data: **U.S. Geological Survey (USGS), 3D Elevation Program (3DEP)**. Learn more at the [USGS 3DEP program](https://www.usgs.gov/3d-elevation-program).

Cartography and layout: **Brittne Valdivia, 2026**. Data-source credits do not imply endorsement by the source organizations.

## Repository contents

This repository shares the finished map image and documentation. The editable QGIS project and source GIS datasets remain private. QGIS projects, GeoPackages, elevation rasters, VRTs, and other source datasets are excluded through protective ignore rules.

The map is a cartographic study intended for portfolio viewing, not navigation. No additional reuse license is granted for the original cartographic design; underlying data retains its own licensing terms.
