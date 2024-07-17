# Heart Disease Predictor

## Project Overview

This project involves creating a machine learning model to predict the likelihood of heart disease in patients. The model is built using the logistic regression algorithm, and the dataset used is sourced from Kaggle.

## Problem Statement

The main objective of this project is to develop a predictive model that can identify patients at risk of heart disease. By analyzing various health-related factors, the model aims to assist healthcare providers in making informed decisions and taking preventive measures.

## Dataset

The dataset used in this project is from Kaggle and contains various features related to patients' health. The dataset includes the following columns:

- `age`: Age of the patient
- `sex`: Gender of the patient
- `cp`: Chest pain type (4 values)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl
- `restecg`: Resting electrocardiographic results (values 0, 1, 2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels (0-3) colored by fluoroscopy
- `thal`: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
- `target`: Diagnosis of heart disease (1 = presence; 0 = absence)

## Methodology

1. **Data Collection and Preparation**: Load the dataset, handle missing values, and preprocess the data for analysis.
2. **Exploratory Data Analysis (EDA)**: Perform EDA to understand the distribution of data and identify any patterns or correlations.
3. **Feature Selection**: Identify the most significant features that impact heart disease prediction.
4. **Modeling**: Use the logistic regression algorithm to build a predictive model.
5. **Evaluation**: Evaluate the performance of the model using appropriate metrics such as accuracy, precision, recall, and F1-score.
6. **Insights and Recommendations**: Derive insights from the analysis and suggest recommendations for healthcare providers.
