# S1-iceberg-areas

This repository contains the code underlying the paper "Backscatter-sensitive iceberg areas from Sentinel-1 extra-wide swath SAR data". This repository documents the used code, but it is not meant to be an executable. If you are interested in running code on your own machine or you have other questions, please get in touch.

## Iceberg area model

In the paper, we present a regression model for predicting backscatter-sensitive iceberg areas from Sentinel-1 data. We provide the algorithm as a Python package: URL

## Content of this repository
The repository includes the following code:
- the CFAR algorithm,
- search and download CARRA metocean data,
- search, download, and filter data, preprocess, detect icebergs from Sentinel-1 and Sentinel-2 data,
- extract information from matched Sentinel-1 and Sentinel-2 icebergs,
- merge iceberg matches across all Sentinel-2 tiles,
- quantify the error in Sentinel-1 iceberg areas compared to Sentinel-2 areas,
- analyze the error with respect to backscatter statistics,
- train and evaluate iceberg area models,
- various helper tools.

Additionally, the repository includes CSV files that contain the iceberg matches analyzed in the paper, including all statistics extracted from Sentinel-1, Sentinel-2, and from the CARRA metocean data. The files are provided for all analyzed polarization channels, CFAR window sizes, and PFAs.
