# GRIDCERF: Geospatial Raster Input Data for Capacity Expansion Regional Feasibility
Harmonized geospatial data to support feasibility analyses of energy system transitions in the United States

![image](https://github.com/IMMM-SFA/gridcerf/assets/74064300/d49d5e0e-015a-4289-bfc0-3900f769f2e6)

## Overview
Meeting increasing future electricity demand in the United States will require extensive and explorative planning due to advancing climatic, socioeconomic, and decarbonization policy drivers.  Accounting for the response of changes in these drivers on the energy system are made even more complex when considering them in aggregate form with regionally relevant land and technology constraints that narrow where power plants capable of supporting increasing demand will be feasible to operate under uncertain futures.  We offer the Geospatial Raster Input Data for Capacity Expansion Regional Feasibility (GRIDCERF) data package as a high-resolution product to readily evaluate siting suitability for renewable and non-renewable power plants in the conterminous United States for alternative energy futures. GRIDCERF provides 269 suitability layers for use with 56 power plant technology configurations in a harmonized format readily ingestible by geospatially-enabled modeling software.  GRIDCERF comes equipped with pre-compiled technology-specific suitability layers but also allows for user customization to robustly address science objectives when evaluating varying future conditions.

Though the GRIDCERF data can be used for standalone geospatial analysis, the GRIDCERF layers can also be directly used with the open source power plant siting model CERF (Capacity Expansion Regional Feasibility). More information on the CERF model is available here: https://github.com/IMMM-SFA/cerf 

This repository includes Jupyter Notebooks to support GRIDCERF development. 

## Download the Compiled Raster Data

All compiled raster data for common layers, technology specific layers, and combinations compiled by technology are available for download from MSDLive.

[MSDLive Link]

## How to Use this Repository

The following are a step-by-step approach to reproduce the raster data presented in the GRIDCERF data package.

1. Clone this repository to your local machine.
2. Download and unzip the GRIDCERF package into the data directory of this repository.
3. For each dataset of interest, follow the data source described in the beginning of the appropriate notebook to download the original source data. Note that original source data is not provided as part of GRIDCERF due to licensing restrictions.
4. Save the downloaded source file to the raw data folder
5. Update the source file path in the notebook and run the file.
