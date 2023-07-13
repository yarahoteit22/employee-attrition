# employee-attrition
Executive Summary:

This executive summary provides an overview of the findings obtained from a group assignment in the Machine Learning II course within the IE's MBD program. The objective of the assignment was to identify the most effective machine learning model for predicting employee attrition based on a synthetic dataset generated from real data. The dataset consisted of information on 1,677 employees, including various demographic and work-related variables.

Employee attrition is a significant concern for organizations worldwide, leading to financial costs and other negative impacts. Understanding and predicting employee turnover can provide organizations with valuable insights to implement strategies and reduce turnover.

The report follows a technical pipeline, including data preparation, exploratory data analysis, feature engineering, and model training and selection. Data cleaning involved examining feature statistics, removing irrelevant features, handling missing values, and identifying skewed features. Exploratory data analysis explored correlations between variables and their relationships with employee attrition.

Feature processing and engineering included defining input and target variables, splitting the dataset, one-hot encoding categorical variables, scaling numerical features, and creating new features to improve model performance.

Four different models, namely Support Vector Machine (SVM), Logistic Regression, XGBoost, and Random Forest, were trained and evaluated using appropriate metrics for unbalanced data. Logistic Regression was selected as the optimal model based on its ROC AUC score, precision, recall, MCC, and Cohen's Kappa. Feature importance analysis identified travel frequency, overtime work, and job role as top predictors of employee attrition.

Implementing a data-driven people analytics approach enables organizations to make informed decisions, reduce costs, and address workforce-related challenges proactively. However, there were challenges throughout the process, and opportunities for improvement were identified, such as incorporating dimensionality reduction techniques and utilizing pipelines for preprocessing.

In conclusion, the assignment demonstrates the power of machine learning and data analytics in predicting employee attrition and providing valuable insights for effective HR management.
