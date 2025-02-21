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
- **[`Cannabit_phil_R.ipynb`](https://colab.research.google.com/github/pgeorgakakos/cannabit/blob/main/Cannabit_phil_R.ipynb)** – Code for analysis, data summaries, and figure generation.
- **[`cannabit_gq_phil.ipynb`](https://colab.research.google.com/github/pgeorgakakos/cannabit/blob/main/cannabit_gq_phil.ipynb)** – Uses storage-discharge sensitivity functions to generate hydrographs for streams under different scenarios.

### 📖 Documentation
- **`README.md`** – This document, describing the repository contents and usage.

## ⚙️ Usage

Click the links below to open the analysis notebooks in Google Colab. Once opened, run all cells by selecting **"Runtime" → "Run all"** in the Colab menu.

- **[Open `Cannabit_phil_R.ipynb` in Google Colab](https://colab.research.google.com/github/pgeorgakakos/cannabit/blob/main/Cannabit_phil_R.ipynb)**
- **[Open `cannabit_gq_phil.ipynb` in Google Colab](https://colab.research.google.com/github/pgeorgakakos/cannabit/blob/main/cannabit_gq_phil.ipynb)**

## 🔬 Research Context

Groundwater extraction can deplete streamflow in headwater catchments, impacting ecosystems and water availability. This repository applies **storage-discharge functions** to estimate streamflow depletion due to cannabis agriculture in California's North Coast. The study explores:
- Effects of cannabis cultivation area, irrigation water source, efficiency, and hydrologic conditions on streamflow.
- Streamflow depletion scenarios using the storage-discharge function to predict hydrograph recessions under different pumping scenarios.
- Comparisons of groundwater vs. surface water withdrawals and their hydrological impacts.

## 📜 Citation

If you use this data or code, please cite:  

Georgakakos, P., Dralle, D., Dillis, C., Hahm, J., Lapides, D., & Grantham, T. (2024).  
_Assessing Streamflow Depletion from Agricultural Groundwater Use in Headwater Catchments Using Storage-Discharge Functions._  
🔗 **[DOI: 10.5281/zenodo.14902190](https://doi.org/10.5281/zenodo.14902190)**  

---

For any questions or contributions, feel free to open an **Issue** or **Pull Request**! 🚀
