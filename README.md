# Baby Name Trend Analysis & Popularity Predictor

## Overview
This project explores historical baby name data from the United States to analyze long-term naming trends and regional patterns. It also includes a desktop application that predicts the future popularity of a given baby name using regression models.

## Dataset
- **NationalNames.csv** – National-level baby name data by year and gender  
- **StateNames.csv** – State-level baby name data by year and gender  

## Project Features
- Data cleaning and validation (null and duplicate checks)
- Filtering baby names by year, gender, and region
- Popularity trend analysis using time-series data
- Top baby names by decade and overall popularity
- Rising and falling name analysis across time periods
- Regional comparison of name popularity (state-level)
- Name lifespan and volatility analysis
- Gender distribution analysis for unisex names
- Detection of comeback names using polynomial trends

## Machine Learning Models
- **Linear Regression** to predict future name popularity
- **Logistic Regression** with MinMax scaling to estimate popularity trends

## Desktop Application
- Built using **Tkinter**
- User inputs baby name and gender
- Displays historical popularity trends
- Predicts popularity for upcoming years
- Embedded Matplotlib charts for visualization

## Visualizations
- Name popularity over time
- Regression trend lines
- Top names per decade
- State-wise comparison plots
- Gender distribution pie charts
- Bar charts of most popular baby names

## Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib  
- Scikit-learn  
- Tkinter  


