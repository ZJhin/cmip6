# CMIP6 water mass transformation
This repository contains the code and processes used to investigate "How sea ice affects water mass transformation in CMIP6 models", as part of Zijin's Chapter 1. The project is divided into two main parts:
Code have 2 main parts. 

# Project Structure
## 1. Pre-Processing: 1_step1_data_initial_process.ipynb
This notebook handles the time-consuming pre-calculation steps required to process raw data. \
Key tasks include:

Data Preparation: Loading and cleaning raw CMIP6 datasets.\
Climatology Computation: Calculating the climatological averages of relevant variables over the given time period.\
Output Generation: Saving intermediate results to reduce runtime for subsequent analysis.
## 2. Visualization and Analysis: 1_step2.ipynb
This notebook focuses on presenting the results through visualizations. \
Key tasks include:

Data Loading: Importing pre-processed data from the previous step.\
Plot Generation: Creating visualizations to analyze and interpret the impact of sea ice on water mass transformation.\
Analysis Outputs: Producing plots and figures for use in reports and publications.

# How to Use
## 1.Run "1_step1_data_initial_process.ipynb"

Ensure all raw CMIP6 datasets are in the appropriate directory.
Execute this notebook to generate pre-processed climatological data.
Note: This step is computationally intensive and may take a significant amount of time.
## 2.Run "1_step2.ipynb"

Load the outputs from Step 1.
Generate and analyze the plots to interpret the relationship between sea ice and water mass transformation.
