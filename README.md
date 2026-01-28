#  Medical Insurance Cost Predictor

> Hybrid Regression & Classification System for Healthcare Cost Forecasting

---

## Overview

The **Medical Insurance Cost Predictor** is a machine learning–based system developed to **accurately estimate individual medical insurance charges** and **classify customers into cost tiers** using demographic and health-related data.

The project addresses real-world challenges faced by insurance providers such as inaccurate cost forecasting, ineffective risk stratification, and lack of interpretability in traditional pricing systems.

This solution combines:

* **Exact cost prediction (regression)**
* **Cost-tier categorization (classification)**
* **Feature importance & correlation analysis**

making it suitable for insurance pricing, underwriting, and data-driven decision-making.

---

## Problem Statement

Insurance companies struggle with:

*  Imprecise forecasting of individual healthcare costs
*  Difficulty categorizing policyholders into risk-based cost segments
*  Limited interpretability of cost-driving factors

This project aims to bridge these gaps by developing a **scalable and highly accurate ML-based prediction framework**.

---

## Project Objectives

* Predict **exact medical insurance charges** using regression models
* Classify customers into **Low / Moderate / High cost tiers**
* Benchmark model performance using industry-standard metrics
* Analyze **feature importance and correlations**
* Deliver interpretable and actionable insights for insurers

---

## Dataset Information

The dataset consists of demographic and medical attributes commonly used in insurance analytics.

### Features

| Feature  | Description             |
| -------- | ----------------------- |
| Age      | Age of the policyholder |
| Sex      | Biological gender       |
| BMI      | Body Mass Index         |
| Children | Number of dependents    |
| Smoker   | Smoking status          |
| Region   | Residential region (US) |

### Targets

* **Charges** → Continuous insurance cost (Regression)
* **Cost Tier** → Low / Moderate / High (Classification)

---

## Data Preprocessing

A rigorous preprocessing pipeline was implemented:

* Data cleaning and missing-value handling
* Label encoding of categorical variables
* Feature scaling and normalization
* Exploratory Data Analysis (EDA)
* Train–test data splitting
* Cost-tier creation from continuous charges

This ensured consistent, noise-free, and model-ready input data.

---

## Machine Learning Models

### 🔹 Regression

**Decision Tree Regressor**

* Captures non-linear relationships
* High interpretability
* Strong performance on continuous targets

### Classification

**Random Forest Classifier**

* Ensemble-based architecture
* Reduced overfitting
* High generalization capability

---

## Model Performance

### Regression Results

| Metric       | Score      |
| ------------ | ---------- |
| **R² Score** | **0.9984** |
| **MAE**      | **0.0410** |
| **RMSE**     | **0.2799** |

---

### Classification Results

| Metric                | Score    |
| --------------------- | -------- |
| **Accuracy**          | **97%**  |
| **Macro F1 Score**    | **0.95** |
| **Weighted F1 Score** | **0.96** |
| **Precision (Avg.)**  | **0.96** |
| **Recall (Avg.)**     | **0.95** |


---

## Feature Importance & Insights

### Key Cost Drivers

The most influential features affecting insurance cost:

1. **Age**
2. **Number of Children**
3. **BMI**

### Correlation Analysis

* Smoking status shows strong positive correlation with charges
* Age and BMI significantly influence overall cost

These insights enhance transparency and support targeted insurance strategies.

## Authors

Aarushi Rawal

Sahaj Kapoor
