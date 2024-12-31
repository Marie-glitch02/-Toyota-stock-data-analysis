# Toyota Stock Data Analysis

This repository contains an analysis of Toyota Motor Corporation's stock data (1980-2024) sourced from Yahoo Finance. The analysis focuses on exploratory data analysis (EDA), moving average crossover strategies, and volume trend analysis.

## Dataset

The dataset includes:
- Date
- Adjusted Close Price
- Open, High, Low, Close Prices
- Volume

### File Structure
- **data/**: Contains the dataset (`Toyota_Data.csv`).
- **notebooks/**: Jupyter notebook version of the analysis.
- **scripts/**: Python script version of the analysis.
- **visualizations/**: Folder to store generated plots (optional).

## Analysis Overview

### Exploratory Data Analysis (EDA)
- Time-series plots of adjusted close prices.
- Identification of high trading volume periods.
  <img width="545" alt="12" src="https://github.com/user-attachments/assets/f21a7d1e-2901-4286-9cd5-a4a24db070e7" />


### Moving Average Crossover Strategy
- Calculated 50-day and 200-day Simple Moving Averages (SMA).
- Identified buy and sell signals based on SMA crossovers.
  <img width="533" alt="13" src="https://github.com/user-attachments/assets/dd172f66-e927-4a80-b50a-18042bd6c0df" />


### Volume Analysis
- Trend analysis of trading volume.
- Highlighted periods of unusually high trading activity (95th percentile).
<img width="554" alt="14" src="https://github.com/user-attachments/assets/61713162-da70-4eee-b9b3-6113cf0cd498" />


