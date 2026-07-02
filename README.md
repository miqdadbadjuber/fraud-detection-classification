# Fraud Detection Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Accuracy](https://img.shields.io/badge/Accuracy-100%25-28A745?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-2EA44F?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-00C853?style=for-the-badge)

A Machine Learning project for fraud detection classification using Decision Tree and Random Forest algorithms with hyperparameter tuning.

---

## Overview

This project focuses on fraud detection using supervised machine learning algorithms.

The workflow covers the complete machine learning pipeline, including:

- Data preprocessing
- Train-test split
- Decision Tree model training
- Random Forest model training
- Hyperparameter tuning using GridSearchCV
- Model evaluation
- Model comparison
- Export trained models

---

## Dataset

Source:

**Processed dataset generated from the fraud detection pipeline.**

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
├── LICENSE
└── README.md
```

---

## Model Performance

| Model | Accuracy |
|--------|---------:|
| Decision Tree | **100.00%** |
| Random Forest | **100.00%** |
| Tuned Random Forest | **100.00%** |

All three trained models achieved **100% classification accuracy** on the test dataset.

---

## Models

The repository contains three trained machine learning models:

| Model | Description |
|--------|-------------|
| Decision Tree | Baseline classification model |
| Random Forest | Ensemble classification model |
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
- Explore XGBoost and LightGBM
- Improve feature engineering
- Perform advanced hyperparameter optimization
- Deploy the trained model using FastAPI or Streamlit

---

## Author

**Miqdad Badjuber**

GitHub: https://github.com/miqdadbadjuber
