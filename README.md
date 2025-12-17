# FinAnalyzeNet: Financial Volatility Forecasting Dataset

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-green.svg)](https://www.python.org/downloads/)
[![Pandas](https://img.shields.io/badge/pandas-2.0%2B-orange)](https://pandas.pydata.org/)
[![Dataset Size](https://img.shields.io/badge/dataset%20size-~500MB-brightgreen)]()
[![License: Academic](https://img.shields.io/badge/License-Academic-blue.svg)](LICENSE)

## 📊 Overview
This repository contains the complete dataset and code for reproducing the results of:
**"A Hybrid Deep Learning Framework for Volatility Prediction in Financial Markets"**

## Dataset Structure

### Raw Data
- `raw/equity_indices/`: Daily and 5-minute data for 5 major indices
- `raw/individual_stocks/`: Daily data for 50 stocks across 5 sectors
- `raw/currency_pairs/`: Hourly and daily forex data for 4 major pairs
- `raw/commodities/`: Daily commodity futures data
- `raw/macroeconomic/`: Daily macroeconomic indicators
- `raw/sentiment/`: Hourly and daily market sentiment data

### Processed Data
- `processed/features/`: Engineered features for volatility forecasting
- `processed/realized_volatility/`: Computed realized volatility measures
- `splits/`: Temporal train/validation/test splits

### Results
- `results/figures/`: Data underlying all figures in the paper
- `results/tables/`: Data underlying all tables in the paper

## Reproducibility
All results can be reproduced using the provided Python scripts. See `reproduce_all.py` for complete replication.

## Citation
If you use this dataset, please cite our paper.

## License
Academic use only. See LICENSE file for details.
