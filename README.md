# Pymaceuticals Inc. Data Analysis

This repository contains a Python script for analyzing data from Pymaceuticals Inc., a pharmaceutical company specializing in anti-cancer medications. The script performs various data analysis tasks and generates visualizations to analyze the effectiveness of different drug regimens in treating squamous cell carcinoma (SCC), a form of skin cancer, based on an animal study.

## Overview

The script conducts the following analysis tasks:

- Data preparation: It reads data from two CSV files containing mouse metadata and study results, merges them into a single DataFrame, and cleans the data by removing duplicate entries.

- Summary statistics: It calculates summary statistics including mean, median, variance, standard deviation, and standard error of the mean (SEM) for tumor volume for each drug regimen.

- Visualization: It generates bar charts using Pandas and Matplotlib to show the total number of timepoints for each drug regimen and pie charts to display the distribution of female versus male mice.

- Quartiles, outliers, and box plots: It calculates the final tumor volume for each mouse across selected treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin), identifies potential outliers, and creates box plots to visualize the distribution of tumor volume for each treatment group.

- Line and scatter plots: It generates a line plot to show tumor volume versus time point for a single mouse treated with Capomulin and a scatter plot to display mouse weight versus the average observed tumor volume for the entire Capomulin regimen.

- Correlation and regression: It calculates the correlation coefficient and performs linear regression analysis between mouse weight and average observed tumor volume for the Capomulin treatment regimen, and plots the linear regression model on top of the scatter plot.

## Usage

To use the script, ensure you have Python installed along with the necessary libraries: Pandas, Matplotlib, NumPy, and SciPy. Then, clone the repository and execute the script in a Python environment.

```bash
git clone https://github.com/yourusername/pymaceuticals-analysis.git
cd pymaceuticals-analysis
python analysis_script.py
```

Make sure to replace `yourusername` with your GitHub username.

## Files Included

- `analysis_script.py`: The Python script for data analysis.
- `data/`: Directory containing the input data files (`Mouse_metadata.csv` and `Study_results.csv`).
