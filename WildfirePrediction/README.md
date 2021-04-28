# Predicting Wildfire Severity with Machine Learning

Andrew McDonald // CSE 847 // April 2021

## Motivation

[Climate change is to blame for the recent rise in frequency and severity of wildfires](https://www.c2es.org/content/wildfires-and-climate-change/), driving hotter, drier conditions favorable for ignition across the globe. In this project, we aim to predict the severity of a wildfire at ignition-time in a machine learning-driven manner using information from historical wildfires, 30-year climate normals, and month-level meteorological variables. We characterize severity by (i) size in km<sup>2</sup>, (ii) perimeter in km, and (iii) duration in days.

More broadly, we hope this project sheds light on the [power machine learning can bring in the fight against climate change](https://www.climatechange.ai/).

## Summary

Data is obtained from the [Global Fire Atlas](https://www.globalfiredata.org/fireatlas.html) and [NOAA CDO API](https://www.ncdc.noaa.gov/cdo-web/webservices/v2#gettingStarted), code is written in Python, and models are constructed using `sklearn`. The Jupyter notebooks numbered 00 through 09 walk through the data scraping, cleaning and preprocessing, along with model training, hyperparameter selection via cross-validation, and model evaluation on each target variable.

A comprehensive project report is available [here]() for further information.

Notebooks in the `archive/` directory contain intermediate results not detailed in the final project report, but may be of interest to those hoping for a "behind-the-scenes" look at the project's development, including extensive experimentation in geospatial data visualization and management. 

## Contact

Please email Andrew at mcdon499 [at] msu [dot] edu with any questions, ideas, or comments. For more information about MSU's CSE 847 (Graduate Machine Learning), check out [the class website](https://msu-ml.github.io/) or visit course instructor Dr. Jiayu Zhou's [website](https://jiayuzhou.github.io/).
