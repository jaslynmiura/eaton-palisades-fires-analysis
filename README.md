# Visualizing Fire Scars Through False Color (EDS 220, Homework 4)

## About

This repository contains materials for Homework 4 of the course EDS 220 - Working with Environmental Datasets. The material is used to conduct an analysis of the effect of the Eaton and Palisades fires in California (January 2025), using false-color imagery to visualize the fire scars. 

## File Structure

```
.
├── data
│   ├── Eaton_Perimeter_20250121
│   ├── landsat8-2025-02-23-palisades-eaton.nc
│   └── Palisades_Perimeter_20250121
├── hwk4-task2-false-color-MIURA.ipynb
└── README.md
```

## Data

- Eaton Fire Perimeter: Accessed from the County of Los Angeles Geohub. The dataframe contains geometries of the perimeter of the Eaton fire.
    - Date Accessed: November 19, 2025

- Palisade Fire Perimeter: Accessed from the County of Los Angeles Geohub. The dataframe contains geometries of the perimeter of the Palisade fire.
    - Date Accessed: November 19, 2025

- Landsat: Accessed from the Microsof Planetary Computer data catalogue and sourced from the Landsat Collection 2 Level-2 Science Products, specifically the atmospherically corrected surface reflectance image data. 
    - Date Accessed: November 19, 2025

## References:

Earth Resources Observation and Science (EROS) Center. (2020). Landsat 8-9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2 [dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6.

County of Los Angeles, Geohub. (2025). Palisades and Eaton Dissolved Fire Perimeters (2025) [dataset]. County of Los Angeles. https://geohub.lacity.org/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about
