# TimeSeries-HurstExponent
A collection of Python scripts for advanced time series analysis, featuring a refined method for calculating the Hurst exponent. This repository is ideal for researchers and analysts looking to delve into the statistical properties of time series data.

# Time Series Analysis Tools

This repository contains Python scripts for analyzing time series data, including the calculation of the Hurst exponent using a refined method.

## Description

The scripts provided enable users to perform advanced time series analysis. Key features include:

- `refined_hurst_exponent.py`: Calculates the Hurst exponent, a measure of the long-term memory of time series data.
- `load_dataset.py`: Utility script for loading and preprocessing data.

## Getting Started

### Dependencies

- Python 3.x
- NumPy
- Pandas

### Installing

- Clone this repository to your local machine.
- Ensure you have the required dependencies installed.

### Executing Program

1. Load your time series data using `load_dataset.py`.
2. Pass the data to `refined_hurst_exponent.py` to calculate the Hurst exponent.

```python
import load_dataset
import refined_hurst_exponent

# Load your data
data = load_dataset.load("path_to_your_data.txt")

# Calculate Hurst exponent
hurst = refined_hurst_exponent.calculate(data)
