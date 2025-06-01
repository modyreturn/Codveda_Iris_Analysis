# 🌸 Iris Dataset Analysis and Machine Learning

This project presents a comprehensive **data analysis** and **machine learning** workflow using the classic **Iris dataset**. The analysis includes **exploratory data analysis (EDA)**, **correlation analysis**, **linear regression modeling**, and **unsupervised clustering** using **k-means**.

---

## 📊 Project Overview

- **Dataset**: Iris dataset (150 samples, 4 features: sepal length, sepal width, petal length, petal width; target: species).
- **Objectives**:
  - Explore data distributions.
  - Identify feature correlations.
  - Build and evaluate a linear regression model.
  - Apply k-means clustering and evaluate its effectiveness.

---

## ✅ Key Analyses & Findings

### 1. Exploratory Data Analysis (EDA)
- Boxplots revealed distinct feature distributions across species.
- **Petal features** provided better separation between species compared to sepal features.
- **Setosa** stood out with small petal dimensions, while **Versicolor** and **Virginica** showed some overlap.

### 2. Correlation Analysis
- Strong positive correlation between **sepal and petal dimensions**.
- Scatter plots visualized these relationships effectively.

### 3. Regression Modeling
- Built a **linear regression** model to predict **petal length** from **sepal length**.
- Evaluation through residuals and predicted vs actual plots indicated reasonable model performance.
- Some heteroscedasticity observed, suggesting potential for non-linear models.

### 4. Clustering Analysis
- Utilized **k-means clustering** for unsupervised learning.
- **Elbow method** and **silhouette analysis** identified **k=3** as optimal, matching the actual number of species.
- Visual comparison showed good clustering performance, especially for **Setosa**; some overlap for **Versicolor** and **Virginica**.

---

## 🔧 Technologies Used

- **Python**
- **Pandas** for data manipulation
- **Seaborn** and **Matplotlib** for visualization
- **Scikit-learn** for regression, clustering, and evaluation metrics

---
