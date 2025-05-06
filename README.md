# Bloodfed-Collections
This repository contains the data and code used to analyse mosquito trap collections from Australian piggeries, with a focus on identifying the most effective methods for collecting bloodfed mosquitoes. The analysis was conducted using a Generalized Linear Mixed Model (GLMM) framework with environmental covariates.

## Contents
TrapsPaperPublication.qmd – Full analysis script written in Quarto, including model fitting, cross-validation, visualisations, and summary tables.

BloodmealDataPublication.xlsx – Raw field data of mosquito collections, including collection method, location, bloodfed count, and sampling metadata.

### Environmental covariates:

Precipitation:

Piggery1Precip.csv, Piggery2Precip.csv, Piggery3Precip.csv, Piggery4Precip.csv, WestmarPrecip.csv

Temperature:

Piggery1Temp.csv, Piggery2Temp.csv, Piggery3Temp.csv, Piggery4WestmarTemp.csv, Piggery5Temp.csv

Vegetation and moisture indices:

NDVI.csv, NDWI.csv, NDMI.csv

Evapotranspiration:

Evapotranspiration (ETa).csv

## Description
Mosquitoes collected at multiple commercial piggery sites were analysed to assess how collection method performance varies across environmental conditions and mosquito density. The analysis standardised bloodfed mosquito counts, merged them with spatial covariates, and applied GLMMs to model collection outcomes.

Key steps include:

Data cleaning and standardisation

Integration of Sentinel-2 and climate data

Model selection and comparison (AIC, ΔAIC ≤ 2)

Cross-validation

Plotting predicted trap performance across density gradients

Reproducibility
