# Retail Financial Analytics & GL Data Modelling
## Overview
This project focuses on transforming raw general ledger (GL) data into a structured, analytics-ready dataset to support financial performance analysis and decision-making.

The objective was not just to analyse financial data, but to replicate how finance data is prepared, modelled, and interpreted in real-world environments.

## Problem Context
Retail financial data is often fragmented across transactions and lacks a consistent structure for analysis. This makes it difficult to:

- Identify performance trends across time
- Analyse profitability by segment (e.g. brand, GL category)
- Derive meaningful financial ratios
- Perform scalable, repeatable analysis

## Approach
### Data Preparation & Modelling

- Cleaned and standardised raw GL transaction data
- Consolidated multiple CSV sources into a single Parquet dataset for performance and scalability
- Structured data to support time-based and dimensional analysis

### Financial Analysis

- Built logic for:
  Gross Profit, EBIT, Net Profit
  Key ratios: ROA, ROE, Gross Profit Margin
  
- Aggregated results across:
  Time (monthly, quarterly)
  GL codes
  Brand segments
  
## What This Enables
- Scalable financial reporting from structured datasets
- Faster identification of performance drivers
- Foundation for advanced use cases such as:
- forecasting
- anomaly detection
- margin optimisation

## Dataset
The dataset is fully synthesised and modelled to reflect realistic retail financial structures.
It does not represent any real organisation.

## Technical Stack
- Python (pandas, numpy)
- Data storage: Parquet
- Visualisation: matplotlib, seaborn

## Key Notes
- Post amounts were standardised to ensure consistency across analysis
- Time-based aggregations (month, quarter, year) were used to support trend analysis
