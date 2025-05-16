# 📊 Principal Component Analysis (PCA) – Dimensionality Reduction

## 📌 Problem Statement

High-dimensional datasets often contain redundant features that increase computational cost, reduce model performance, and complicate visualization. **Principal Component Analysis (PCA)** is a statistical technique used to reduce the number of input variables in a dataset while preserving as much variance as possible.

This project demonstrates how to apply PCA to reduce dimensionality, interpret the results, and visualize transformed data effectively.

---

## 🎯 Objectives

- Understand and implement PCA from scratch and/or using `scikit-learn`.
- Reduce the dimensionality of a high-dimensional dataset.
- Visualize the variance explained by principal components.
- Compare original and reduced-dimension datasets using plots.
- Optionally: Use PCA-transformed data to improve model training speed and performance.

---

## 📚 Dataset Description

The dataset used includes multiple numeric features across various dimensions (e.g., cancer data, wine dataset, or synthetic high-dimensional data). It may contain:

- **Numerical Features**: Continuous attributes used for PCA transformation.
- **Target Variable** (if used for supervised learning after PCA): Class labels or regression targets.

---

## 🔬 What is PCA?

**Principal Component Analysis (PCA)** is a linear transformation technique that:

- Converts correlated features into a set of uncorrelated principal components.
- Orders components by the amount of original variance they explain.
- Enables dimensionality reduction while minimizing information loss.

---

## 🧪 Workflow

1. **Standardization**: 
   - Scaled the features using `StandardScaler` to ensure unit variance.
2. **Covariance Matrix Calculation**
3. **Eigen Decomposition**
   - Computed eigenvalues and eigenvectors.
4. **Explained Variance Plot**
   - Scree plot and cumulative variance graph.
5. **PCA Transformation**
   - Reduced data to 2D or 3D for visualization.
6. **Visualizations**
   - Plots of original vs. PCA-reduced space.
   - Biplots or scatterplots by class (if classification data used).
7. *(Optional)*: Applied PCA-transformed data to train a classification or regression model and compared results.

---

## ✅ Results

- PCA retained **X%** of the total variance using **n components**.
- Dimensionality reduced from **original n features** to **k components**.
- PCA visualization showed clear separation/clustering for certain classes (if applicable).
- Optional model training (e.g., Logistic Regression, KNN) showed similar or better performance after dimensionality reduction with reduced complexity.

---

## 📈 Visualizations

- Scree Plot (Explained variance by each component)
- Cumulative Explained Variance
- 2D/3D Scatter Plot of PCA-transformed data
- Biplot with loading vectors (optional)

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebook)
- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`
- `Scikit-learn` (PCA, StandardScaler)

---
