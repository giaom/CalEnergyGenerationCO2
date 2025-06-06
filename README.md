# California Energy Generation and CO₂ Emissions Analysis

This project analyzes California's power generation by type and associated CO₂ emissions using public CAISO data. It covers data loading, aggregation, and visualization for both energy generation and emissions.

## Project Structure

- `calEnergy.ipynb`: Main Jupyter notebook for data analysis and visualization.
- `caiso_gen_all_5min_*.csv`: Quarterly CAISO generation data files.
- `CAISO-historical-co2-20250530.csv`: Historical CO₂ emissions data.

## Data Sources

- **CAISO 5-Min Fuel Mix Generation (MW) 2020Q3-2025Q2**: https://www.eia.gov/electricity/wholesalemarkets/data.php?rto=caiso
- **CO2 Emissions Data**: https://www.caiso.com/todays-outlook/emissions#section-total-co2-trend


## How to Run

1. Open `calEnergy.ipynb` in Jupyter or VS Code.
2. Run each cell in order to:
   - Import libraries and set up file paths.
   - Load and combine all quarterly generation CSVs.
   - Aggregate and visualize quarterly and daily generation by type.
   - Load and process CO₂ emissions data.
   - Visualize annual, monthly, and quarterly CO₂ emissions.
   - Overlay generation and emissions data for comparison.

## Visualizations

- Bar charts of quarterly generation by type.
- Stacked bar charts for generation types.
- Line plots for daily, monthly, and quarterly CO₂ emissions.
- Dual-axis plots overlaying generation and emissions.

## Requirements

- Python 3.x
- pandas
- matplotlib
- numpy

Install dependencies with:

```sh
pip install pandas matplotlib numpy
```

## Team

- CSS 290 course

## Problem Statement

Analyze trends in California's renewable and non-renewable energy generation and their relationship to CO₂ emissions over time.

## How We Solved It

- Aggregated and visualized CAISO generation and emissions data.
- Compared trends across quarters and years.
- Provided clear plots to support analysis and presentation.

---
