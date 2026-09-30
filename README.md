# online-retail-eda
Data extraction, cleaning and EDA on the UCI Online Retail dataset using Python



# Online Retail: Data Cleaning and EDA

## About
Week 2 task: data extraction, cleaning and exploratory analysis of the
UCI Online Retail dataset (541,909 transactions, Dec 2010 - Dec 2011).

## Dataset
UCI Machine Learning Repository - Online Retail
https://archive.ics.uci.edu/dataset/352/online+retail

## What was done
- Extracted data using Pandas
- Removed cancelled invoices, negative quantities, duplicates, invalid prices
- Handled missing Description and CustomerID
- Detected outliers with the IQR method and normalized values (Min-Max)
- EDA: histograms, boxplot, scatter plot, correlation matrix, trend charts

## How to run
1. pip install -r requirements.txt
2. Put the dataset in the data folder
3. Open notebook/Online_Retail_EDA.ipynb and run all cells

## Key findings
- UK generates most of the revenue
- Sales peak in the last quarter of the year
- Bulk buying happens on low-priced items
