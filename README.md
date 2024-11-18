# Car-Prediction-Using-Machine-Learning
Project Overview
This project builds a machine learning model to predict used car prices based on 402,005 entries with 12 features, including specifications, mileage, and registration year. Data preprocessing, feature engineering, and advanced model selection achieved an R² of 0.8741 with a Voting Regressor, delivering accurate and actionable price predictions.

# Key Features of the Project
# Data Preprocessing:
Handled missing values (mode for categorical, median for numerical).
Removed outliers and normalized numerical features.
# Feature Engineering:
Created new features like Car Age and Average Mileage Per Year.
Applied Target Encoding for categorical data.
# Dimensionality Reduction:
Used PCA to reduce features to 4 principal components (95% variance retained).
# Model Building:
Models tested: Linear Regression, Random Forest, XGBoost.
Final Model: Voting Regressor combining Random Forest and XGBoost.
# Model Performance:
Voting Regressor:
R²: 0.8741
RMSE: 2015.00
# Results
Best Model: Voting Regressor (Random Forest + XGBoost) with an RMSE of 2015.00.
# Key Insights:
Car Age: Major factor in price depreciation.
Model Standard: Strongly correlated with higher prices.
# Visualizations:
Scatter plot of actual vs. predicted prices.
SHAP analysis for feature importance.
# Technologies Used
Languages: Python
Libraries: sci-kit-learn, XGBoost, SHAP, pandas, matplotlib, seaborn
Tools: Jupyter Notebook

