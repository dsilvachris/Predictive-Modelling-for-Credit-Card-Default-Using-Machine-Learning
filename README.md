# Predictive-Modelling-for-Credit-Card-Default-Using-Machine-Learning

Project Overview

This project aims to predict credit card payment defaults, enabling banks to identify high-risk customers and intervene before defaults occur. Utilizing the Credit Card Default dataset, it focuses on constructing a machine learning model to predict whether a customer will default (1) or not (0) within the next month. The notebook comprises five major tasks: data understanding, exploratory data analysis, data preprocessing, model training & evaluation, and model interpretation using SHAP. Early prediction of defaults is crucial for minimizing financial losses and enhancing credit policies, aiding in more informed lending decisions.

Dataset Overview & Initial Preprocessing

The dataset is used to predict whether a credit card client will default on their payment in the next month, making it a binary classification problem in the financial risk domain.

It comes from a credit card default dataset (Credit_Card.csv) and contains 34,788 records and 30 features, including demographic information, credit limits, billing amounts, and repayment history

The target variable is default.payment.next.month, where 1 indicates a default (fraud/risk) and 0 indicates no default, which is the key outcome the model aims to predict.
