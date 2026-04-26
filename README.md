# Assessment 4 — Machine Learning

## Overview

This repository contains solutions for Assessment 4, covering supervised learning, unsupervised learning, feature engineering, and a business case analysis based on a fashion retail promotion effectiveness scenario.

---

## Repository Structure

```
├── part_a/
│   ├── q1_supervised.ipynb           # Heart Disease Classification
│   ├── q2_unsupervised.ipynb         # Customer Segmentation
│   └── q3_feature_engineering.ipynb  # Retail Sales Regression Pipeline
│
├── part_b/
│   └── business_analysis.md          # Business Case Analysis
│
├── data/                             # Place datasets here (not included in repo)
│   ├── q1_heart_disease.csv
│   ├── q2_customers.csv
│   └── q3_retail_promotions.csv
│
└── README.md
```

---

## Setup Instructions

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd <repo-folder>
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Add the datasets
Place the provided CSV files into the `data/` folder:
- `data/q1_heart_disease.csv`
- `data/q2_customers.csv`
- `data/q3_retail_promotions.csv`

### 4. Run the notebooks
```bash
jupyter notebook
```
Open each notebook from the `part_a/` folder and run all cells.

---

## Part A — Notebooks Summary

### Q1: Supervised Learning — Heart Disease Classification
- **Dataset:** `q1_heart_disease.csv` (800 rows, 12 features)
- **Goal:** Predict presence of heart disease using classification models
- **Models:** Decision Tree, Random Forest, Gradient Boosting
- **Key steps:** EDA, median imputation, one-hot encoding, stratified split, GridSearchCV tuning

### Q2: Unsupervised Learning — Customer Segmentation
- **Dataset:** `q2_customers.csv` (500 rows, 6 features)
- **Goal:** Segment customers into meaningful groups using K-Means clustering
- **Key steps:** StandardScaler, Elbow method (K=4), PCA for 2D visualisation, cluster interpretation

### Q3: Feature Engineering — Retail Sales Regression
- **Dataset:** `q3_retail_promotions.csv` (1200 rows, 9 features)
- **Goal:** Predict items sold using a regression pipeline with engineered date features
- **Models:** Linear Regression, Random Forest Regressor
- **Key steps:** Date feature extraction, temporal train-test split, ColumnTransformer pipeline, feature importance

---

## Part B — Business Case Analysis

A written analysis covering:
- ML problem formulation for promotion effectiveness
- Data joining strategy and EDA approach
- Model evaluation setup and metrics
- Deployment, monitoring, and retraining strategy

---

## Dependencies

| Library | Version |
|---|---|
| Python | 3.12+ |
| pandas | latest |
| numpy | latest |
| scikit-learn | latest |
| matplotlib | latest |
| seaborn | latest |
| jupyter | latest |

---


