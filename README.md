# Customer Churn Prediction & Revenue Impact Modeling

This project builds an end-to-end machine learning pipeline to predict customer churn and estimate the business revenue at risk due to potential customer loss.

## Problem
Customer churn leads to significant revenue loss for subscription-based businesses. Identifying high-risk customers early allows companies to design targeted retention strategies.

## Solution
This project develops a churn prediction system using machine learning models and extends it with explainable AI and revenue impact modeling.

## Key Features
- Customer churn prediction using multiple ML models (Logistic Regression, Random Forest, XGBoost, LightGBM)
- Feature engineering for engagement and revenue behavior
- Hyperparameter tuning and model evaluation using ROC-AUC
- Model explainability using SHAP
- Risk segmentation of customers (Low / Medium / High)
- Revenue at risk estimation
- Retention campaign simulation with discount cost and net gain analysis

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- LightGBM
- SHAP
- Matplotlib

## Results
- Best Model: XgBoost
- ROC-AUC Score: ~0.75
- Estimated Revenue at Risk: ~$764K
- Potential Net Gain from Retention Campaign: ~$206K

## Future Improvements
- LLM-based AI retention strategy generator
- Streamlit dashboard for interactive business insights
