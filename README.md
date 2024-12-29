# Dominos - Predictive Purchase Order System

## Project Overview
Dominos aims to optimize the ordering process for ingredients by predicting future sales and generating an efficient purchase order. By accurately forecasting sales, Dominos can ensure the right stock levels, reduce waste, and prevent stockouts. This project utilizes historical sales and ingredient data to build a predictive model for sales forecasting and automate purchase order generation.

## Skills Learned
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Time series forecasting
- Predictive modeling
- Business decision-making
- Real-world application of data science

## Domain
Food Service Industry

## Problem Statement
Dominos seeks to improve its inventory and ordering system by predicting ingredient demand based on historical sales data. This project will create a predictive model to forecast sales and generate purchase orders for the right quantities of ingredients.

## Business Use Cases
- **Inventory Management**: Ensuring optimal stock levels to meet future demand without overstocking.
- **Cost Reduction**: Minimizing waste and reducing costs associated with expired or excess inventory.
- **Sales Forecasting**: Accurately predicting sales trends to inform business strategies and promotions.
- **Supply Chain Optimization**: Streamlining the ordering process to align with predicted sales and avoid disruptions.

## Approach

### Data Preprocessing and Exploration
1. **Data Cleaning**: Handling missing or inconsistent data entries, outliers, and ensuring proper data formatting.
2. **Exploratory Data Analysis (EDA)**: Analyzing sales trends, seasonality, and patterns in the historical data. Visualizing the data to identify key features influencing sales.

### Sales Prediction
1. **Feature Engineering**: Creating relevant features like day of the week, month, promotional periods, and holiday effects.
2. **Model Selection**: Choosing a time series forecasting model (e.g., ARIMA, SARIMA, Prophet, LSTM, Regression).
3. **Model Training**: Training the predictive model on historical sales data.
4. **Model Evaluation**: Evaluating model performance using Mean Absolute Percentage Error (MAPE).

### Purchase Order Generation
1. **Sales Forecasting**: Predicting pizza sales for a future period (e.g., one week).
2. **Ingredient Calculation**: Calculating the required quantities of each ingredient based on predicted sales.
3. **Purchase Order Creation**: Generating a detailed purchase order listing required ingredients for the forecasted period.

## Results
- Accurate sales predictions for the forecasted period.
- A comprehensive purchase order listing the required ingredients to meet the predicted sales.

## Technical Tags
- Data Cleaning
- EDA
- Time Series Forecasting
- ARIMA/SARIMA/Prophet/LSTM/Regression Model
- Predictive Modeling
- Inventory Management
- Python
- Pandas
- Scikit-learn
- Matplotlib/Seaborn

## Datasets

### Sales Dataset
Contains historical sales data including:
- Date
- Pizza Type
- Quantity Sold
- Price
- Category
- Ingredients Used

### Ingredients Dataset
Lists ingredient requirements for each pizza type, including:
- Pizza Type
- Ingredient
- Quantity Needed

## Project Deliverables & Evaluation Metrics
- Cleaned and preprocessed datasets
- EDA report with insights
- Predictive model with code and evaluation metrics
- Detailed purchase order for the forecasted period
- GitHub repository with code and documentation
- Project report documenting methodology, findings, and business implications

## Project Guidelines
- Follow best coding practices with clear and consistent naming conventions.
- Use version control (Git) for managing code changes and collaboration.
- Document all steps clearly in the code and the project report.
- Ensure reproducibility by using consistent computing environments and dependencies.

