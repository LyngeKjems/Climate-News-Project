# Climate News Coverage at Jyllands Posten
### Investigating correlation between climate news coverage and weather deviations

## Overview
This repository contains the collection, cleaning, and analysis of data that investigates the correlation between climate news coverage and weather deviations, using articles from Jyllands Posten and weather data from DMI.

## Table of Contents
- [Data Collection and Cleaning](#data-collection-and-cleaning)
- [Descriptive Statistics and Analysis](#descriptive-statistics-and-analysis)
- [Usage](#usage)

---

## Data Collection and Cleaning

1. **Notebook**: `Webscrape_JP.ipynb`
   - **Description**: Extracts articles related to climate change from Jyllands Posten's [online archives](https://jyllands-posten.dk/).
   
2. **Notebook**: `News_cleaning.ipynb`
   - **Description**: Processes the raw scraped data from Jyllands Posten to refine and structure it for analysis.
   
3. **Notebook**: `Weather_daily.ipynb`
   - **Description**: Obtains daily weather data points from DMI's API
   
4. **Notebook**: `Weather_monthly.ipynb`
   - **Description**: Gathers aggregated monthly weather data from DMI

---

## Descriptive Statistics and Analysis

5. **Notebook**: `Merged_daily_data.ipynb`
   - **Description**: This notebook undertakes several tasks:
     - **Merging**: Combines daily weather data with the news data to produce a unified dataset.
     - **Visualization**: Creates plots and charts to provide a visual perspective of the data trends and potential correlations.
     - **OLS Regressions**: Conducts Ordinary Least Squares regressions to quantitatively assess relationships within the data.
   
6. **Notebook**: `Merged_monthly_data.ipynb`
   - **Description**: This notebook mirrors the operations of the daily data notebook but operates on a monthly aggregated level. Activities include:
     - **Merging**: Combines monthly weather data with the news data.
     - **Visualization**: Displays monthly trends and deviations through visual mediums.
     - **OLS Regressions**: Performs regressions on the monthly dataset to derive insights and statistical significance.


---

## Usage

To ensure the analysis's integrity, please execute the Jupyter notebooks in the following sequence:

1. `Webscrape_JP.ipynb`
2. `News_cleaning.ipynb`
3. `Weather_daily.ipynb`
4. `Weather_monthly.ipynb`
5. `Merged_daily_data.ipynb`
6. `Merged_monthly_data.ipynb`

Executing them in this order will ensure data continuity and the correctness of results.

---

