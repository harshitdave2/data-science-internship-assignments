# Week 2 Assignment - End-to-End Machine Learning Pipeline on Tesla Sales & Production Data

## Overview

This project was completed as part of the Week 2 assignment for the Data Science Internship Program.

The objective was to build a complete end-to-end Machine Learning pipeline using Tesla deliveries and production data. The project covers the entire Data Science workflow, from data preprocessing and exploratory analysis to model building, hyperparameter tuning, feature engineering, and time series forecasting.

---

## Dataset

**Dataset:** Tesla Deliveries and Production Data (2015–2025)

The dataset contains information related to:

- Tesla vehicle deliveries
- Production units
- Vehicle models
- Regions
- Average vehicle prices
- Battery capacity
- Vehicle range
- CO₂ savings
- Charging infrastructure

---

## Project Workflow

### 1. Data Loading & Exploration
- Loaded dataset using Pandas
- Examined dataset structure and statistics
- Identified data types and missing values

### 2. Data Cleaning
- Removed duplicate records
- Handled missing values
- Performed data quality checks

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis
- Region-wise delivery analysis
- Model-wise delivery analysis
- Correlation heatmap
- Trend visualizations

### 4. Feature Engineering
Created new business-oriented features such as:

- Delivery Efficiency
- Price per Kilometer
- Stations per Delivery
- Date-based features

### 5. Machine Learning Pipeline
Implemented a complete Scikit-Learn pipeline including:

- OneHot Encoding
- ColumnTransformer
- Random Forest Regressor

### 6. Model Evaluation
Evaluated model performance using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 7. Hyperparameter Tuning
Optimized model performance using:

- GridSearchCV

### 8. Feature Importance Analysis
Analyzed the most influential factors affecting vehicle deliveries.

### 9. Time Series Forecasting
Performed delivery forecasting using:

- Moving Averages
- ARIMA Model
- Forecast Visualization

---

## Results

### Random Forest Regression Performance

| Metric | Value |
|----------|----------|
| MAE | 79.46 |
| RMSE | 122.84 |
| R² Score | 0.9990 |

The model achieved excellent predictive performance, explaining approximately 99.9% of the variance in delivery data.

---

## Key Insights

- Production Units were the strongest predictor of Tesla deliveries.
- Delivery volume showed strong correlation with manufacturing output.
- Charging infrastructure and vehicle specifications contributed to demand patterns.
- Feature engineering improved model performance and interpretability.
- Time series forecasting successfully captured future delivery trends.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Statsmodels

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Pipelines
- Hyperparameter Tuning
- Model Evaluation
- Time Series Forecasting
- End-to-End Data Science Workflow

---

## Author

**Harshit Dave**

Data Science Internship Program - Week 2 Assignment
