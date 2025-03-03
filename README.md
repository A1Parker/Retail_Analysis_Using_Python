# Retail_Analysis_Using_Python

## Retail Case Study Analysis


### Overview


This project focuses on retail analytics, where data from customers, transactions, and product hierarchy are analyzed to derive key business insights. Using data-driven methodologies, we explore customer behavior, sales trends, and product category performance to enhance business decision-making.


### Business Context


With increasing competition in the retail market, optimizing service business processes and managing data efficiently is crucial for customer satisfaction and profitability. Retailers leverage customer intelligence by analyzing transactional and behavioral data to generate actionable insights.


### Objective


A retail store wants to analyze day-to-day transactions and track its customers' purchases/returns across various locations and product categories. The goal is to generate reports, calculate metrics, and derive insights from the available data.


### Dataset Details


The data is available in Retail Data.xlsx, which consists of three sheets:

- Customer: Contains customer demographics.

  Transaction: Includes transaction details.

  Product Hierarchy: Holds product-related information (category, subcategory, etc.).

- Data Preparation & Cleaning

  Merged Customers, Product Hierarchy, and Transactions datasets into Customer_Final.

  Ensured all customers with transactions were included using an appropriate join type.

  Checked for missing values, data types, and anomalies.

### Key Analysis & Insights

- 1. Data Summary & Descriptive Analysis

  Extracted column names and their corresponding data types.

  Identified top and bottom 10 observations in the dataset.

  Performed a Five-number summary for continuous variables (min, Q1, median, Q3, max).

  Created frequency tables for categorical variables.

- 2. Visualizations & Distribution Analysis

  Generated histograms for all continuous variables.

  Created bar plots for categorical variables to understand distribution trends.

- 3. Key Business Metrics

  Time Period Analysis: Identified the time range covered by the transaction data.

  Negative Transactions: Counted instances where the total transaction amount was negative.
  

### Customer Demographics:


- Analyzed product preferences by gender (female vs male customers).

- Determined the city with the maximum customers and its percentage share.


### Store Performance:


- Identified which store type sells the maximum products by value and quantity.

- Calculated total revenue from Electronics & Clothing in Flagship Stores.

- Derived total earnings from male customers in the Electronics category.

### Customer Loyalty & Transactions:

Counted customers with more than 10 unique transactions (excluding negative amounts).

- Customer Spending Analysis (Aged 25-35):

  Total spend on Electronics & Books.

  Spend between January 1, 2014 - March 1, 2014.


### Technologies Used


Python (Pandas, NumPy, Matplotlib, Seaborn) for data processing & visualization.

Jupyter Notebook for interactive analysis.

### Files in Repository

Retail Case Study Analysis.ipynb - Jupyter Notebook with full analysis.

Retail Data.xlsx - Raw dataset used for analysis.

README.md - Project documentation (this file).
