# Rainfall Prediction Using Machine Learning 🌧️📊

## Introduction

This project focuses on predicting rainfall in India using machine learning techniques. The dataset consists of historical rainfall data across various subdivisions in India, and the goal is to classify annual rainfall into categories: Low, Medium, and High. The project explores different ML models, including Random Forest, Support Vector Machine (SVM), and Logistic Regression.

## Dataset

- **Source:** Indian Meteorological Department (IMD) Dataset
- **Features:** Monthly rainfall data, seasonal rainfall, subdivision, year, etc.
- **Target Variable:** Rainfall category (Low, Medium, High)

## Machine Learning Models Used

- **Random Forest Classifier** 🌲
- **Support Vector Machine (SVM)** 📈
- **Logistic Regression** 📊

## Project Workflow

1. **Data Preprocessing:** Handling missing values, encoding categorical variables.
2. **Exploratory Data Analysis (EDA):** Visualizing rainfall distribution.
3. **Model Training & Evaluation:** Training and testing multiple ML models.
4. **Feature Importance Analysis:** Understanding which factors influence rainfall the most.
5. **Model Comparison & Visualization:** Evaluating and comparing model performance.

## Results

### **Model Performance Comparison**

| Model                   | Accuracy | Precision | Recall | F1 Score |
| ----------------------- | -------- | --------- | ------ | -------- |
| **Random Forest**       | 95.2%    | 97%       | 96%    | 96%      |
| **SVM**                 | 96.02%   | 97%       | 97%    | 97%      |
| **Logistic Regression** | 97.3%    | 98%       | 97%    | 97%      |

- **Best Model:** Logistic Regression
- **Feature Importance:** Seasonal rainfall and monsoon months contribute most to prediction accuracy.

## Model Comparison & Visualization

To compare the models, we use:

1. **Bar Chart:** Comparing accuracy of Random Forest, SVM, and Logistic Regression.
2. **Confusion Matrix:** Analyzing misclassification patterns.
3. **ROC Curve:** Evaluating classification performance.

### **Accuracy Comparison**

A bar chart is used to compare the accuracy of each model.

### **Confusion Matrices**

Confusion matrices help us understand where each model makes classification mistakes.

### **ROC Curve**

The ROC curve is plotted for a multi-class setting using the One-vs-Rest (OvR) strategy to compare the probability-based performance of each model.

## Contributing

Feel free to fork this repository, improve the model, and submit a pull request! 😊

