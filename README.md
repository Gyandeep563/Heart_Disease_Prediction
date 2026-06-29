# Heart Disease Prediction using Machine Learning

## Overview

This project predicts whether a patient is at risk of heart disease using various Machine Learning classification algorithms.

## Dataset

- Records: 50,000
- Features: 25
- Target:
  - 0 → No Heart Disease
  - 1 → Heart Disease

## Workflow

- Data Cleaning
- Feature Engineering
- Encoding
- Feature Scaling
- Model Training
- Model Evaluation
- Cross Validation
- GridSearchCV
- Feature Importance Analysis

## Models & Results

| Model | Accuracy |
|---------|----------:|
| Logistic Regression | 88.86% |
| Logistic Regression Pipeline | 92.56% |
| KNN (Without Scaling) | 70.21% |
| KNN (With Scaling) | 86.11% |
| SVM (Without Scaling) | 73.63% |
| SVM (With Scaling) | 94.10% |
| Decision Tree | 100.00% |
| Random Forest | 100.00% |


## Top Important Features

- Age
- Cholesterol_Total
- Hypertension
- Diabetes
- Previous_Heart_Attack

## Key Learnings

- EDA
- Feature Engineering
- One-Hot Encoding
- Feature Scaling
- Logistic Regression
- Decision Tree
- Random Forest
- KNN
- SVM
- Pipeline
- Cross Validation
- GridSearchCV
- Feature Importance

## Files

```text
Heart_disease_prediction.ipynb
README.md
```

## Note
Tree-based models achieved perfect performance on this dataset, likely due to strong predictive relationships among key health indicators.

Decision Tree and Random Forest achieved 100% accuracy on this dataset. Feature importance analysis revealed that Age, Cholesterol_Total, Hypertension, Diabetes, and Previous_Heart_Attack were the dominant predictors. The Decision Tree reached perfect classification with a depth of only 5, indicating that the dataset contains strong and easily separable patterns for tree-based models.

### View Notebook

If the notebook does not render properly on GitHub, open it using:
https://nbviewer.org/

## Author

**Gyandeep**

GitHub: https://github.com/Gyandeep563
