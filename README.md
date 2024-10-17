# Credit Risk Modeling

## Project Overview

This project focuses on building a **Credit Risk Modeling** system to predict the likelihood of default on loans or credit by individuals. The objective is to analyze various features of credit data and use machine learning techniques to assess risk levels, aiding financial institutions in making informed lending decisions.

## Objectives

- **Predict Credit Risk**: Classify loan applicants as either high or low risk based on their credit profile.
- **Minimize Default Rates**: Assist financial institutions in reducing default rates by identifying high-risk applicants early.
- **Improve Decision-Making**: Provide data-driven insights to improve lending strategies.

## Dataset

- **Source**: The dataset used in this project contains information on borrowers' demographic and financial features, such as income, loan amount, credit history, and repayment records.
- **Features**:
  - Loan Amount
  - Income
  - Credit Score
  - Employment Status
  - Loan Purpose
  - Debt-to-Income Ratio
  - Previous Default

## Methodology

1. **Data Preprocessing**:
   - Handling missing values
   - Feature engineering
   - Encoding categorical variables
   - Scaling numerical features

2. **Model Selection**:
   - Logistic Regression
   - Random Forest
   - XGBoost
   - Support Vector Machine (SVM)
   
3. **Evaluation Metrics**:
   - **Accuracy**: Measures the overall correctness of the model.
   - **Precision & Recall**: Helps assess the trade-off between predicting high-risk applicants correctly and minimizing false positives.
   - **AUC-ROC Curve**: Evaluates the performance of the model in distinguishing between high-risk and low-risk applicants.

## Results

- **Best Performing Model**: XGBoost showed the best performance with an accuracy of 87% and an AUC-ROC score of 0.91.
- **Feature Importance**: The most important factors for predicting credit risk were **Credit Score**, **Income**, and **Debt-to-Income Ratio**.

## Conclusion

The model developed in this project successfully classifies credit risk, providing valuable insights for financial institutions. Future improvements include tuning the hyperparameters of the models and incorporating additional features such as economic indicators to improve prediction accuracy.

## Future Work

- Hyperparameter tuning for better model performance
- Use of deep learning models for enhanced risk prediction
- Integration of external financial and economic indicators
