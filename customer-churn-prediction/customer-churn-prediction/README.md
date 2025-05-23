# Customer Churn Prediction

This project analyzes customer data to predict customer churn using machine learning models. It includes data preprocessing, exploratory data analysis (EDA), handling missing values, outlier treatment, balancing the dataset with SMOTE, and training classifiers such as K-Nearest Neighbors, Naive Bayes, and Support Vector Machine.

---

## Project Overview

Customer churn prediction is critical for businesses to retain customers and improve revenue. This project uses a dataset containing customer demographics and behavioral data to build predictive models that classify whether a customer will churn or not.

---

## Dataset

- The dataset `customer.csv` contains customer information such as demographics, loyalty scores, service subscriptions, and churn status.
- Features include both categorical and numerical variables.
- The target variable is `Churn` indicating whether the customer left (1) or stayed (0).

---

## Key Steps

1. Data loading and initial exploration
2. Handling missing values with mode and mean imputation
3. Visualizing distributions and relationships with seaborn plots
4. Outlier detection and treatment using IQR method
5. Encoding categorical variables with Label Encoding and One-Hot Encoding
6. Balancing classes using SMOTE to address class imbalance
7. Feature scaling with StandardScaler
8. Training and evaluating models:
    - K-Nearest Neighbors (KNN)
    - Bernoulli Naive Bayes
    - Support Vector Machine (SVM)
9. Performance evaluation using confusion matrix, accuracy, and classification report




