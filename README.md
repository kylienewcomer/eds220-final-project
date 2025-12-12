# Identifying changes in the Biodiversity Intactness Index (BII) in Phoenix, AZ

This repository hosts the materials by Kylie Newcomer completed for the EDS 220 - *Working with Environmental Data* final project.

## Background
Phoenix, AZ is a rapidly growing city. As a consequence for the increase in urban area, the natural areas and green space decreae. As a result, the biodiversity would also decrease. This project analyzes and calculates the change in BII from 2017 to 2020

## Repository Structure
```
├── .gitignore
│   └── data
│       └── tl_2024_04_cousub
│           ├── tl_2024_04_cousub.cpg
│           ├── tl_2024_04_cousub.dbf
│           ├── tl_2024_04_cousub.prj
│           ├── tl_2024_04_cousub.shp
│           ├── tl_2024_04_cousub.shp.ea.iso.xml
│           ├── tl_2024_04_cousub.shp.iso.xml
│           └── tl_2024_04_cousub.shx
├── phoenix_biodiversity.ipynb
└── README.md
```

## Data
**Biodiversity Intactness Index (BII)** data was accessed as a SpatioTemporal Asset Catalog (STAC), through the Microsoft Planetary Computer STAC API. Data can be accessed by importing the `Client` from `pystac_client` and `planetary_computer` packages. More information on NetCDF can be found [here](https://docs.unidata.ucar.edu/netcdf-c/current/index.html)

**Phoenix subdivision border** is a shapefile of the Arizona County subdivision from the [U.S Census Bureau](https://catalog.data.gov/dataset/tiger-line-shapefile-current-state-arizona-county-subdivision)

## References
Microsoft Open Source, Matt McFarland, Rob Emanuele, Dan Morris, Tom Augspurger, microsoft/PlanetaryComputer: October 2022, https://doi.org/10.5281/zenodo.7261897

U.S. Department of Commerce, U.S. Census Bureau, TIGER/Line Shapefile, Current, State, Arizona, County Subdivision, https://www2.census.gov/geo/tiger/TIGER2024/COUSUB/tl_2024_04_cousub.zip [Date Access: 12/06/2025]
