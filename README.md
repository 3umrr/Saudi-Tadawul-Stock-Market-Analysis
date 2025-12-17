Saudi Tadawul Stock Market Analysis
This project analyzes historical Saudi Tadawul (TASI) stock market data and builds simple predictive models for a selected company. The workflow covers data extraction, cleaning, exploratory analysis, and regression modeling.

Project Goals
Clean and preprocess multi‑year Tadawul data from MongoDB.

Explore trading behavior across companies and sectors with visualizations.

Build linear regression models to predict:

Daily close price.

Daily value traded.

Test the models on recent data scraped from Yahoo Finance and combined with an Excel file.

Main Steps
Load raw data from MongoDB into pandas.

Remove duplicates, handle missing values and zeros, and treat outliers.

Engineer features such as average price and year.

Generate plots (correlation heatmap, sector distributions, yearly trends, top companies).

Select the company with the largest history (symbol 3020) and train regression models.

Scrape recent OHLCV data for 3020.SR, merge it with trade statistics from Excel, and evaluate model performance on this new period.
