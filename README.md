<p align="center">
  <img src="images/winthrop_log.png" width="100%">
</p>

# INBRE Summer Research 2026: Diabetes Prediction

## Overview

This project was completed as part of the INBRE Summer Research Program at Winthrop University.

The goal of this study is to develop an accurate and interpretable machine learning model for diabetes prediction using the Pima Indians Diabetes Dataset. We investigated several data preprocessing techniques and compared multiple classification models to evaluate their predictive performance.

---

## Research Poster

📄 **[View the Research Poster (PDF)](Poster/poster.pdf)**

---


## Dataset

- Dataset: Pima Indians Diabetes Dataset
- Source: UCI Machine Learning Repository
- Number of observations: 768
- Predictors: 8 clinical variables
- Response variable:
  - 0 = Non-diabetic
  - 1 = Diabetic
- Features include:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age

---

## Data Preprocessing

The following preprocessing methods were investigated:

- Mean imputation for missing values
- Z-score standardization
- Principal Component Analysis (PCA)
- K-means clustering
- Outlier removal within clusters

---

## Models

The following models were evaluated:

- Logistic Regression
- PCA + Logistic Regression
- K-means + Logistic Regression
- Support Vector Machine (Linear)
- Support Vector Machine (Radial)
- K-Nearest Neighbors (KNN)

---

## Model Evaluation

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve
- AUC
- AIC
- BIC

---

## Results

The study demonstrates that appropriate data preprocessing can improve model performance.

- Among all Logistic Regression approaches, the K-Means (k = 2) preprocessing strategy achieved the best overall performance, improving classification accuracy and producing the lowest AIC and BIC values.

- Overall, the KNN model (k = 5) delivered the best predictive performance, achieving the highest accuracy, precision, and recall among all models evaluated.

---

## Repository Structure

```text

├── Pima-Indians-Diabetes-Dataset/
│   ├── diabetes_imputed.csv
│   ├── diabetes.csv
│   ├── test_data_imputed.csv
│   ├── test_data.csv
│   ├── train_data_imputed.csv
|   └── train_data.csv
├── images/
│   └── winthrop_log.png
├── poster/
│   └── INBRE_Poster.pdf
├── Code/
│   ├── Logistic_Regression/
│   │   ├── 01_Original_LR.ipynb
│   │   ├── 02_Missing_Value_Imputation_LR.ipynb
│   │   ├── 03_PCA_LR.ipynb
│   │   └── 04_KMeans_LR.ipynb
│   ├── SVM_KNN_Graphs.ipynb
│   └── SVM.ipyn
```

---

## Author

Rong Wei & Ethan Beam

Mentor: Dr. Gihanee Senadheera

INBRE Summer Research Program

Department of Mathematics

Winthrop University

2026
