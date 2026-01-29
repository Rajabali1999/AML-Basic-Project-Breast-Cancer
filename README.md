# AML-Basic-Project-Breast-Cancer#  

 Breast Cancer Benign vs Malignant Diagnosis: Logistic Regression Analysis (Binary Classification)
 
I selected the BASIC-2 Breast Cancer Wisconsin (Diagnostic) dataset from the Suggested Datasets document for my AML-BASIC project. The dataset contains 569 samples, each with 30 nuclear features (e.g., radius, texture) derived from FNA biopsies

# Key Challenges #

>Feature engineering for derived indicators (mean, standard error, worst values, etc.)

>Addressing class imbalance (357 benign vs 212 malignant samples)

# Workflow Overview

This version integrates a complete workflow covering hypothesis, EDA, baseline comparison, model building, and result interpretation. The report now uses Markdown + code blocks for clarity and readability.

# Major Updates:

Baseline Model Introduction

Added a DummyClassifier as a benchmark.

Accuracy comparison: ~63% (Dummy) vs ~97% (Logistic Regression).

# Enhanced Exploratory Data Analysis & Preprocessing

Visualized feature distributions, class imbalance, and correlation heatmaps.

Automatically removed highly correlated features (corr > 0.9) to reduce multicollinearity.

# Refined Report Structure

Clear modular format: Markdown explanations + code + interpretation.

# Expanded Results & Discussion

Discussed limitations, risks, and potential pipeline improvements.

Sets the stage for AML-Advanced projects.

# Additional Enhancements

Improved class imbalance handling

Stricter feature standardization

More comprehensive performance metrics

