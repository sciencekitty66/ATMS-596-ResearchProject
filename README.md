# Modeling Ice Accretion Impacts on Electric Infrastructure Using WRF Output

This repository contains the Jupyter notebooks, scripts, and figures associated with the case study analyzing the meteorological conditions and subsequent customer power outages on December 14, 2024.

## Repository Contents:
1. Notebooks:
+ FRAMandOutageAnalysis.ipynb - Contains the statistical modeling and regression analysis, specifically examining the relationship between radial ice accretion and customer power outages (utilizing statsmodels OLS).
+ variables_in_wrfout.ipynb - Contains workflows for processing and visualizing WRF model outputs, calculating variables such as wet-bulb temperature, and creating animations of event evolution.
2. In-Development Notebooks:
+ FRANA_implementation.ipynb
+ ensemble_analysis.ipynb
3. Figures
+ /figures - Contains output plots and geospatial visualizations for the event

## Usage:
WRF Extraction: Start by opening variables_in_wrfout.ipynb to process output from the December 14, 2024, case study and generate initial animations or plots.

Statistical Modeling: Run FRAMandOutageAnalysis.ipynb to merge meteorological parameters with outage counts and fit the regression models.

## License:
[Open Source / MIT License - update as needed]
