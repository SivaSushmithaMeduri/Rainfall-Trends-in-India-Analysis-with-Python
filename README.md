# Rainfall-Trends-in-India-Analysis-with-Python

## Overview
This project analyzes rainfall trends in India from 1901 to 2015 using Python and Plotly for interactive visualizations. The analysis covers:

* Annual rainfall trends

* Monthly and seasonal rainfall patterns

* Rainfall anomalies over time

## Dataset

The dataset used in this analysis is the rainfall_area-wt_India_1901-2015.csv file, which includes:

* YEAR: The year of observation

* ANNUAL: Total annual rainfall (mm)

* Monthly Rainfall: JAN to DEC columns representing rainfall in each month (mm)

* Seasonal Rainfall: JF (Winter), MAM (Pre-monsoon), JJAS (Monsoon), OND (Post-monsoon)

## Installation

To run this project locally, install the required dependencies:
          
          pip install pandas plotly numpy prophet

## Key Visualizations

* Annual Rainfall Trends: A line graph showing yearly rainfall variations.

* Monthly Rainfall Patterns: A bar chart highlighting months with the highest and lowest rainfall.

* Seasonal Rainfall Analysis: A grouped bar chart showing rainfall distribution across seasons.

* Rainfall Anomalies: A scatter plot identifying extreme rainfall years.


## Why These Libraries?

* pandas: Efficiently processes tabular rainfall data.

* plotly: Creates interactive and dynamic visualizations.

* numpy: Handles numerical operations for calculating means and anomalies.

* prophet: Time series forecasting model developed by Facebook, ideal for handling trends and seasonality in rainfall data.










