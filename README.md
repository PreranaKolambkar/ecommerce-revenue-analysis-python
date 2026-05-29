# E-commerce Revenue Analysis Using Python

## Project Overview

This project analyzes customer spending behavior for an e-commerce business using Python.

The goal of this project is to identify the factors that influence customer revenue and build a machine learning model to predict yearly customer spending.

---

## Project Objective

To understand customer behavior through data analysis and determine which factors contribute most to yearly spending.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Dataset Features

The dataset contains the following customer information:

- Avg Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent

---

## Project Workflow

### 1. Data Loading

- Loaded dataset using Pandas
- Viewed dataset structure and sample records

### 2. Data Cleaning

- Checked missing values
- Checked duplicate records
- Verified data quality

### 3. Exploratory Data Analysis (EDA)

Performed the following analyses:

- Revenue Distribution Analysis
- Session Length vs Revenue
- Time on App vs Revenue
- Time on Website vs Revenue
- Membership Length vs Revenue
- Correlation Heatmap

### 4. Machine Learning

Built a Linear Regression model to predict customer yearly spending.

Steps performed:

- Feature Selection
- Train-Test Split
- Model Training
- Prediction
- Model Evaluation

---

## Key Findings

- Length of Membership has the strongest relationship with yearly spending.
- Customers with longer memberships tend to spend more money.
- Time on App has a positive relationship with revenue.
- Average Session Length has a moderate impact on spending.
- Time on Website has very little effect on yearly spending.
- Customer loyalty appears to be the biggest driver of revenue.

---

## Model Performance

| Metric | Value |
|----------|----------|
| MAE | 8.56 |
| MSE | 109.86 |
| R² Score | 0.98 |

### Interpretation

- The model predicts customer spending with high accuracy.
- R² Score of 0.98 means the model explains about 98% of the variation in customer spending.
- Actual and predicted values are very close, indicating strong model performance.

---

## Feature Importance

| Feature | Importance |
|----------|----------|
| Length of Membership | 61.90 |
| Time on App | 38.79 |
| Avg Session Length | 25.60 |
| Time on Website | 0.31 |

### Observation

Length of Membership is the most important factor affecting customer spending, while Time on Website contributes very little.

---

## Conclusion

The analysis showed that customer loyalty plays the biggest role in determining yearly spending.

Customers who stay with the company for a longer period tend to generate higher revenue.

The Linear Regression model achieved excellent performance with an R² Score of 0.98, making it highly effective for predicting customer spending.

Businesses can focus on improving customer retention and app engagement to increase revenue.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Correlation Analysis
- Linear Regression
- Model Evaluation
- Business Analysis
- Python Programming
- Data-Driven Decision Making

---

## Repository Structure

```text
ecommerce-revenue-analysis-python/
│
├── Ecommerce_analysis.ipynb
├── Ecommerce_Customers.csv
└── README.md
```

---

## Author

**Prerana Kolambkar**

Aspiring Data Analyst skilled in SQL, Python, Data Analysis, Data Visualization, and Machine Learning.
