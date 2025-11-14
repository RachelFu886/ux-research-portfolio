# Credit Risk Modeling – XGBoost Pipeline

## Overview
Built an end-to-end machine learning pipeline to predict device financing default risk using payment history, down payment patterns, and credit score data. Project demonstrates my skills in data engineering, modeling, and insight synthesis.

## Data & Features
- **Records:** 6,000+  
- **Key Features:**  
  - FICO score  
  - Down payment amount  
  - Income ratio  
  - Installment history  
  - Device tier  
- **Target:** Binary default flag  

## Pipeline
1. Data cleaning (missing values, outliers)  
2. Feature engineering  
3. Train-test split  
4. Model training using XGBoost  
5. Evaluation + feature importance  

## Evaluation Metrics
- **AUC:** 0.79  
- **Accuracy:** 84%  
- **Balanced precision/recall**  
- **Confusion Matrix** analyzed in notebook  

## Key Insights
- Lower down payments are strongly associated with higher risk  
- High-tier devices correlate with lower default (self-selection effect)  
- FICO score is the strongest single predictor  

## Tools
Python · Pandas · Matplotlib · XGBoost · Jupyter Notebook  

## Impact
- Provides a clear, interpretable risk pipeline  
- Useful for improving approval decisions and reducing revenue loss  
