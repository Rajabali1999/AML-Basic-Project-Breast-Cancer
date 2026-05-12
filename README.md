
 # Breast Cancer Diagnosis: Benign vs Malignant using Logistic Regression (Binary Classification)

For this AML-BASIC project, the Breast Cancer **Wisconsin (Diagnostic) dataset** was selected from the official Suggested Datasets document.

The dataset contains **569** samples, each described by **30 numerical features** extracted from digitized images of Fine Needle Aspiration (FNA) of breast masses. These features represent characteristics of cell nuclei such as radius, texture, perimeter, area, smoothness, and shape irregularities.

The goal of this project is to develop a **binary classification model** capable of distinguishing between benign and malignant tumors using a supervised machine learning approach.

# Project Overview

This project addresses the following key aspects of a complete machine learning pipeline:

**Exploratory Data Analysis (EDA):**
Understanding the dataset distribution, feature behavior, and relationships between variables.

**Feature Preprocessing and Selection:**
Handling different feature scales, addressing multicollinearity, and preparing data for modeling.

**Handling Class Imbalance:**
The dataset contains 357 benign and 212 malignant samples, requiring appropriate strategies such as stratified splitting and class-weighted learning to avoid biased predictions.

**Baseline Model Comparison:**
Establishing a Dummy Classifier baseline to evaluate the added value of machine learning.

**Logistic Regression Modeling:**
Training an interpretable classification model suitable for medical applications.

**Model Evaluation and Interpretation:**
Using metrics such as accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix, with emphasis on clinical interpretability.

# Dataset

The dataset used in this project is the **Wisconsin Diagnostic Breast Cancer (WDBC) Dataset**, available from the **UCI Machine Learning Repository**.

The dataset contains measurements computed from digitized images of fine needle aspirate (FNA) of breast masses.

# Dataset Information

* **Total Samples:** 569
* **Total Features:** 30 numerical features

### Target Classes

* **M** – Malignant
* **B** – Benign

### Example Features

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry
* Fractal Dimension


# Key Challenges

* Feature engineering for derived indicators (mean, standard error, worst values)
* Addressing class imbalance (**357 benign vs 212 malignant samples**)

---

# Workflow Overview

The project follows a complete machine learning workflow including hypothesis formulation, exploratory data analysis, baseline comparison, model development, and evaluation.

Introduction
1. Hypothesis
2. Data Loading and Preliminary Exploration
3. Exploratory Data Analysis (EDA)
4. Data Preparation
5. Baseline Model – Dummy Classifier
6. Feature Standardization
7. Logistic Regression Modeling
8. .Performance evaluation using multiple metrics
9. Result Evaluation
10. Interpretation of model results and coefficients
11. ROC Curve and AUC Analysis
12. BASELINE COMPARISON
13. Discussion
14. Limitations
15. Conclusion

---

# Major Updates

### Baseline Model Introduction

A **Dummy Classifier** was added as a benchmark model.

**Accuracy Comparison**

* Dummy Classifier: ~63%
* Logistic Regression: ~97%

---

# Machine Learning Models Used

Two classification algorithms were implemented:

1. **Logistic Regression**
2. **Dummy Classifier** (Baseline Model)

### Model Training Steps

* Dataset split using `train_test_split`
* Feature scaling using `StandardScaler`
* Model evaluation using:

  * Confusion Matrix
  * Classification Report
  * ROC Curve
  * AUC Score

---

# Supporting Libraries

These libraries were used for data processing and visualization:

* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **Scikit-learn**

---

# Enhanced Exploratory Data Analysis & Preprocessing

* Visualized feature distributions and class imbalance
* Created correlation heatmaps to analyze feature relationships
* Automatically removed highly correlated features (**correlation > 0.9**) to reduce multicollinearity

---

# Refined Report Structure

The project report follows a **clear modular format** combining:

* Markdown explanations
* Python code blocks
* Model interpretation and analysis

---

# Expanded Results & Discussion

The results section includes discussion of:

* Model performance
* Dataset limitations
* Risk factors in prediction
* Possible improvements to the machine learning pipeline

This work also prepares the foundation for more advanced machine learning implementations in future AML projects.

---

# Additional Enhancements

* Improved handling of class imbalance
* Strict feature standardization
* More comprehensive performance evaluation metrics

---
