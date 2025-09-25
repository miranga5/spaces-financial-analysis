# Retail GL & Financial Analytics

This repository contains Python scripts for analyzing retail general ledger (GL) and financial data. The analysis covers data cleaning, aggregation, and visualization of top/bottom GL codes and brands, profit metrics (Gross Profit, EBIT, Net Profit), and key financial ratios (ROA, ROE, GP Margin).  

## Dataset

The dataset used in this analysis was modeled after a real retail dataset but has been fully synthesized for the purpose of this project. All data points are fictional and do not represent any real company. The source CSV files were combined toa PARQUET file to accomodate the volume

## Features

- Data cleaning and preprocessing of GL transactions
- Top 10 GL codes by post amount and monthly trends
- Gross Profit, EBIT, Net Profit analysis over time
- Profit analysis by brand
- Key financial ratios: ROA, ROE, GP Margin
- Correlation analysis: Sales vs COGS, Marketing Spend vs Sales
- Visualizations: bar charts, line charts, stacked area charts, lollipop charts, scatter plots with regression

## Requirements

- Python 3.10+
- pandas
- matplotlib
- seaborn
- numpy

## Usage

1. Clone the repository
2. Install required libraries
3. Run individual scripts for each analysis
4. Modify paths to point to your local dataset if needed

## Note

All PostAmount values are converted to positive values where necessary for consistent analysis. Quarters, months, and years are used for time-based aggregation and trends.

