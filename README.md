LTV Prediction Project
Overview
Predict customer churn and calculate Lifetime Value (LTV) using machine learning to optimize retention strategies.

Models & Performance
XGBoost: 80.6% accuracy (Best)

Logistic Regression: 79.8% accuracy

Random Forest: 78.0% accuracy

Key Results
Top Features: TotalCharges (31%), MonthlyCharges (31%), Tenure (19%)

Low-Risk Customers: 16.4% (<5% churn probability)

Actual Churn Rate: 26.5%

Average LTV: $580

Max LTV: $3,142

Business Impact
Identify high-value customers for priority retention

Target at-risk customers proactively

Optimize resource allocation based on customer value

Improve contract strategies to reduce churn

Quick Start
bash
pip install -r requirements.txt
jupyter notebook ltv.ipynb
Files
ltv.ipynb - Main analysis

README.md - This documentation

requirements.txt - Dependencies

Recommendations
Use XGBoost model for predictions

Focus retention efforts on top 10% by LTV

Incentivize longer contracts (significantly lower churn)
