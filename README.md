
# AML Basic Project Breast Cancer Prediction

# Project Overview

This project applies machine learning to perform **binary classification** for breast cancer diagnosis. The model predicts whether a tumor is **benign** or **malignant** using numerical features from the **Wisconsin Diagnostic Breast Cancer Dataset**.

The implementation is developed using **Python** and the **Scikit-learn** machine learning library, with **Logistic Regression** as the primary classification algorithm.

The goal of this project is to demonstrate how machine learning algorithms can be applied to structured medical data to build predictive models for breast cancer diagnosis.


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

1. Hypothesis
2. Data Loading and Preliminary Exploration
3. Exploratory Data Analysis (EDA)
4. Data Preparation
5. Baseline Model – Dummy Classifier
6. Feature Standardization
7. Logistic Regression Modeling
8. Result Evaluation
9. ROC Curve and AUC Analysis
10. Discussion

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
