# eCommerce Transactions Dataset Analysis

This repository contains a comprehensive analysis of an eCommerce Transactions dataset. The project involves Exploratory Data Analysis (EDA), building a Lookalike Model, and performing Customer Segmentation using Clustering techniques. The primary goal is to extract business insights, recommend similar customers, and perform clustering for customer segmentation based on transaction and customer profile data.

## Project Overview

### Dataset Files

- **Customers.csv**: Contains customer information such as ID, name, region, and signup date.
- **Products.csv**: Contains product details including product ID, name, category, and price.
- **Transactions.csv**: Contains transaction details including transaction ID, customer ID, product ID, transaction date, quantity, total value, and price.

### Tasks

1. **Exploratory Data Analysis (EDA) and Business Insights**  
   - Performing exploratory data analysis on the dataset to identify trends and patterns.
   - Deriving at actionable business insights based on the EDA.

2. **Lookalike Model**  
   - Building a Lookalike Model that recommends the top 3 similar customers based on customer profile and transaction history.
   - Providing a similarity score for each recommendation.

3. **Customer Segmentation / Clustering**  
   - Using clustering techniques to segment customers based on both their profile and transaction data.
   - Visualizing the clusters and calculate clustering metrics, including the DB Index.

## Installation and Requirements

To run the code in this repository, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
- datetime

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
