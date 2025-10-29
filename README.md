# CodeAlpha_CreditScoring

**Objective**
To build a machine learning model that predicts whether a loan applicant will be able to repay a loan or will default, based on financial and personal information.

**Dataset**
Source: [Credit Risk Dataset on Kaggle](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)
Records: ~28,000 samples after cleaning
Target column: loan_status
    0 → Loan fully paid
    1 → Loan defaulted
    
**Technologies Used**
Language: Python
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Environment: Google Colab

**Steps Followed**
1-Data exploration (EDA) and visualization
2-Cleaning and handling missing values
3-Automatic encoding for categorical features
4-Splitting data into training and testing sets
5-Feature scaling using StandardScaler
6-Model training and evaluation:
    Logistic Regression
    Random Forest Classifier
7-Feature Importance visualization

**Results**
Logistic Regression : Accuracy = 0.78
Random Forest : Accuracy = 0.93

The Random Forest Classifier outperformed Logistic Regression, achieving an overall accuracy of 93%.
It can accurately identify risky loan applicants with high precision.
