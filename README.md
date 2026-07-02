# Fraud Detection Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Accuracy](https://img.shields.io/badge/Accuracy-100%25-28A745?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-2EA44F?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-00C853?style=for-the-badge)

A Machine Learning classification project for fraud detection using Decision Tree and Random Forest algorithms with hyperparameter tuning to improve predictive performance.

---

## Overview

This project builds classification models based on the clustering results obtained from the previous stage.

The workflow covers the complete machine learning pipeline, including:

- Data preprocessing
- Train-test split
- Decision Tree training
- Random Forest training
- Hyperparameter tuning
- Model evaluation
- Model comparison
- Model export

---

## Dataset

Source:

**Processed dataset generated from the clustering stage.**

Target Classes:

- Fraud
- Non-Fraud

---

## Features

- Data preprocessing
- Train-Test Split
- Decision Tree Classifier
- Random Forest Classifier
- Hyperparameter Tuning (GridSearchCV)
- Classification Report
- Model Performance Comparison
- Export trained models using Joblib

---

## Project Structure

```text
fraud-detection-classification/
├── models/
│   ├── decision_tree_model.h5
│   ├── explore_RandomForest_classification.h5
│   └── tuning_classification.h5
├── classification_analysis.ipynb
├── requirements.txt
└── README.md
```

---

## Model Performance

| Model | Accuracy |
|--------|---------:|
| Decision Tree | **100.00%** |
| Random Forest | **100.00%** |
| Tuned Random Forest | **100.00%** |

The tuned Random Forest model achieved the best overall performance after hyperparameter optimization using GridSearchCV.

---

## Models

The project includes three trained machine learning models:

| Model | Description |
|--------|-------------|
| Decision Tree | Baseline classification model |
| Random Forest | Ensemble learning model |
| Tuned Random Forest | Optimized Random Forest using GridSearchCV |

---

## Technologies

- Python
- Scikit-Learn
- Pandas
- NumPy
- Joblib
- Jupyter Notebook

---

## Future Improvements

- Evaluate using cross-validation
- Experiment with XGBoost and LightGBM
- Improve feature engineering
- Optimize hyperparameter search
- Deploy the classification model using FastAPI or Streamlit

---

## Author

**Miqdad Badjuber**

GitHub: https://github.com/miqdadbadjuber
