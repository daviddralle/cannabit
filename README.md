README

Cannabis Effects on Streamflow

This repository contains code and data associated with the analysis of streamflow depletion due to cannabis cultivation, as detailed in the manuscript Assessing streamflow depletion from agricultural groundwater use in headwater catchments using storage-discharge functions.

DOI for Data

The data associated with this repository is available on Zenodo: 10.5281/zenodo.14902190

Repository Contents

Data Files

20211201_dry_discharge_daily.csvUsed in script Cannabit_phil_R.ipynb.

20240405_Full_Catchment_Statistics.csvStatistics associated with the catchments on the landscape for cannabis area and percent cover, used in script Cannabit_phil_R.ipynb.

20240621_Cannabis Farm Annual and Monthly Water Prediction Totals_Phil Task.csvEstimates of monthly water use in permitted and unpermitted farms in Mendocino and Humboldt counties, used in script Cannabit_phil_R.ipynb.

20240802_modeled_use_flow_landscape_coverage.csvData for modeled farm use, used in cannabit_gq_phil.ipynb.

level4e.csvData file used in hydrograph modeling.

sims_data.csvOutput file of cannabit_gq_phil.ipynb that contains all synthetic hydrographs and modeled scenarios, used for plotting and figures in Cannabit_phil_R.ipynb.

Code Files

Cannabit_phil_R.ipynbCode for analysis, summaries, and figure generation.

cannabit_gq_phil.ipynbCode that uses storage-discharge sensitivity functions to generate hydrographs for both streams for all scenarios and makes figures.

Documentation

README.mdThis document, describing the repository contents and usage.

Usage

This repository provides data and analysis scripts to evaluate the hydrological impacts of cannabis agriculture. The scripts require R and relevant libraries to run properly. If using Google Colab, ensure that necessary dependencies are installed before execution.

Citation

If you use this data or code, please cite the associated Zenodo DOI and the published manuscript.
