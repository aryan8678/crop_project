# Setup Guide

This project contains agricultural datasets and a Jupyter notebook for analysis.

## Project Contents

- `Untitled.ipynb` - notebook for analysis
- `crop_price_data.csv` - crop pricing data
- `crop_production_data.csv` - crop production data
- `soil_analysis_data.csv` - soil metrics data
- `water_usage_data.csv` - water usage data
- `mustard_model.pkl` - saved model artifact

## Prerequisites

- Python 3.9+ (recommended)
- Jupyter Notebook support in VS Code

## Environment Setup

If `venv` already exists (as in this workspace):

```bash
source venv/bin/activate
```

If you need to create it from scratch:

```bash
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
```

## Install Common Packages

Install the basic packages typically used with this dataset/notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Running the Notebook

1. Open `Untitled.ipynb` in VS Code.
2. Select the Python kernel from `venv`.
3. Run cells in order.

## Optional: Verify Data Files

Run this in the terminal to verify all CSV files are present:

```bash
ls -1 *.csv
```

## Deactivate Environment

When done:

```bash
deactivate
```
