- `Title`: 2020 Alabama Census Block Groups
- `Abstract`: Vector polygon geopackage layer of Census tracts and demographic data.
- `Spatial Coverage`: Alabama (State). OSM link: [https://www.openstreetmap.org/relation/161950]
- `Spatial Resolution`: Census block groups
- `Spatial Reference System`: EPSG 4269 NAD 1983 geographic coordinate system
- `Temporal Coverage`: 2020 census 
- `Temporal Resolution`: Single census survey period
- `Lineage`: Downloaded from the U.S. Census APL "pl" public law summary file using 'tidycensus' in R
- `Distribution`: US Census API
- `Constraints`: Public Domain data free for use and redistribution.

| Label | Alias | Definition | Type | Accuracy | Domain | Missing Data Value(s) | Missing Data Frequency |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| GEOID | ID Code | Code that uniquely identifies census tracts  | Numeric | N/A | ... | ... | ... |
| P4_001N | Total population over 18 | Total population over 18 years old in the 2020 census, divided by block group | Numeric | Generally Accurate | ... | ... | ... |
P4_006N | Total black population over 18 | Total black population over 18 years old in the 2020 census, divided by block group | Numeric | The US Census tends to overcount white populations and undercount those of minorities ([US Census](https://www.census.gov/newsroom/press-releases/2022/2020-census-estimates-of-undercount-and-overcount.html)) | ... | ... | ... |
| P5_003N | Institutionalized population | Total institutionalized population in correctional facilities for adults during the 2020 census, 18 years or older divided by block group  | Numeric | The US Census tends to overcount white populations and undercount those of minorities ([US Census](https://www.census.gov/newsroom/press-releases/2022/2020-census-estimates-of-undercount-and-overcount.html)) | ... | ... | ... |
| 