# Geospatial Technology Radar

An interactive Geospatial Technology Radar built with D3.js.

The radar visualizes geospatial technologies across four lifecycle stages and four domains. Technologies are placed within a quadrant and ring, then distributed using a force simulation to avoid overlaps while remaining constrained to their designated segment.

## Rings

The radar uses four rings to represent technology maturity:

* **Adopt** — Recommended for broad use.
* **Trial** — Suitable for experimentation and limited adoption.
* **Assess** — Worth evaluating for future use.
* **Hold** — Not recommended for new initiatives.

## Quadrants

Technologies are grouped into four domains:

* Applications
* Platforms & Services
* Components & Toolkits
* Data & Standards

## Data

Technologies are loaded from `technologies.json`.

Example:

```json
[
  {
    "name": "PostGIS",
    "quadrant_enterprise": "Data & Standards",
    "ring": "Adopt"
  },
  {
    "name": "QGIS",
    "quadrant_enterprise": "Applications",
    "ring": "Trial"
  }
]
```
