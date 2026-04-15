# Research Project: Ice Accretion Analysis Using WRF and FRAM

Author: Alison Chatham \
Institution: University of Illinois Urbana-Champaign \
Date: April 2026 

1. Project Overview

This repository contains code and analysis workflows used to investigate freezing rain ice accretion from a WRF-ARW ensemble simulation of the 14 December 2024 winter storm. The primary objectives of this project are to:
- Implement the Freezing Rain Accumulation Model (FRAM) on WRF output
- Evaluate ice accretion forecasts across ensemble members
- Compare modeled ice accretion against surface observations (NWS)
- Assess spatial variability and uncertainty in freezing rain impacts

2. Scientific Background

Freezing rain produces ice accretion when supercooled liquid precipitation freezes upon contact with exposed surfaces. The amount of ice accumulation depends on both precipitation and near-surface thermodynamic conditions. This project applies the Freezing Rain Accumulation Model (FRAM), an empirical model used to estimate ice accretion from commonly available meteorological variables.

FRAM incorporates:
- Liquid-equivalent precipitation
- Near-surface air temperature
- Wet-bulb temperature
- Wind speed

Dew point (or wet-bulb temperature) is used to better represent thermal conditions governing accretion efficiency, including the effects of evaporative cooling and latent heat exchange. This improves estimation of whether precipitation will freeze efficiently upon contact.

FRAM uses regime-based relationships to estimate ice accretion and produces:
- Flat ice accretion (horizontal surfaces)
- Radial ice accretion (cylindrical structures, e.g., power lines)

As an empirical diagnostic model, FRAM does not explicitly simulate detailed microphysical processes such as droplet size distributions. Instead, it provides a computationally efficient method for estimating ice accretion from model output (e.g., WRF), making it well suited for ensemble and post-processing applications.

3. Repository Structure
- FRAM_implementation.ipynb (Core FRAM algorithm applied to WRF output)
- variables_in_wrfout.ipynb (Exploration and extraction of WRF variables)
- ensemble_analysis.ipynb (Ensemble processing and statistical analysis)
- ..... ([placeholder])
- README.md     

4. Data Sources\
WRF Model Output\
Model: WRF-ARW\
Case: 14 December 2024 winter storm\
Format: NetCDF (wrfout files)\
Variables Used:
- [placeholder]
[Your Email]
