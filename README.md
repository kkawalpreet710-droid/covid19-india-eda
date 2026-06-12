# COVID-19 India — Exploratory Data Analysis

## About
Exploratory data analysis on India's statewise COVID-19 dataset 
(Jan 2020 – Aug 2021) using Python, Pandas and Matplotlib.

## Dataset
Source: Kaggle — covid19-in-india by sudalairajkumar  
Rows: 18,110 | Columns: 9

## What I did
- Loaded and explored the raw dataset
- Cleaned dirty values (dash characters in numeric columns)
- Fixed inconsistent state names (Karanataka → Karnataka)
- Converted date column from object to datetime
- Handled cumulative data correctly for accurate totals

## Key findings
- Maharashtra had the highest confirmed cases (~6.3 million)
- Kerala ranked 2nd despite being a smaller state — strong reporting
- India's recovery rate: ~98%
- Total deaths: ~621,910
- Delta wave (April–May 2021) visible as a near-vertical spike in the time series

## Tools
Python · Pandas · Matplotlib · Google Colab

## Charts
- Top 10 states by confirmed cases (bar chart)
- COVID-19 cases over time — India (line chart)
