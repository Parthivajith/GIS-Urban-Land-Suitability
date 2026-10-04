# GIS-Based Land Suitability Analysis for Urban Development Using LULC

## Project Overview

Urbanization increases the demand for land for residential, commercial, and infrastructure development. However, different areas have different physical, environmental, and accessibility characteristics.

This project aims to identify areas that are potentially suitable for future urban development using Geographic Information System (GIS) techniques and Land Use/Land Cover (LULC) data.

The study will integrate multiple spatial factors, including LULC, slope, road accessibility, distance from water bodies, and proximity to existing built-up areas, to generate an urban land suitability map.

## Objectives

- Analyze the existing Land Use/Land Cover (LULC) of the study area.
- Identify spatial factors that influence urban development suitability.
- Preprocess and normalize the selected spatial datasets.
- Assign suitability scores and weights to the different factors.
- Apply a weighted overlay approach to generate a suitability index.
- Classify the study area into different levels of suitability.
- Generate a final GIS-based land suitability map.

## Study Area

The proposed study area is **Kharagpur, West Bengal, India**, and its surrounding region.

The study area will be finalized based on the availability and spatial resolution of the required datasets.

## Data Sources

The project will use publicly available spatial datasets.

| Dataset | Proposed Source | Purpose |
|---|---|---|
| Land Use/Land Cover | ESA WorldCover | Identify existing land-use classes |
| Road Network | OpenStreetMap | Analyze accessibility |
| Digital Elevation Model | SRTM / public DEM | Derive elevation and slope |
| Water Bodies | OpenStreetMap / satellite data | Identify environmental constraints |
| Built-up Areas | LULC / satellite data | Analyze existing urban extent |

## Proposed Methodology

The project will follow a GIS-based multi-criteria decision analysis approach.

```text
Data Collection
       ↓
Data Preprocessing
       ↓
LULC Analysis
       ↓
Generation of Suitability Factors
       ↓
Normalization of Factors
       ↓
Weight Assignment
       ↓
Weighted Overlay Analysis
       ↓
Suitability Index
       ↓
Suitability Classification
       ↓
Final Land Suitability Map
```

### Main Suitability Factors

The initial analysis will consider:

1. **Land Use/Land Cover**
2. **Slope**
3. **Distance from Roads**
4. **Distance from Water Bodies**
5. **Proximity to Existing Built-up Areas**

The suitability criteria and weights will be refined based on literature, spatial characteristics, and data availability.

## Expected Output

The project is expected to produce:

- LULC map of the study area.
- Individual spatial suitability-factor maps.
- Normalized suitability layers.
- Weighted suitability index.
- Final urban land suitability map.
- Classification of areas into different suitability levels.

## Technologies

The project will use:

- Python
- GeoPandas
- Rasterio
- NumPy
- Matplotlib
- QGIS
- OpenStreetMap data
- Public satellite/geospatial datasets

## Repository Structure

```text
GIS-Urban-Land-Suitability/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── README.md
│
├── src/
│   └── README.md
│
├── outputs/
│   └── README.md
│
└── README.md
```

## Current Project Status

### Completed

- [x] Problem definition
- [x] Study area identified
- [x] Initial spatial factors identified
- [x] Initial data sources identified
- [x] GitHub repository created
- [x] Project repository structure created
- [x] Initial methodology designed

### In Progress

- [ ] Dataset acquisition
- [ ] Spatial data preprocessing
- [ ] LULC analysis
- [ ] Suitability factor generation
- [ ] Weight assignment
- [ ] Weighted overlay analysis
- [ ] Final suitability map
- [ ] Validation

## Team Contributions

Team member responsibilities will be finalized during the project and documented here.

| Member | Planned Contribution |
|---|---|
| Member 1 | Data Collection & Preprocessing — Collect the LULC, road, water-body and elevation data and prepare them for analysis. |
| Member 2 | 

GIS Suitability Analysis — Use the prepared data to create suitability layers and combine them to identify suitable areas.s |
| Member 3 | Maps, Results & Documentation — Create the final maps, analyze the results, prepare visualizations and maintain the GitHub documentation. |


## Project Status

**Current stage:** Initial implementation and methodology development.

The repository will be updated throughout the project with preprocessing code, analysis notebooks, spatial outputs, and documentation.
