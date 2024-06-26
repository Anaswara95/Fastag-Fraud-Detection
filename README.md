# Fastag-Fraud-Detection
## [DATASET](https://www.kaggle.com/datasets/thegoanpanda/fastag-fraud-detection-datesets-fictitious/code)

## Introduction

This project aims to develop a robust machine learning model to predict toll transaction outcomes based on various vehicle and transaction attributes. The following steps outline the main processes involved in this project:

### Project Steps
**1. Data Collection:**
- Gathered a dataset with features such as amount paid, fraud indicator, vehicle speed, transaction hour, vehicle type, and tollbooth IDs.

**2. Data Preprocessing**
- Removed outliers and handled missing values to ensure data quality.

- Deleted columns with multicollinearity to avoid redundancy and improve model performance.

**3.Feature Engineering:**
- Created new features and transformed existing ones to better represent the data.

**4. Model Selection:**
- Explored several classification algorithms including Logistic Regression, Decision Tree, Random Forest, SVC, and Naive Bayes.

**5. Hyperparameter Tuning:**
- Used GridSearchCV to perform hyperparameter tuning and find the best parameters for each model.

**6. Model Evaluation:**
- Evaluated the models using metrics such as accuracy, precision, recall, F1 score, and ROC AUC.

- Selected the Random Forest classifier as the best-performing model based on these metrics.

**7. Model Saving and Loading:**
- Saved the trained Random Forest model using joblib.

- Provided code for loading the model to make predictions on new, unseen data.

**8. Future Work:**
- Suggested improvements like collecting more data, trying different algorithms, resampling in case of imbalanced data, and adding more features for better accuracy and performance.

***By following these steps, the project demonstrates a comprehensive approach to developing and deploying a machine learning model for predicting toll transaction outcomes, offering valuable insights for enhancing toll management systems.***
