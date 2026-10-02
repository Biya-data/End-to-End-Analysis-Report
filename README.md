# Telecom Customer Churn Analysis

## Project Overview

This project analyzes customer churn in a telecommunications dataset to identify factors associated with customers leaving the service.

The analysis includes data inspection, data cleaning, exploratory data analysis (EDA), data visualization, key insights, conclusion, and recommendations.

## Objectives

- Understand the overall customer churn rate.
- Explore factors associated with customer churn.
- Analyze the relationship between customer service calls and churn.
- Compare churn rates for customers with and without an International Plan.
- Analyze the relationship between Voice Mail Plan and churn.
- Compare average usage and charges between churned and non-churned customers.
- Generate insights and recommendations based on the analysis.

## Dataset

The project uses a telecommunications customer churn dataset containing customer information, service details, usage information, charges, and churn status.

The target variable is:

- **Churn** – indicates whether a customer has left the service.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Data Cleaning

The dataset was checked and prepared before performing the analysis.

The cleaning process included:

- Checking missing values
- Checking duplicate records
- Checking text/categorical columns
- Checking numeric columns
- Checking data types
- Saving the cleaned dataset as `cleaned_customer_data.csv`

## Exploratory Data Analysis

The following areas were analyzed:

- Customer Churn Distribution
- International Plan vs Churn
- Customer Service Calls vs Churn
- Voice Mail Plan vs Churn
- Average Total Day Minutes by Churn Status
- Average Total Day Charge by Churn Status

## Key Insights

- The overall customer churn rate is approximately **14.55%**.
- Customers with an International Plan have a higher churn rate (**43.70%**) compared with customers without an International Plan (**11.27%**).
- Higher numbers of Customer Service Calls are associated with higher churn rates.
- Customers with 8 or 9 Customer Service Calls showed a 100% churn rate in this dataset, although these groups may contain fewer customers.
- Churned customers had a higher average Total Day Charge (**34.88**) compared with non-churned customers (**29.77**).
- International Plan usage, frequent Customer Service Calls, and higher day charges were associated with customer churn in the analysis.

## Conclusion

The analysis shows that customer churn is influenced by several factors. Customers with an International Plan have a higher churn rate than customers without one. Frequent Customer Service Calls are also associated with higher churn. Churned customers also have a higher average Total Day Charge than non-churned customers.

## Recommendations

- Monitor customers who use the International Plan, as this group shows a higher churn rate.
- Provide better support and follow-up for customers who make frequent Customer Service Calls.
- Investigate the reasons for higher charges among customers who churn.
- Use customer churn patterns to identify customers who may need additional support or retention efforts.

## Project Files

- `Project4_Analysis(2).ipynb` – Complete analysis notebook
- `telecom-churn.csv` – Original dataset
- `cleaned_customer_data.csv` – Cleaned dataset
- `README.md` – Project documentation

## Author

**Rabiya Shaheen**

BS Information Technology
