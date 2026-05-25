# thesis-bezpiaty
2024 New York Tornado Season Analysis

A climatological and environmental analysis of the 2024 tornado season in New York State using reanalysis data and historical tornado records.


Overview

This repository contains the code, analysis workflow, and visualizations developed for an undergraduate thesis examining whether the 2024 tornado 
season in New York was anomalous relative to historical climatology, and whether the atmospheric environments associated with the season were also 
unusual.

The project combines historical tornado observations with meteorological reanalysis data to investigate trends and anomalies in severe weather environments across New York State.

The analysis focuses on:

Tornado occurrence frequency and seasonality
Atmospheric instability and wind shear environments
Comparison of 2024 conditions against long-term climatology
Spatial and temporal variability in severe weather parameters


Research Questions

This project was designed around two primary questions:

Was the 2024 tornado season in New York anomalous compared to the historical record?
Were the large-scale atmospheric environments associated with the 2024 season also anomalous?

To address these questions, the project evaluates both tornado occurrence data and several commonly used severe weather parameters derived from atmospheric reanalysis datasets.


Variables Analyzed

The environmental analysis includes:

Convective Available Potential Energy (CAPE)
Storm Relative Helicity (SRH)
Vertical Wind Shear
Significant Tornado Parameter (STP)
Seasonal and annual averages of the above variables

These parameters were analyzed spatially and temporally to assess how the 2024 season compared to climatological expectations.


Data Sources

Datasets used in this project include:

ERA5 atmospheric reanalysis


Repository Structure
.
├── code/
│   ├── cape/
│   ├── shear/
│   ├── helicity/
│   ├── stp/
│   ├── averages/
│   
├── figures/
│   ├── maps/
│   ├── time_series/
│   └── composites/
│ 
├── thesis/
│
└── README.md


Methods Summary

The workflow generally followed these steps:

Define spatial and temporal bounds for the study
Retrieve and reprocess atmospheric reanalysis data
Calculate or aggregate severe weather parameters
Generate climatological baselines
Compare 2024 values against historical distributions
Visualize spatial and temporal anomalies
Interpret results in the context of New York tornado climatology

All analysis and visualization was performed in Python.

Tools and Libraries

This project primarily uses:

Python
xarray
pandas
numpy
matplotlib
cartopy

Additional packages may be added as the repository develops.

Example Outputs

The repository includes:

Spatial anomaly maps
Seasonal time series
Environmental composites
Climatological comparisons
Severe weather parameter visualizations

This project was completed as an undergraduate thesis.

Advisor: Osamu Miyawaki

Current Status

This repository is currently being organized and expanded. Additional documentation, cleaned workflows, processed datasets, and reproducibility 
instructions will be added over time.

Future Work

Potential future directions include:

Expanding the climatological period
Additional environmental parameters
Automated ERA5 retrieval workflows
Interactive visualizations

For questions, collaboration, or discussion related to this work, feel free to reach out through GitHub, or email me at harleybez@gmail.com
