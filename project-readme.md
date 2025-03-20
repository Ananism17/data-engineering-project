# Million Song Dataset Analysis

This repository contains a set of Jupyter notebooks for analyzing the Million Song Dataset (subset) using Apache Spark.

## Overview

This project demonstrates scalable data processing techniques using PySpark to analyze musical features and artist diversity in the Million Song Dataset subset. The analysis includes outlier detection, feature importance, and artist style diversity measurements.

## Notebooks

The repository consists of three main notebooks:

1. **h5_to_csv.ipynb**
   - Converts the original HDF5 (h5) format Million Song Dataset files to CSV format
   - Makes the data more accessible for analysis with PySpark

2. **scalability_analysis.ipynb**
   - The main analysis notebook that:
     - Sets up a Spark session with dynamic allocation
     - Loads and preprocesses the CSV data
     - Performs outlier detection using Z-score methodology
     - Identifies artists with the widest range of musical styles
     - Calculates style diversity scores based on feature ranges

3. **results_plotting.ipynb**
   - Creates visualizations of the analysis results
   - Plots outlier distributions, feature importance, and artist diversity rankings


## Setup and Requirements

- Apache Spark cluster
- Python libraries: PySpark, pandas, matplotlib, numpy
- Input data: Million Song Dataset subset CSV file
