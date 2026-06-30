# PM2.5-component-mixtures_TB
# Associations of distributed Lag-Weighted PM2.5 component mixtures and pulmonary tuberculosis incidence in China: A BKMR and Quantile G-Computation analysis

This repository contains data and code for the study **"Associations of distributed Lag-Weighted PM2.5 component mixtures and pulmonary tuberculosis incidence in China: A BKMR and Quantile G-Computation analysis"** by Cheng et al.

## Data

The `Data` folder contains the following files:

- **Tuberculosis surveillance data** (2013-2019):
  - `anhui_new_13-19.csv` - Case data for Anhui province
  - `sichuan_new_13-19.csv` - Case data for Sichuan province

- **Geographic boundary files**:
  - `China.shp` - National boundaries of China
  - `Anhui.shp` - Provincial boundaries of Anhui
  - `Sichuan.shp` - Provincial boundaries of Sichuan
  - `Nine-dash_line.shp` - Maritime boundaries

## Code

All analysis scripts are located in the `Code` folder and are organized sequentially:

1. **`1_Main_model.R`**
   - Loads required packages and defines functions
   - Performs model selection and runs primary statistical models

2. **`2_Stratified_sex_and_age.R`**
   - Fits stratified models by sex and age groups
   - Conducts subgroup analyses

3. **`3_Linear_interaction.R`**
   - Adds linear interaction terms between pollutants and effect modifiers
   - Tests for effect modification

4. **`4_Sensitivity_analysis.R`**
   - Performs sensitivity analyses with alternative model specifications
   - Assesses robustness of primary findings

5. **`5_Main_Figures.R`**
   - Generates main figures and visualizations for the manuscript
   - Creates publication-ready graphics
