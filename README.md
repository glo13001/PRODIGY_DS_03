# PRODIGY_DS_03
Decision Tree Classifier for Bank Marketing Dataset

This repository contains Python code to build a Decision Tree Classifier for predicting whether a customer will subscribe to a product or service based on their demographic and behavioral data. The dataset used for this analysis is the Bank Marketing dataset from the UCI Machine Learning Repository.

About the Dataset

The Bank Marketing dataset consists of various features such as age, job, marital status, education, balance, housing loan status, personal loan status, contact type, and other attributes related to marketing campaigns. The goal is to predict the binary outcome 'y' (whether the customer subscribes or not) based on these features.

Files in the Repository

-bank.csv: The dataset file containing the banking data.
-decision_tree_classifier.ipynb: Jupyter Notebook containing Python code for data preprocessing, model training, evaluation, and visualizations.
-README.md: This file, providing an overview of the project.

Project Workflow

-Data Loading and Preprocessing:
Load the dataset and preprocess the data by encoding categorical variables and splitting the data into features and target.
-Decision Tree Classifier:
Build a Decision Tree Classifier using scikit-learn.
Train the model on the training data.
Make predictions on the test data.
-Model Evaluation:
Evaluate the model using accuracy, confusion matrix, and classification report.
Visualizations:
-Visualize the confusion matrix to understand the model's performance.
Plot feature importances to identify key factors influencing the predictions.
Visualize the ROC curve and calculate the AUC score for model evaluation.

Dependencies

-Python 3.x
-pandas
-scikit-learn
-matplotlib
-seaborn
