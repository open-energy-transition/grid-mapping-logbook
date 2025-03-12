# Grid Mapping Logbook
This repository documents OET's mapping process of electricity infrastructure using OpenStreetMap (OSM).

## Overview
This repository documents the process of mapping electricity infraestructure such as transmission towers/lines/poles above 90 kV, generators, substations and transformers using OpenStreetMap (OSM). It includes guidance on data sources, mapping tools, challenges encountered, and insights about different countries' mapping feasibility. Additionally, it focuses on continuously updating and expanding mapping efforts within specific countries or regions.

## Repository Structure
```
📂 power-mapping-osm
│── Nigeria
   │── 📄 Nigeria_v0.md
   │── 📂 images/ (Screenshots and visual guides)
```

## Mapping Process
1. **Identify Data Sources**
   - OSM data via Overpass API [OET overpass turbo initial query](https://github.com/open-energy-transition/grid-mapping-starter-kit/blob/main/josm-config/transmission-grid.overpassql)
   - Satellite imagery (e.g., Bing, Mapbox, Esri, Sentinel-2)
   - Official grid infrastructure government reports or open datasets [Please check our list of resources](https://github.com/open-energy-transition/Awesome-Electric-Grid-Mapping)
   - Utility company reports (if available)

2. **Assess Country-Specific Feasibility**
   - **Ease of Mapping**: Presence of existing grid data in OSM.
   - **Satellite Image Quality**: Clarity of power lines, towers, and substations.
   - **Street View Availability**: Google Street View or Mapillary coverage.
   - **Metadata Gaps**: Missing tags or incomplete infrastructure data.
   - **OSM Coverage**: Density and accuracy of mapped infrastructure.

3. **Mapping Guidelines**
   - Use JOSM or iD editor for adding power infrastructure.
   - Tagging conventions following [OSM Power Guidelines](https://wiki.openstreetmap.org/wiki/Power).
   - Verifying data accuracy using multiple sources.

## Updates by Country or Region
- This repository maintains a dedicated `updates/` folder where the latest mapping efforts, findings, and corrections for specific countries or regions are documented.
- Each update should include details on:
  - Newly mapped transmission lines or substations.
  - Any challenges faced while mapping.
  - Data quality improvements and missing metadata.
  - New tools or methodologies tested.

## Contributions
- Submit issues or feature requests.
- Open pull requests with mapping improvements, Overpass Turbo query limitations, and edge cases found.
- Share country-specific updates to help improve the overall quality of transmission grid mapping.
- Follow best practices outlined in the repository.
- [Visualize your contributions heatmap](https://yosmhm.neis-one.org/#)
