# Georeferencing Audit Analysis

This repository contains a Jupyter notebook for auditing georeferencing data using two methods to identify inconsistencies in location data (e.g., client addresses). The analysis is designed to be generic, reusable, and privacy-conscious, using synthetic data.

## Features
- **Method 1: Real Coordinates Analysis**: Identifies clusters of reference coordinates that are too close (e.g., <500 meters), indicating potential duplicates or errors.
- **Method 2: Estimated Coordinates Analysis**: Compares reference coordinates with those estimated via a geocoding API (simulated or real, e.g., Google Maps) to detect inaccuracies.
- Modular Python code with error handling.
- Interactive Plotly visualizations (maps, histograms) and Matplotlib plots.
- Comprehensive documentation and actionable recommendations.

## Requirements
```bash
pip install pandas numpy matplotlib seaborn geopy plotly