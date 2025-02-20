# Dominos---Predictive-Purchase-Order-System_Project


# Overview

This project optimizes Dominos’ ingredient ordering process by predicting future sales and generating efficient purchase orders. By leveraging historical sales data, the system minimizes waste, prevents stockouts, and improves inventory management.

# Business Use Cases:
1) Inventory Management: Ensuring optimal stock levels to meet future demand without overstocking.
2) Cost Reduction: Minimizing waste and reducing costs associated with expired or excess inventory.
3) Sales Forecasting: Accurately predicting sales trends to inform business strategies and promotions.
4) Supply Chain Optimization: Streamlining the ordering process to align with predicted sales and avoid disruptions.

# Approach:
1) Data Preprocessing and Exploration
- Data Cleaning: Remove any missing or inconsistent data entries, handle outliers, and format the data appropriately.
- Exploratory Data Analysis (EDA): Analyze sales trends, seasonality, and patterns in the historical sales data. Visualize the data to 
identify significant features.
2) Sales Prediction
- Feature Engineering: Create relevant features from the sales data, such as day of the week, month, promotional periods, and holiday effects.
- Model Selection: Choose an appropriate time series forecasting model (e.g., ARIMA, SARIMA, Prophet,Regression Model).
- Model Training: Train the predictive model on the historical sales data.
- Model Evaluation: Use metric Mean Absolute Percentage Error (MAPE) to evaluate model performance.
3) Purchase Order Generation
- Sales Forecasting: Predict pizza sales for the next one week (your choice of months or weeks) using the trained model.
- Ingredient Calculation: Calculate the required quantities of each ingredient based on the predicted sales and the ingredient dataset.
- Purchase Order Creation: Generate a detailed purchase order listing the quantities of each ingredient needed for the predicted sales period.

# Technical Tags:
- Data Cleaning
- EDA
- Time Series Forecasting
- ARIMA/SARIMA/Prophet/Regression Model
- Predictive Modeling
- Inventory Management
- Python
- Pandas
- Scikit-learn
- Matplotlib/Seaborn

