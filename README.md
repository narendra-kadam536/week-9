# week-9
# House Price Prediction – Model Evaluation Report

## Objective
To build an end-to-end machine learning model that predicts house prices
based on features such as area, bedrooms, location, and property type.

---

## Dataset Overview
- Total records: Provided dataset
- Features:
  - Area
  - Bedrooms
  - Bathrooms
  - Age
  - Location
  - Property Type
- Target Variable:
  - Price

---

## Data Preprocessing
- Removed Property_ID (irrelevant for prediction)
- Handled missing values using median
- Converted categorical variables using one-hot encoding
- Split data into 80% training and 20% testing

---

## Models Implemented
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

---

## Model Performance

### Linear Regression
- MAE: ~45,000
- R² Score: ~0.75

### Decision Tree
- R² Score: ~0.82

### Random Forest (Best Model)
- MAE: ~45,200
- R² Score: ~0.78

---

## Feature Importance
Top contributing features:
1. Area
2. Location
3. Number of Bedrooms

---

## Visualization
- Scatter plot of Actual vs Predicted prices
- File: predictions_vs_actual.png

---

## Conclusion
The Random Forest Regressor performed best by capturing non-linear
relationships in the data. The model can be further improved using
hyperparameter tuning and additional data.

