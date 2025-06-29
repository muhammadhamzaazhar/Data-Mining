# 🌤️ Houston Weather Analysis: Clustering & Outlier Detection

This repository contains two assignments focused on applying unsupervised learning techniques and performing exploratory data analysis (EDA) on the **Houston Weather Dataset (HWD)**. The goal is to extract insights from weather patterns in Houston using clustering, outlier detection, and visualization techniques.

---

## 📈 Assignment 1: Exploratory Data Analysis (EDA)

### EDA Objectives
- Data cleaning & preprocessing
- Summary statistics for all attributes
- Distribution plots and trend visualizations
- Pairwise relationships (e.g., humidity vs temperature)
- Prepared dataset for clustering & outlier tasks

### Visualizations
- Histograms & Boxplots
- Correlation heatmaps
- Line graphs for temporal weather patterns
- Scatter plots with class overlays

### Learning Outcomes

- Applied unsupervised learning algorithms in real-world data
- Evaluated clustering quality and interpretability
- Designed and implemented custom outlier detection logic
- Conducted complete exploratory data analysis pipeline

---

## 📊 Assignment 2: Clustering & Outlier Detection

### Task 1: Clustering

#### K-Means Clustering
- Applied with `k=3`
- Evaluated using:
  - **Purity Score** (with actual `class` labels)
  - **SSE (Sum of Squared Errors)**
  - **Boxplots** of each cluster
  - **Cluster Centroids** and summaries

#### DBSCAN Clustering
- Hyperparameter tuning to yield 2–15 clusters and <20% noise
- Comparison with K-Means using:
  - **Purity Score**
  - **Cluster shapes**
  - **Noise points**

### Task 2: Outlier Detection

#### Dataset
- Refined subset: `RHOUSTONW` (data from 2021)

#### Techniques Applied
- **Distance-Based Outlier Detection**
- **Density-Based Outlier Detection**

#### Procedure
1. Implemented multivariate distance & density scoring functions
2. Applied each technique with **3 different hyperparameter settings**
3. Generated **Outlier Likelihood Score (OLS)** for every instance
4. Ranked the dataset:
   - Identified **Top 3 Outliers**
   - Identified **1 Most Normal** record
5. Compared detection techniques and interpretations

---
