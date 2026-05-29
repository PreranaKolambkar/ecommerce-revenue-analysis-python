# E-commerce Revenue Analysis Using Python

## Project Overview
This project analyzes customer behavior and spending patterns for an e-commerce business using Python.

The objective is to identify the factors that influence customer revenue and build a machine learning model to predict yearly customer spending.

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset Features
- Avg Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent

## Project Workflow

### 1. Data Loading
- Imported dataset using Pandas
- Checked dataset structure

### 2. Data Cleaning
- Checked missing values
- Checked duplicate records
- Verified data quality

### 3. Exploratory Data Analysis (EDA)
Performed:
- Revenue Distribution Analysis
- Session Length vs Revenue
- Time on App vs Revenue
- Time on Website vs Revenue
- Membership Length vs Revenue
- Correlation Heatmap

### 4. Key Findings
- Length of Membership showed the strongest relationship with revenue.
- Time on App had a moderate positive relationship with revenue.
- Average Session Length had a moderate impact on spending.
- Time on Website showed little influence on revenue.

### 5. Machine Learning
Built a Linear Regression model to predict customer yearly spending.

### Model Performance
- MAE: 8.56
- MSE: 109.86
- R² Score: 0.98

## Conclusion
Customer loyalty (Length of Membership) is the most important factor influencing revenue. The Linear Regression model achieved excellent performance and can accurately predict customer spending behavior.

## Repository Structure

ecommerce-revenue-analysis-python/
│
├── Ecommerce_analysis.ipynb
├── Ecommerce_Customers.csv
└── README.md
