# Diwali Sales EDA
EDA on Diwali sales data to identify high-value customer segments by age, gender, marital status, and location

# Diwali Sales — Customer Segmentation Analysis

Business Problem

A retail company wanted to identify the customer segments, regions, occupations, and product categories generating the highest revenue during the Diwali season. The objective was to improve customer targeting and allocate marketing budgets more effectively for future festive campaigns.

Dataset
Source: Kaggle Diwali Sales Dataset
Original Records: 11,251 transactions
Features: 15 columns
Key fields:
Gender
Age Group
Marital Status
State
Occupation
Product Category
Orders
Amount
Data Cleaning
Removed unnecessary columns: Status and unnamed1
Identified 12 missing values in the Amount column
Removed rows containing missing values
Final dataset size: 11,239 records and 13 columns
Approach
Performed exploratory data analysis (EDA) using Pandas
Analyzed customer purchasing behavior by:
Gender
Age Group
Marital Status
State
Occupation
Product Category
Created visualizations using Matplotlib and Seaborn
Evaluated revenue contribution and order volume across customer segments
Key Findings
Female customers generated ₹74.34 million in revenue, compared to ₹31.91 million from male customers, contributing approximately 70% of total sales revenue.
Customers aged 26–35 years were the highest-spending segment, generating ₹42.61 million in sales revenue.
Customers aged 36–45 years generated ₹22.14 million in revenue, making them the second most valuable customer group.
Married female customers contributed significantly more revenue than other marital-status segments.
The highest revenue-generating age groups were 26–35, 36–45, and 18–25, indicating strong purchasing activity among young and middle-aged consumers.
State-wise analysis revealed that a small group of states accounted for the majority of orders and revenue, with Uttar Pradesh, Maharashtra, and Karnataka appearing among the top contributors.
Occupation analysis showed strong spending patterns among customers working in IT, Healthcare, and Aviation sectors.
Product category analysis indicated that Food, Clothing & Apparel, and Electronics were among the highest-performing categories during the festive season.
Business Recommendations
Prioritize marketing campaigns targeting women aged 26–35 years.
Allocate larger advertising budgets to top-performing states.
Create occupation-focused promotional campaigns for IT and Healthcare professionals.
Increase inventory planning for high-performing product categories before festive periods.
Develop personalized offers for repeat customer segments with historically high spending behavior.

## Tools Used
Python | Pandas | NumPy | Matplotlib | Seaborn | Jupyter Notebook

## Files in This Repo
- `Diwali_Sales.ipynb` — main analysis notebook
- `[dataset filename]` — source data (or link to Kaggle if not redistributable)
