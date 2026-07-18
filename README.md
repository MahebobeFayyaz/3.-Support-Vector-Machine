# Breast Cancer Diagnosis Prediction Using Support Vector Machine (SVM)

## Project Overview

This project implements a **Support Vector Machine (SVM)** model to classify breast tumors as **Benign** or **Malignant** using the Breast Cancer Wisconsin Diagnostic Dataset.

The project demonstrates an end-to-end machine learning workflow, including data preprocessing, feature scaling, SVM kernel comparison, hyperparameter tuning, and model evaluation.
<img width="977" height="659" alt="Linear_SVM" src="https://github.com/user-attachments/assets/3a7cbc34-cf8e-41ea-9246-02d81ca27d67" />

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
Kernel: RBF
C: 1
Gamma: Scale
Degree: 2


**Best Cross-Validation Accuracy:**
97.58%

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Support Vector Machine (SVC)

---

## Key Concepts Covered

- Maximum Margin Hyperplane
- Support Vectors
- Kernel Trick
- Linear vs Non-Linear Classification
- C Parameter (Regularization)
- Gamma Parameter
- Cross Validation
- Hyperparameter Optimization

---

## Conclusion

The Support Vector Machine model successfully learned patterns from cell nucleus measurements and achieved strong classification performance in distinguishing malignant and benign tumors.

This project demonstrates the practical application of SVM for binary classification problems in healthcare analytics.
