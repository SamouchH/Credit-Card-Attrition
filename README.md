# Credit Card Attrition Prediction

## Overview
This project focuses on predicting customer attrition for a banking institution. The primary objective is to understand the key factors influencing credit card customer churn and to develop a predictive model to identify customers likely to leave.

## Problem Statement
The bank has experienced a decline in revenue due to customer attrition. The challenge is to analyze customer data to understand the reasons behind this trend and predict future attrition, enabling the bank to implement retention strategies proactively.

## Data Description
The dataset contains historical customer data, including demographics, transaction information, and churn status. It comprises multiple features that describe the customers' relationship with the bank, such as age, balance, transactions, and credit score.

## Methodology
The approach taken involves several steps:
- Data preprocessing, including handling missing values and encoding categorical variables
- Exploratory Data Analysis (EDA) to understand the data distribution and identify patterns
- Feature selection using Random Forest to determine the most significant predictors of attrition
- Model development and evaluation, applying various machine learning algorithms such as Logistic Regression, Decision Trees, Random Forest, SVM, KNN, XGBoost, CatBoost, LightGBM, and ensemble methods
- Hyperparameter tuning to optimize model performance
- Evaluation metrics including accuracy, precision, recall, F1 score, ROC-AUC, and precision-recall curves to assess models

## Results
The ensemble method, specifically the Voting Classifier, yielded the highest accuracy, demonstrating the effectiveness of combining multiple models. Feature importance analysis revealed that `Total_Trans_Ct` and `Total_Revolving_Bal` were significant predictors of attrition.

## Conclusions and Recommendations
The analysis indicates that transaction behavior and revolving balance are critical in predicting customer churn. The bank should focus on these areas to develop targeted retention strategies.

## Further Reading
For more insights and a detailed walkthrough of this project, you can read my article on Medium: https://medium.com/@samoucheharoune/credit-card-attrition-0e02d61215ac

## Next Steps
Further work could explore:
- More advanced feature engineering techniques
- Deep learning models for potential performance improvements
- Deployment of the model as a real-time prediction service

## Notebook
The project is available as a notebook, which can be run in Google Colab:
https://colab.research.google.com/github/SamouchH/Credit-Card-Attrition/blob/main/Credit_Card_Attrition.ipynb

## Data
The dataset used for this analysis can be found here:
https://github.com/SamouchH/Credit-Card-Attrition/blob/main/Bank_Churn.csv

## Author
- Haroune Samouche

## Acknowledgements
Thanks to all contributors to the project and mentors for their support.
