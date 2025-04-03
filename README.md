# Insurance Claims Analysis and Prediction

This project involves analyzing an insurance dataset to understand customer behavior, evaluate key performance indicators (KPIs), and build a predictive model for estimating insurance claims.

## Dataset Overview
The dataset includes information about customers, their insurance policies, and claims filed. Key columns include:
- **Customer_ID**: Unique identifier for each customer.
- **Customer_Age**, **Gender**, **Risk_Level**: Demographic and risk-related information.
- **Policy_Type**, **Monthly_Premium**, **Coverage_Amount**: Details about the insurance policy.
- **Claims_Filed**, **Total_Claims**: Information on claims filed by the customer.
- **Retention_Rate**, **Revenue_Per_Customer**: KPIs related to customer retention and company revenue.

## Key Steps

### 1. **Data Loading and Exploration**
- The dataset is loaded using pandas and inspected for the first few rows.

### 2. **Data Cleaning and Feature Engineering**
- Missing values are filled with the median, unnecessary columns are dropped, and new features like **Premium_to_Claim_Ratio** are created.

### 3. **Exploratory Data Analysis (EDA)**
- Visualizations are used to analyze customer age distribution, claim amounts, and other trends.
- Correlation analysis helps identify relationships between variables.

### 4. **Key Performance Indicators (KPIs)**
- Key metrics like **Average Monthly Premium** and **Claims Frequency** are calculated to understand overall trends.

### 5. **Segmentation and Insights**
- Claims are analyzed based on customer demographics (e.g., age and risk level) to understand how different groups file claims.

### 6. **Predictive Modeling**
- A Linear Regression model is used to predict total claims based on customer data. The model is trained and evaluated using Mean Squared Error (MSE).

## Conclusion
This project provides insights into customer behavior and a model for predicting insurance claims. Future work can include experimenting with more complex models, hyperparameter tuning, and deployment for real-time prediction.

## Future Steps
- Experiment with advanced machine learning algorithms.
- Optimize model performance through hyperparameter tuning.
- Explore advanced feature engineering techniques for better predictions.
