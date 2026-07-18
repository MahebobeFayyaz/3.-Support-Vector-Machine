# Breast Cancer Diagnosis Prediction Using Support Vector Machine (SVM)

## Project Overview

This project implements a **Support Vector Machine (SVM)** model to classify breast tumors as **Benign** or **Malignant** using the Breast Cancer Wisconsin Diagnostic Dataset.

The project demonstrates an end-to-end machine learning workflow, including data preprocessing, feature scaling, SVM kernel comparison, hyperparameter tuning, and model evaluation.
Images/Linear_SVM.JPG
---

## Dataset

**Dataset:** Breast Cancer Wisconsin (Diagnostic) Dataset

- Samples: 569
- Features: 30 numerical features
- Target: Diagnosis
  - 0 → Benign
  - 1 → Malignant

The features represent characteristics of cell nuclei such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

---

## Project Workflow

- Data Loading and Exploration
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Scaling using StandardScaler
- Training Support Vector Classifier (SVC)
- Visualization of Linear SVM Decision Boundary
- Comparison of SVM Kernels:
  - Linear
  - Polynomial
  - RBF
  - Sigmoid
- Hyperparameter Tuning using GridSearchCV
- Model Evaluation

---

## Model Optimization

GridSearchCV was used to find the optimal SVM parameters.

**Best Parameters:**
