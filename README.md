# Retail Sales Analysis — Online Retail II

## Overview
A comprehensive analysis of over 1 million retail transactions from a UK-based online retailer covering December 2009 to December 2011. 
This project explores product performance, seasonal trends, customer markets and operational patterns to uncover actionable business insights.

## Key Findings
- **UK dominates revenue** accounting for the majority of total sales, with Ireland and Netherlands completing the top 3 markets
- **Revenue peaks in November** each year driven by early Christmas and Black Friday purchasing, with a sharp December decline suggesting customer concerns around delivery lead times
- **Regency Cakestand 3 Tier** leads both revenue (£314,045) and units sold — the same top 10 products appear in both revenue and quantity rankings
- **Core trading window is 10:00-16:00** with a lunch hour peak at 12:00, consistent with a wholesale B2B customer base
- **19,104 cancellations** recorded with two products showing abnormally high cancellation volumes requiring urgent investigation
- **Overall Average Order Value is £382.05** with Netherlands, Australia and Thailand representing high AOV growth opportunities

## Technologies Used
- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset
- **Name:** Online Retail II UCI
- **Source:** [Kaggle](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
- **Instructions:** Download the CSV file from Kaggle and save it as 
  `online_retail_II.csv` in the same folder as the notebook

## How to Run
1. Clone this repository
2. Download the dataset from the Kaggle link above
3. Save the CSV file as `online_retail_II.csv` in the project folder
4. Open `retail_sales_analysis.ipynb` in Jupyter Notebook
5. Run all cells from top to bottom

## Project Structure
retail-sales-analysis/
│
├── retail_sales_analysis.ipynb    # Main analysis notebook
└── README.md                      # Project documentation

## Analysis Sections
1. Data Loading & Exploration
2. Data Cleaning
3. Revenue by Country
4. Revenue by Month
5. Top 10 Products by Revenue
6. Revenue by Day of Week
7. Revenue by Hour of Day
8. Top 10 Products by Quantity
9. Cancellation Analysis
10. Average Order Value by Country
11. Month over Month Growth Rate
12. International Markets (Excluding UK)
13. Worst Performing Products

## Author
Jordan Nel — Aspiring Data Analyst  
www.linkedin.com/in/jordan-nel-4399a61b9 
https://github.com/hjnel3-droid
