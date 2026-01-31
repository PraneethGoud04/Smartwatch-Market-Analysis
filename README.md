# Smartwatch-Market-Analysis
End-to-end web scraping and exploratory data analysis of Amazon smartwatches
# Smartwatch Web Scraping & EDA Project

## Project Overview
This project performs end-to-end web scraping and exploratory data analysis (EDA) on smartwatch data collected from Amazon.  
The goal is to understand pricing patterns and identify key features that influence smartwatch prices.

## Business Problem
Smartwatch prices vary significantly across brands and features.  
This project aims to determine whether pricing is driven by technical specifications or brand positioning.

## Data Collection
- Source: Amazon (Web Scraped)
- Tools: Selenium, BeautifulSoup
- Records: ~500 smartwatches
- Duplicate removal using ASIN

## Features Analyzed
- Brand
- Price (Target Variable)
- Bluetooth Calling
- Battery Life (Days)
- Battery Capacity (mAh)
- Review Count
- Display Type
- Operating System

## Key Analysis Performed
- Univariate Analysis (Price, Brand distribution)
- Bivariate Analysis (Price vs Features)
- Correlation Analysis
- Hypothesis Testing (Mann–Whitney U, Spearman Correlation)

## Key Insights
- Brand positioning is the strongest pricing driver
- Higher price does not guarantee better battery life
- Bluetooth calling is not a premium feature
- Review count reflects popularity, not value

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Selenium, BeautifulSoup
- SciPy

## Project Structure
- notebooks/: Web scraping, feature extraction, and EDA notebooks
- data/: Raw and cleaned datasets
- presentation/: Final PPT used for analysis presentation

## Conclusion
Mid-range smartwatches offer the best value for money.  
Premium pricing is driven more by brand perception than technical advantages.
