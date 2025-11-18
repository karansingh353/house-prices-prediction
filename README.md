# House Price Prediction Project

## Project Overview
This project analyzes the Ames Housing dataset to predict final sale prices. 
Using an "Engineer's Approach," I focused on statistical feature engineering rather than model complexity.

## Key Techniques Used
* **Statistical Analysis:** Identified Log-Normal distribution in target variable.
* **Feature Engineering:** One-Hot Encoding with multicollinearity handling.
* **Regularization:** Implemented Lasso Regression (L1) to perform automatic feature selection.
* **Hyperparameter Tuning:** Used Cross-Validation (LassoCV) to optimize model penalty.

## Results
* **Baseline R2:** 0.49 (Simple Linear Regression)
* **Final Test R2:** 0.85 (Tuned Lasso)
* **Kaggle Score (RMSLE):** 0.174 (Top tier for linear models)
