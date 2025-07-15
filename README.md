# Credit Card Fraud Detection
## Overview
This project leverages machine learning to detect fraudulent credit card transactions with high accuracy, using a real-world dataset of over 555,000 records from Kaggle. The goal is to develop a robust and interpretable fraud detection system that enables financial institutions to minimise risk and reduce manual oversight.

## Dataset
[https://www.kaggle.com/datasets/kelvinkelue/credit-card-fraud-prediction ](url)

The dataset is comprised of 555,719 transactions and 22 attributes, featuring a balanced mix of numerical and categorical variables. With no missing values, it offers a clean and reliable foundation for predictive modelling.

## Project Objectives
- Develop high-accuracy classification models to detect fraudulent transactions and minimise financial losses.
- Enhance model reliability by reducing false positives through feature engineering, data balancing, and AUC-based evaluation.
- Deliver interpretable insights to inform fraud prevention strategies.

## Methodology
- Performed extensive data cleaning, feature engineering (eg. creation of age and time category variables), and one-hot encoding for categorical features.
- Addressed class imbalance through undersampling techniques to improve model sensitivity.
- Conducted statistical testing (chi-squared, correlation coefficients, Mann–Whitney U) and visual analysis to identify key data patterns.
- Trained and evaluated models such as Random Forest, Logistic Regression, Multi-Layer Perceptron (MLP), and K-Nearest Neighbours (KNN).
- Assessed models using accuracy, True Positive Rate (TPR), False Positive Rate (FPR), and AUC metrics.
  
## Key Findings
- Transaction amount, product category, gender, purchase time, and customer age are significant predictors of fraud.
- Random Forest achieved the best performance with 97% accuracy and AUC of 0.99, effectively balancing detection and false alarms.

## Impact
- Accurately flags suspicious transactions, reducing false alarms and undetected fraud.
- Empowers financial institutions to streamline fraud monitoring and proactively manage risk.
- Supports data-driven decision-making through explainable, model-backed insights.

## Recommendations
- Increase monitoring during high-risk times and platforms based on model insights.
- Foster collaboration with industry partners for continuous model improvement.
- Promote awareness of fraud patterns among stakeholders.

## Conclusion
Effective fraud detection demands continuous innovation. By combining robust machine learning techniques with interpretable insights, this project demonstrates how data science can strengthen financial security and adapt to evolving threats.

