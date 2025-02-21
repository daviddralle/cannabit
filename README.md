# 🌿 Cannabis Effects on Streamflow

This repository contains code and data associated with the analysis of streamflow depletion due to cannabis cultivation, as detailed in the manuscript:

📄 **Assessing Streamflow Depletion from Agricultural Groundwater Use in Headwater Catchments Using Storage-Discharge Functions**  
Authors: Philip Georgakakos, David Dralle, Chris Dillis, Jesse Hahm, Dana Lapides, Ted Grantham  

## 📥 Data Access

The dataset associated with this repository is available on Zenodo:  
🔗 **[DOI: 10.5281/zenodo.14902190](https://doi.org/10.5281/zenodo.14902190)**

## 📂 Repository Contents

### 📊 Data Files
- **`20211201_dry_discharge_daily.csv`** – Used in `Cannabit_phil_R.ipynb` for dry discharge data.
- **`20240405_Full_Catchment_Statistics.csv`** – Contains statistics on cannabis area and percent cover for catchments, used in `Cannabit_phil_R.ipynb`.
- **`20240621_Cannabis Farm Annual and Monthly Water Prediction Totals_Phil Task.csv`** – Estimates of monthly water use for permitted and unpermitted farms in Mendocino and Humboldt counties.
- **`20240802_modeled_use_flow_landscape_coverage.csv`** – Data for modeled farm use, used in `cannabit_gq_phil.ipynb`.
- **`level4e.csv`** – Data file used in hydrograph modeling.
- **`sims_data.csv`** – Output file from `cannabit_gq_phil.ipynb` containing synthetic hydrographs and modeled scenarios for visualization in `Cannabit_phil_R.ipynb`.

### 🖥️ Code Files
- **`Cannabit_phil_R.ipynb`** – Code for analysis, data summaries, and figure generation.
- **`cannabit_gq_phil.ipynb`** – Uses storage-discharge sensitivity functions to generate hydrographs for streams under different scenarios.

### 📖 Documentation
- **`README.md`** – This document, describing the repository contents and usage.

## ⚙️ Usage

This repository provides data and analysis scripts to evaluate the hydrological impacts of cannabis agriculture. The scripts require **R** and relevant libraries to run properly.

### Running the Analysis in R
1. Install the required packages in R:
   ```r
   install.packages(c("tidyverse", "ggplot2", "dplyr", "lubridate"))
