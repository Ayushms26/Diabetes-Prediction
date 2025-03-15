
# Diabetes Prediction: A Classification Problem

## Overview

This project implements various machine learning models to predict the likelihood of an individual having diabetes based on health-related factors such as Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age. The objective is to predict whether an individual has diabetes (binary classification: 1 for diabetes, 0 for non-diabetes).

Models like Decision Trees, Random Forest, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and XGBoost are applied to the dataset, with the model performance evaluated using accuracy and AUC (Area Under the Curve) scores.

## Dataset

The dataset used is the **Pima Indians Diabetes Database**, containing 768 entries with the following columns:

- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure
- **SkinThickness**: Skinfold thickness
- **Insulin**: 2-hour serum insulin
- **BMI**: Body mass index
- **DiabetesPedigreeFunction**: Family history of diabetes
- **Age**: Age of the individual
- **Outcome**: Whether the individual has diabetes (1) or not (0)

## Features

- **Data Preprocessing**: Cleans and transforms the data for model training.
- **Model Training**: Trains multiple machine learning models.
- **Evaluation**: Evaluates model performance using accuracy and AUC.
- **Feature Selection**: Uses 7 health-related features for prediction.

## Usage

- Run the main Python script or Jupyter Notebook to execute the analysis and prediction tasks.
- The script performs the following:
  - Loads and preprocesses the data
  - Trains and evaluates various machine learning models (KNN, SVM, Decision Tree, Random Forest, XGBoost)
  - Outputs evaluation metrics such as accuracy and AUC scores

## Results

- **KNN and SVM** achieved the highest accuracy of **0.81** and an AUC score of **0.86**, demonstrating strong performance.
- The models effectively predict diabetes and can be used for early detection.

## Conclusion

This project demonstrates how machine learning algorithms can be used for predicting diabetes based on common health metrics. The best-performing models, KNN and SVM, show strong predictive capabilities with high accuracy and AUC scores.
