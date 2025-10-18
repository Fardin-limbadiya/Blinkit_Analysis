# Blinkit Sales Analysis

A comprehensive analysis of Blinkit's sales data using Python, focusing on various business metrics and visualizations.

## Overview

This project analyzes sales data from Blinkit outlets to derive insights about:
- Total and average sales performance
- Product categories and their performance
- Outlet characteristics and their impact on sales
- Distribution of sales across different store parameters

## Key Metrics Analyzed

1. **Overall Performance Metrics**
   - Total Sales: $1,201,681.48
   - Average Sales: $140.99 per transaction
   - Number of Items Sold: 8,523
   - Average Product Rating: 3.97

2. **Product Analysis**
   - Sales distribution by fat content (Regular vs Low Fat)
   - Sales performance across different item types
   
3. **Outlet Analysis**
   - Sales by outlet establishment year
   - Sales distribution by outlet size
   - Performance across different location types
   - Impact of outlet tier on sales

## Visualizations

The analysis includes various visualizations:
- Pie charts for fat content and outlet size distribution
- Bar charts for item type sales
- Line plots for yearly trends
- Bar plots for location-based analysis

## Technologies Used

```python
- Python
- Pandas for data manipulation
- Matplotlib for basic visualizations
- Seaborn for statistical visualizations
```

## Key Findings

1. Sales distribution varies significantly across outlet locations and types
2. There's a clear pattern in sales based on outlet establishment years
3. Different item types show varying levels of sales performance
4. Outlet size has a notable impact on overall sales

## Usage

1. Install required libraries:
```python
pip install pandas numpy matplotlib seaborn
```

2. Load and run the Jupyter notebook:
```python
jupyter notebook blinkit_analysis.ipynb
```

## Data Source
The analysis uses the `blinkit_data.csv` file containing sales and outlet information.
