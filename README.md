# Mapping the 2025, Eaton and Palisades Fire Effects (EDS 220, Homework 4 and Section 8)

## About

This repository contains materials for final project, of the course EDS 220 - Working with Environmental Datasets. The material is used to conduct an analysis of the effect of the Eaton and Palisades fires in California (January 2025), using false-color imagery to visualize the fire scars and identify communities disproportionately affected. 

## File Structure

```
.
├── data
│   ├── Eaton_Perimeter_20250121
│   ├── landsat8-2025-02-23-palisades-eaton.nc
│   └── Palisades_Perimeter_20250121
├── fire-scars-map.ipynb
├── hwk4-task2-false-color-MIURA.html
├── README.md
└── social-dimensions-fire.ipynb
```

## Data

- Environmental Justice Index: Access from the Centers for Disease Control and Prevention and Agency for Toxic Substances Disease Registry's Geospatial, Research, Analysis, and Services program. The datafroma contains EJI data for the state of California.
    - Date Accessed: November 21, 2025

- Eaton Fire Perimeter: Accessed from the County of Los Angeles Geohub. The dataframe contains geometries of the perimeter of the Eaton fire.
    - Date Accessed: November 19, 2025

- Palisade Fire Perimeter: Accessed from the County of Los Angeles Geohub. The dataframe contains geometries of the perimeter of the Palisade fire.
    - Date Accessed: November 19, 2025

- Landsat: Accessed from the Microsof Planetary Computer data catalogue and sourced from the Landsat Collection 2 Level-2 Science Products, specifically the atmospherically corrected surface reflectance image data. 
    - Date Accessed: November 19, 2025

## References:

Centers for Disease Control and Prevention and Agency for Toxic Substances Disease Registry. [Year] Environmental Justice Index. Accessed [2025-11-21]. [https://atsdr.cdc.gov/place-health/php/eji/eji-data-download.html](https://atsdr.cdc.gov/place-health/php/eji/eji-data-download.html)

Earth Resources Observation and Science (EROS) Center. (2020). Landsat 8-9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2 [dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6.

County of Los Angeles, Geohub. (2025). Palisades and Eaton Dissolved Fire Perimeters (2025) [dataset]. County of Los Angeles. https://geohub.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about
