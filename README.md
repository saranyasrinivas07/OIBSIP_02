# OIBSIP Project 2 – Unemployment Analysis

This repository contains my submission for Project 2 of the Oasis Infobyte Data Science Internship.

## Objective

To analyze unemployment data across different regions of India, clean and preprocess the dataset, and visualize trends and patterns using Python.

## Tools and Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

### 1. Data Cleaning

- Loaded the unemployment dataset using Pandas.
- Inspected the data for null values and missing rows.
- Stripped whitespace from column names for consistency.
- Dropped rows with missing values.
- Converted the `Date` column to datetime format for time-series analysis.

### 2. Exploratory Data Analysis (EDA)

- Reviewed basic statistical summaries of the dataset.
- Checked for the presence of null values after cleaning.
- Examined data types and structure.

### 3. Data Visualization

- **Time-Series Plot:** Visualized the average Labour Participation Rate over time.
- **Bar Chart:** Compared average Unemployment Rates between Rural and Urban areas.
- **Heatmap:** Displayed correlations between numerical features such as:
  - Estimated Unemployment Rate (%)
  - Estimated Employed
  - Estimated Labour Participation Rate (%)

## Key Insights

- Certain regions exhibit significant fluctuations in unemployment rates over time.
- Urban and rural areas show differences in average unemployment rates.
- Correlations exist between employment figures and participation rates, indicating underlying economic patterns.

## Dataset

- File: `Unemployment.csv`
- Features:
  - Region
  - Date
  - Frequency
  - Estimated Unemployment Rate (%)
  - Estimated Employed
  - Estimated Labour Participation Rate (%)
  - Area (Urban/Rural)

## Status

Task Completed

## Author

Saranya Srinivas
