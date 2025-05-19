# 🧠 Brain Stroke Prediction using Machine Learning

## 📌 Project Overview

This project implements and evaluates multiple machine learning models for predicting the occurrence of brain strokes using health-related data such as age, gender, BMI, glucose levels, hypertension, heart disease, and more. The goal is to determine which model performs best at identifying high-risk individuals and to compare the results with those published in the paper:

**- Implement and evaluate the following machine learning models:**  
  - KNN (k = 5 and k = 173)
  - Logistic Regression
  - Random Forest
  - Decision Tree
  - Naive Bayes
  - SVM (Linear, RBF, Polynomial, Sigmoid kernels)
  - XGBoost

**- Assess model performance using metrics:**
  - Accuracy
  - F1 Score
  - Precision
  - Recall
  - Log Loss
  - ROC-AUC

- Replicate findings from the referenced paper
- Utilize **MLflow** for tracking experiments and logging metrics

## 📁 Dataset Description

The dataset is derived from electronic health records (EHR) and consists of 11 features and 1 target variable (`stroke`). The features are:

| Feature           | Description                                         |
|------------------|-----------------------------------------------------|
| `gender`          | Gender of the patient                              |
| `age`             | Age of the patient                                 |
| `hypertension`    | Whether the patient has hypertension               |
| `heart_disease`   | Whether the patient has heart disease              |
| `ever_married`    | Marital status                                     |
| `work_type`       | Job type (Govt_job, Private, Self-employed, etc.) |
| `Residence_type`  | Urban or Rural                                     |
| `avg_glucose_level` | Average glucose level                           |
| `bmi`             | Body Mass Index                                    |
| `smoking_status`  | Smoking status (never, former, current)            |
| `stroke`          | Target variable (1 = stroke, 0 = no stroke)        |

> ⚠️ **Note**: The dataset is highly imbalanced, with far fewer stroke cases than non-stroke cases.
