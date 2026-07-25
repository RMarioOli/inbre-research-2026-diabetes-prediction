<p align="center">
  <img src="images/winthrop_log.png" width="100%">
</p>

# INBRE Summer Research 2026: Diabetes Prediction

## Overview

This project was completed as part of the INBRE Summer Research Program at Winthrop University.

The goal of this study is to develop an accurate and interpretable machine learning model for diabetes prediction using the Pima Indians Diabetes Dataset. We investigated several data preprocessing techniques and compared multiple classification models to evaluate their predictive performance.

---

## Research Poster

📄 **{View the Research Poster (PDF)](Poster/poster.pdf)**

🌐 **[View the interactive poster online](Poster/poster.html)**

---


## Dataset

- Dataset: Pima Indians Diabetes Dataset
- Source: UCI Machine Learning Repository
- Number of observations: 768
- Predictors: 8 clinical variables
- Response variable:
  - 0 = Non-diabetic
  - 1 = Diabetic

Features include:

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

<!-- The study demonstrates that appropriate data preprocessing can improve model performance.

Among the evaluated approaches, clustering-based preprocessing combined with Logistic Regression achieved strong predictive performance while maintaining model interpretability. -->

---

## Repository Structure

```text

├── Pima-Indians-Diabetes-Dataset/
│   ├── diabetes.csv
│   ├── diabetes_imputed.csv
│   ├── test_data.csv
│   ├── train_data.csv
│   ├── test_data_imputed.csv
|   └── train_data_imputed.csv
├── images/
<!-- │   ├── boxplot_glucose.png
│   ├── boxplot_bmi.png
│   ├── scree_plot.png
│   ├── elbow_plot.png
│   ├── silhouette_plot.png
│   ├── kmeans_clusters.png -->
│   └── winthrop_log.png
├── poster/
│   ├── INBRE_Poster.pdf
│   └── INBRE_Poster.tex
<!-- ├── presentation/
│   ├── INBRE_Presentation.pptx
│   └── INBRE_Presentation.pdf -->
├── notebooks/
│   ├── Logistic_Regression/
│   │   ├── Original_LR.ipynb
│   │   ├── Missing_Value_Imputation_LR.ipynb
│   │   ├── PCA_LR.ipynb
│   │   └── KMeans_LR/
│   │       ├── Add_Clusters_As_Predictors.ipynb
│   │       ├── Cluster_Noise_Reduction.ipynb
│   │       └── Cluster_Noise_Reduction_Stepwise.ipynb
│   ├── SVM/
│   │   ├── Linear_SVM.ipynb
│   │   └── Radial_SVM.ipynb
│   └── KNN/
│       └── KNN_k5.ipynb
```

---

## Author

Rong Wei & Ethan Beam

INBRE Summer Research Program

Department of Mathematics

Winthrop University

2026
