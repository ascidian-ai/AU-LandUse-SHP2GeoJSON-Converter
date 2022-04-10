# ESRI Shape File to GeoJSON Converter example using Australian Collaborative Land Use and Management Program (ACLUMP) data

#### Repo: https://github.com/ascidian-ai/AU-LandUse-SHP2GeoJSON-Converter

This project aims to convert Australian Collaborative Land Use and Management Program (ACLUMP) data from ESRI Shape File format to GeoJSON format using the GeoPandas library.

## Background
Land use areas, as vector datasets, as collected by individual state and territory governments mapping programs as part of the Australian Collaborative Land Use and Management Program (ACLUMP)[1]. These individual datasets are consolidated and harmonised by the Australian Department of Agriculture into the Catchment Scale Land use of Australia – Commodities – Update December 2020 dataset[2].

The Australian Bureau of Agricultural and Resource Economics and Sciences (ABARES)[3], the science and economics research division of the Department of Agriculture, Water and the Environment is responsible for the creation and dissemination of this dataset.

The dataset used in this example notebook was compled as of December 2020 and was sourced from:
https://www.awe.gov.au/sites/default/files/documents/CLUM_Commodities_2020.zip

Information, including detailed metadata, about this dataset can be found at the following location:
https://www.awe.gov.au/abares/aclump/land-use/catchment-scale-land-use-of-australia-commodities-update-december-2020

CLUM data can be used to visualise land use across the entire Australian continent using land use codes defined in v8 of the Australian Land Use Management (ALUM) datset.

*Figure 1 : Catchment scale land use of Australia - update december 2020 (Source: ABARES)*
![Catchment scale land use of Australia - update december 2020 (Source: ABARES)](_images/clum_map_december2020_alum_18class.png | width=100)

## References
[1]	‘About ACLUMP - DAWE’. https://www.awe.gov.au/abares/aclump/about-aclump (accessed Apr. 09, 2022).
[2]	Australian Bureau of Agricultural Resource Economics and Sciences (ABARES), ‘Catchment Scale Land Use of Australia – Update December 2020’. Australian Bureau of Agricultural Resource Economics and Sciences (ABARES), Feb. 26, 2021. doi: 10.25814/AQJW-RQ15.
[3]	‘ABARES - DAWE’. https://www.awe.gov.au/abares
