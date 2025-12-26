# IST-QuakeRisk

**IST-QuakeRisk** is a GIS-based seismic risk assessment platform designed to
evaluate location-based earthquake risk in Istanbul by integrating raster
earthquake hazard data with vector-based geological and urban datasets.

## Objectives
- Integrate raster earthquake hazard maps with vector geospatial layers
- Perform location-based seismic risk assessment
- Provide an accessible Web GIS interface for public awareness and decision support
- Establish a scientifically explainable risk scoring methodology

## Data Sources
- AFAD Turkey Earthquake Hazard Map (Raster)
- MTA Geological / Soil Classification Data
- Istanbul Metropolitan Municipality Open Data Portal
- OpenStreetMap

## Methodology Overview
1. Raster-based seismic hazard extraction (PGA / spectral acceleration)
2. Vector-based soil classification analysis
3. Point-in-polygon and raster sampling techniques
4. Weighted seismic risk scoring
5. Web-based visualization using interactive maps

## Technology Stack
**Backend**
- Python
- FastAPI
- GeoPandas
- Rasterio
- PostGIS

**Frontend**
- React
- Mapbox GL JS

## Disclaimer
This platform is a decision-support and public awareness tool.
It does not replace official engineering assessments.
