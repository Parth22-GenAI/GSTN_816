# GSTN Hackathon - Predictive Model
This repository contains the final submission for the GSTN Hackathon, which focuses on building a machine learning model to solve a classification problem using a dataset provided by GSTN. The project includes steps for data preprocessing, model construction, and evaluation to deliver optimized predictions.

# Project Overview
The goal of this project is to develop a robust classification model using a dataset of approximately 900,000 records with 21 attributes. The model predicts the target variable by leveraging various machine learning techniques and methods.

# Features
-Data Importing: Load and preprocess input features (X) and target labels (Y) from CSV files.
-Exploratory Data Analysis (EDA): Visualize and analyze the dataset using Seaborn and Matplotlib to gain insights into feature relationships and distributions.
-Data Preprocessing: Handle missing data, encode categorical variables, and normalize the dataset.
-Modeling: Train and evaluate multiple classification models, including:
  K-Nearest Neighbors (KNN)
  Logistic Regression
  Decision Tree Classifier
  Random Forest Classifier
  Gradient Boosting Classifier
  Naive Bayes Classifiers (GaussianNB, BernoulliNB)
  StackingClassifier with Logistic Regression as the final estimator.
-Model Evaluation: Use metrics such as accuracy, confusion matrix, and other relevant performance metrics to assess model performance.

# Results
The final model, using a StackingClassifier with Logistic Regression as the meta-model, achieved high accuracy and robust predictive performance. Detailed results and evaluation metrics are documented in the notebook.
