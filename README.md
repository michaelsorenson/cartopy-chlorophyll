# Cartopy Chlorophyll

This repository contains code to plot Chlorophyll-A density using cartopy and matplotlib, with data downloaded from NOAA's satellite imagery.

## Data

Station data (CalCOFIStationOrder.csv) is found from CalCOFI's website: https://calcofi.org/sampling-info/station-positions/

Chlorophyll data is found from https://coastwatch.pfeg.noaa.gov/erddap/files/erdMWchla1day/, where the NOAA CoastWatch uploads Chlorophyll-a concentration each day, as measured from NASA's Aqua Spacecraft.

## 01_NOAA_Chlorophyll_Plotting.ipynb

This notebook contains code to plot the CalCOFI stations on top of a map background, and also contains code to plot chlorophyll density over the same map. To plot chlorophyll densities in this notebook, you must download data files from [NOAA's ERDDAP](https://coastwatch.pfeg.noaa.gov/erddap/files/erdMWchla1day/) into the data folder.