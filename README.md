# WorldPop Age and Gender Structures Processing

This repo focuses on the processing, visualisation, and analysis of WorldPop Age and Gender Structures data through comprehensive Jupyter notebooks and associated tools. The repository provides a complete workflow for handling demographic data from the WorldPop project, enabling the extraction of insights from population distribution datasets.
Work developped by Anna 
## Repository Structure

```
worldpop_processing/
│
├── NB1/
│   ├── world_pop_processing_rev4.ipynb    # Primary WorldPop data processing notebook to create multiband composites
│   └── environment.yaml                   # Conda environment specifications
│
├── NB2/
│   ├── arcgis_zonal_stats_rev3.ipynb     # ArcGIS-based zonal statistics analysis, gpkg creation and population pyramid visualisation
│   └── arcgispro_environment.yml         # ArcGIS Pro environment specifications
│
├── R/
│   └── wopr_cat_vision.R                 # Basic R script for exploring WOPR data availability and accessing WOPR Vision locally
│
└── README.md                             # This file
```

### Directory Overview

**NB1/** - Primary data processing workflows
- Contains the main WorldPop data processing notebook with comprehensive analysis pipelines
- Includes Python environment specifications for reproducible setup

**NB2/** - Spatial analysis with ArcGIS
- Focuses on zonal statistics calculations using ArcGIS tools
- Includes specific environment file for ArcGIS Pro integration

**R/** - R-based analysis components  
- Contains R scripts for specialised WOPR (WorldPop Open Population Repository) analysis
- Supports categorical vision and advanced statistical processing



## Data Sources

This project utilises datasets from the WorldPop project, specifically focusing on Age and Gender Structure datasets
For accessing WorldPop data, visit [HDX](https://data.humdata.org/organization/worldpop?dataseries_name=WorldPop+-+Age+and+Gender+Population+Structures) or [worldpop.org]([https://www.worldpop.org](https://hub.worldpop.org/geodata/listing?id=138)) to learn more about the latest datasets and documentation.

## Usage

The notebooks are designed to be run sequentially, with each notebook building upon the outputs of previous processing steps.

Begin by running the contents of NB1 in VSC or Jupyter Lab, before moving on to NB2, which is designed specifically for ArcGIS Pro due to its reliance on ArcPy.

Each notebook contains detailed documentation explaining the methodology, data sources, and expected outputs. Code cells include comments describing processing steps and analytical decisions.



## Data Citation

When using outputs from this repository, please cite the relevant WorldPop datasets and acknowledge the processing methodologies developed in this project.

## Contact

For questions about the repository or collaboration opportunities, please feel free to reach out via the contact links on my profile.
