- `Title`: districts23 Layer of districts.gpkg
- `Abstract`: Spatial bounds and characteristics of U.S. Congressional districts in Alabama
- `Spatial Coverage`: Alabama (State). OSM link: [https://www.openstreetmap.org/relation/161950]
- `Spatial Resolution`: U.S. Congressional Districts
- `Spatial Reference System`: EPSG 3857 WGS 1984 Web Mercator Projection
- `Temporal Coverage`: Districts approved in 2023 for use in the 2024 elections.
- `Temporal Resolution`: N/A
- `Lineage`: Loaded into QGIS as ArcGIS feature service layer and saved in geopackage format. Etraneous data fields were removed and the FIX GEOMETRIES tool was used to correect geometry errors. 
- `Distribution`: Avalible from the Alabama State GIS via ESRI feature service 
- `Constraints`: Public Domain data free for use and redistribution.

| Label | Alias | Definition | Type | Accuracy | Domain | Missing Data Value(s) | Missing Data Frequency |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| DISTRICT | District Number | U.S. Congressional District Number | Numeric | N/A | N/A | N/A | N/A |
| POPULATION | Population | Number of people residing in each congressional district (2020 census) | Numeric | Generally accurate on a full-population scale | ... | ... | ... |
| WHITE | Number of white residents | Total number of white residents (2020 census) | Numeric | The US Census tends to overcount white populations and undercount those of minorities ([US Census](https://www.census.gov/newsroom/press-releases/2022/2020-census-estimates-of-undercount-and-overcount.html)) | ... | ... | ... |
| BLACK | Number of black residents | Total number of black residents (US Census) | Numeric | The US Census tends to overcount white populations and undercount those of minorities ([US Census](https://www.census.gov/newsroom/press-releases/2022/2020-census-estimates-of-undercount-and-overcount.html)) | ... | ... | ... |