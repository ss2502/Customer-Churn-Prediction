# Customer-Churn-Prediction
This project focuses on predicting customer churn in a telecommunications company using machine learning. Customer churn, or the rate at which customers leave a service, is a critical metric for businesses, and predicting it can help in implementing retention strategies.
Key Features
Data Cleaning and Exploration: The dataset is thoroughly cleaned and explored to identify missing values, outliers, and distribution of key variables.

Exploratory Data Analysis (EDA): The EDA phase involves visualizing the distribution of churn, analyzing summary statistics, and creating visualizations to understand the impact of various factors on customer churn.

Building Predictive Models: Two predictive models are implemented — a logistic regression model and a random forest model. These models utilize customer-related features such as tenure, monthly charges, total charges, internet service type, and contract type to predict the likelihood of churn.

Model Evaluation: The models are evaluated using a confusion matrix, accuracy, precision, recall, and F1 score. ROC curves and AUC values are also calculated.

Findings
Logistic Regression Model: The logistic regression model identifies key factors impacting churn. Longer tenures, lower monthly charges, and total charges are associated with lower odds of churn. Fiber optic internet service and month-to-month contracts are linked to higher odds of churn.

Random Forest Model: The random forest model provides an OOB estimate of the error rate and a confusion matrix. It offers an alternative approach to predict churn and can be compared to the logistic regression model for performance.

Usage
The Jupyter Notebook in this repository contains the entire data analysis and modeling process.

Clone the repository and run the notebook to reproduce the analysis on your local machine.

Dependencies
The analysis is performed using R, and key packages such as tidyverse, caret, randomForest, and others are utilized.
Future Work
Further refinement of models, hyperparameter tuning, and inclusion of additional features could improve predictive performance.
