# PIM for Computing 3D EOFs
This repository contains code to compute the partition input method (PIM). This method enables 3D EOF computation for a large dataset on regular personal computers with limited memory. 

## The data
This code specifically uses Global Ocean Physical Reanalysis (GLORYS) for the calculation. It can be found at [the Copernicus Marine Environment Monitoring Service website](https://data.marine.copernicus.eu/product/GLOBAL_MULTIYEAR_PHY_001_030/description). It is highly recommended to use external memory to store the data. 

The user will need to store:
- GLORYS data
- Climatologies
- Anomalies
- Eigenvalues and eigenvectors
- 3D EOFs

**GLORYS data is 1.31 GB for a single month and year**. The same will be true for each a anomaly, and EOF file. 

## How to run
 1. [Download the GLORYS monthly data](https://data.marine.copernicus.eu/product/GLOBAL_MULTIYEAR_PHY_001_030/services). You can find directions on how to download the data [here](https://help.marine.copernicus.eu/en/articles/4469993-how-to-download-copernicus-marine-products)
 2.  Run **Compute Anomalies and Climatologies.ipynb**. Please be mindful of the file path and name for the next step.
 3.  Run **3D EOFs GLORYS.ipynb**. This is heavily dependent on the path the user saved the raw data and anomalies to.

[![DOI](https://zenodo.org/badge/1038361604.svg)](https://doi.org/10.5281/zenodo.17451617)
