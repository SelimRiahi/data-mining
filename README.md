# Customer Segmentation Analysis

This project analyzes customer purchase behavior using the Online Retail dataset from UCI. The goal is to segment customers based on their buying patterns to better understand different customer groups.

## What's in here

- **Data cleaning**: removing missing values, filtering out invalid transactions
- **RFM Analysis**: calculating Recency, Frequency, and Monetary value for each customer
- **Clustering**: using K-means to group customers into segments
- **Association Rules**: finding which products are frequently bought together
- **Visualization**: charts showing customer segments and their characteristics

## Dataset

The data comes from a UK-based online retailer and covers transactions from 2010-2011. It includes invoice details, product descriptions, quantities, prices, and customer info.

## Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
mlxtend
openpyxl
```

## Quick start

Just open the notebook and run the cells in order. The dataset will be downloaded automatically and the analysis will walk through each step.
