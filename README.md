# Blockhouse_Work_Trial_Test

## Description
This repository contains Python scripts and Jupyter notebooks for analyzing Order Flow Imbalance (OFI) and its cross-impact on financial market data. The project includes data preprocessing, OFI calculation, self- and cross-impact analysis, and visualizations of key findings.

## Steps to Run
### Part 1: Data Preprocessing and Self-Impact Analysis
Preprocess raw data and generate OFI for each stock.
Analyze the self-impact of each stock on its returns.
### Part 2: Cross-Impact Analysis
Perform contemporaneous and lagged cross-impact analysis for multiple stocks.
Evaluate the influence of one stock’s OFI on others’ returns.
### Part 3: Optional: Cross-Sector Impact (Example: JPM)
Develop a model to explore cross-sector impact, using JPM as an example.
### Part 4: Visualization
Generate heatmaps, scatter plots, and time-series visualizations to illustrate key insights.

## Key Findings
### Self-Impact Dominance:
Self-impact accounts for the majority of price variations across all stocks analyzed, highlighting its central role in price dynamics.
### Lagged Prediction Weakness:
Lagged cross-impact analysis shows that predictive power diminishes over time, with R² values decaying significantly as the lag increases.
