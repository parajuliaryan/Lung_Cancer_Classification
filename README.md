# Lung Cancer Classification

## Overview
This project focuses on classifying lung cancer risk using various machine learning techniques. It preprocesses the data, trains multiple classifiers, and performs comparative analysis to determine the best-performing model. The goal is to facilitate early diagnosis and improve patient outcomes.

## Key Features
- **Data Preprocessing:** Handles missing values, encodes categorical features, scales data, and performs feature selection.
- **Classifiers Implemented:**
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Decision Tree Classifier (DTC)
  - Random Forest Classifier
  - Margin-based refinement using SVM
- **Comparison:** Classifier performance evaluated using metrics and McNemar's test for statistical comparison.

## Dataset
The dataset used is the [Lung Cancer Risk Dataset](https://www.kaggle.com/datasets/humairmunir/lung-cancer-risk-dataset) from Kaggle.  
It contains various features related to lung cancer risk, such as:
- Age
- Smoking habits
- Genetic predispositions
- Occupational hazards  
and more. The dataset provides valuable insights into predicting lung cancer risk based on these factors.

## Dependencies
- Python (>=3.8)
- NumPy
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- Statsmodels

## Acknowledgments
- Kaggle and Humair Munir for the [Lung Cancer Risk Dataset](https://www.kaggle.com/datasets/humairmunir/lung-cancer-risk-dataset).
- Developers and contributors of the Python libraries used.
