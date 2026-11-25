# AgriLand Assam

Interface prototype of a decision-support system for finding and ranking vacant, cultivable and fertile land in Assam.

Built for NESFIC 2026, problem statement D-13: Geospatial Identification of Cultivable & Fertile Agricultural Potential Lands (Department of Science & Technology, Government of Assam – ASSAC).

## Live demo

Open `index.html` in any browser, or visit the GitHub Pages link for this repository.

## Screens

- **Map**
  - Land Check: select a plot or draw an area and see suitability, best crops, soil NPK and reasons
  - Crop Finder: pick a crop to see where it grows now, where it is suitable and new land for it
  - My Map: set factor weights with sliders and save presets
  - Assam modes: Winter rice-fallow, Char lands, Flood-safe only
  - Layers: boundaries, land use, terrain, soil, water, hazards, satellite, access, results
  - Satellite date picker with cloud cover
- **Data Library**: auto-fetched, uploaded and linked datasets, data cards, versions, upload checks
- **Priority List**: ranked plots with exports (GeoPackage, Shapefile, GeoJSON, GeoTIFF, CSV, PDF)
- **Field Check**: mobile form for field verification with GPS, photos, soil sample and sensor reading
- **Accuracy**: field results and soil prediction vs lab tests
- **Admin**: users, roles and activity log

## Notes

- This is an interface prototype. Buttons show what each feature does but are not connected to live services yet.
- Suitability values on the map and in tables are sample data for illustration.
- Base map: district boundaries (Census 2011) and rivers (Natural Earth), simplified.
- Planned data sources: Copernicus Sentinel-1/2, Bhuvan, NESDR, ASDMA, Soil Health Card, SRTM/Cartosat, IMD.

## Tech

Single HTML file with Leaflet 1.9.4 (loaded from cdnjs). No build step.
