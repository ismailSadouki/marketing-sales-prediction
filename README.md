# Marketing Sales Prediction Using Multiple Linear Regression

## Project Overview
This project involves building a multiple linear regression model to predict sales based on marketing promotion data from a small business. The model uses TV, radio, and influencer marketing as independent variables to estimate sales. The results provide valuable insights into the effectiveness of marketing channels and their impact on sales.

## Business Understanding
The objective is to help a small business optimize their marketing budget by understanding how different promotional efforts—specifically TV, radio, and influencer campaigns—affect sales. The model will guide future investments by highlighting the most effective channels.

## Data Understanding
The dataset includes the following key features:
- **TV**: Promotional budget categorized into "Low," "Medium," and "High."
- **Radio**: Promotional budget in millions of dollars.
- **Influencer**: Influencer size categorized into "Mega," "Macro," "Micro," and "Nano."
- **Sales**: Sales in millions of dollars (target variable).

The dataset was cleaned to handle missing values, renamed columns for model compatibility, and explored using pairplots to identify relationships between variables.

## Modeling and Evaluation
- **Model Used**: Ordinary Least Squares (OLS) Multiple Linear Regression.
- **Features Selected**: TV and Radio budgets (excluding Social Media and Influencer due to lack of impact).
- **Model Performance**: 
  - R-squared: 0.904
  - The model explains 90.4% of the variation in sales.

### Evaluation Metrics:
- Coefficients:
  - TV (Low): -154.30
  - TV (Medium): -75.31
  - Radio: 2.97
- Interpretation: Switching from a high to a low TV promotional budget results in a $154.3 million decrease in sales. Every $1 million increase in the radio budget increases sales by $2.97 million.

## Conclusion
The model reveals that TV and radio budgets significantly influence sales. High TV promotional budgets have the largest impact, while radio also contributes positively. The recommendation is to prioritize higher TV budgets and increase radio spending for optimal sales performance.

