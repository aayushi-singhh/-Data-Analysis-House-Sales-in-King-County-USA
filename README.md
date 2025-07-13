# -Data-Analysis-House-Sales-in-King-County-USA
This project simulates the role of a Data Scientist at a Real Estate Investment Trust (REIT). Using real-world housing data from King County, Washington (USA), the goal was to analyze and predict house prices using Python and machine learning tools.
# 🏠 House Sales in King County, USA

## Overview
This project analyzes housing data from King County, Washington, to identify key drivers of house prices and build predictive models. The notebook simulates the role of a Data Scientist at a Real Estate Investment Trust (REIT), tasked with extracting insights and building price prediction tools.

## Dataset
The dataset includes over 21,000 house sales with features like:
- Square footage
- Number of bedrooms and bathrooms
- Waterfront view
- Geographic location (latitude & longitude)
- Grade, condition, and more

Source: Provided in Coursera’s IBM Data Analysis with Python course.

## Key Steps
- **Data Wrangling:** Cleaned columns, dropped nulls, and converted types
- **EDA:** Visualized price relationships and feature distributions
- **Modeling:**
  - Linear Regression
  - Ridge Regression
  - Polynomial Regression
  - Pipelines with Scalers & Transformers
- **Evaluation:** Used R² to evaluate models and compare performance

## Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## Results
- Discovered that `sqft_living`, `grade`, and `waterfront` had the strongest positive correlation with price
- Improved model performance using polynomial features and regularization

## Author
- IBM Data Science Professional Certificate, Final Project — Aayushi Singh
