# HyperTensionAnalytics
Data Analysis and Prediction of Hypertension from South Korean Health Check-up Data 

## Project Overview
This project focuses on developing a machine learning model to predict whether a patient has hypertension based on their health checkup data. The dataset contains structured data from healthcare screenings, and the goal is to identify key variables that influence hypertension and improve the prediction model's performance through various machine learning algorithms.

## Key Features:
- Dataset: Structured data from health check-ups in CSV format
- Target: Binary classification - Predict whether a patient has hypertension or not
- Language: Python
- Libraries: pandas, scikit-learn, matplotlib, seaborn, numpy
Project Workflow
1. Data Preprocessing: Handling Missing Data: Missing values in the dataset are imputed 
Outlier Detection and Removal: Outliers in critical features such as blood pressure or weight are identified and removed.
Data Normalization: Continuous variables (e.g., weight, height) are normalized to ensure all features are on a similar scale, improving model performance.

2. Feature Selection & Engineering:
Important Variable Selection: Correlation analysis and feature importance techniques (such as from Random Forests) are used to select key variables that strongly influence hypertension prediction.
New Feature Generation: Derived features such as BMI (calculated from height and weight) are created to enhance model performance.

3. Modeling:
Algorithms Used:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
Gradient Boosting (e.g., XGBoost)
Cross-Validation: k-fold cross-validation is used to evaluate model performance across various folds of the data.
Metrics: Accuracy, precision, recall, F1-score, and ROC-AUC are used to evaluate model effectiveness.

4. Model Evaluation & Selection:
Based on the performance metrics, the model with the best overall performance is selected for final deployment. Hyperparameter tuning is done to optimize the chosen model's performance further.