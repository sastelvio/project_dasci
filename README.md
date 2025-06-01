# 🦠 Dengue Data Analysis – Descriptive Statistics & Predictive Modeling

## 📚 Academic Project – Data Science & Public Health

This repository contains an academic project developed as part of a collaborative coursework assignment in A Journey to Data Scientist. The study focuses on **descriptive and predictive analysis** of dengue fever cases in Brazil using a large public dataset provided by the Brazilian Ministry of Health.

> ⚠️ **Note:** This project was created in collaboration with fellow students for educational purposes. It is not intended for direct clinical or governmental application without further validation.

---

## 🧾 Project Overview

Dengue is a major public health concern in Brazil, with over 8 million cases reported between 2012 and 2021. This project aims to explore patterns, risk factors, and geographic disparities associated with dengue, and to propose data-driven solutions to improve prevention and resource allocation strategies.

---

## 📌 Objectives

The main goals of this project are to:

- Conduct an exploratory analysis of a comprehensive dengue dataset
- Identify sociodemographic and clinical risk factors
- Segment regions by vulnerability
- Detect correlations in the data
- Transform real-world health challenges into **machine learning tasks**

---

## 🧩 Dataset

- **Source:** SINAN (Sistema de Informação de Agravos de Notificação) – Brazilian Ministry of Health
- **Access:** [Mendeley Data – Arbovirus Clinical Data, Brazil, 2013–2020](https://doi.org/10.17632/2d3kr8zynf.2)
- **Years covered:** 2013–2020
- **Scope:** Dengue and Chikungunya cases (this project uses only dengue cases)
- **Size:** ~6.7 million records, 56 variables

The dataset includes demographic, clinical, geographic, and temporal attributes, such as:

- Age, sex, education level, ethnicity
- Symptoms, comorbidities, hospitalization status
- Dates of symptom onset and case closure
- Geographic location (municipality, district, state)

---

## 🧪 Methodology

### 🔍 Data Preparation & Cleaning

- Filtering only dengue cases
- Handling missing/incomplete data using imputation strategies
- Creating new derived variables (e.g., evolution time, symptom counts)
- Normalizing and correcting inconsistent date formats
- Resolving geographical gaps using external reference datasets

### 📊 Exploratory Data Analysis (EDA)

- Profiling with **YData Profiling**
- Correlation analysis using **PhiK**, a method suited for categorical and nonlinear relationships
- Identification of patterns in race, age, education, symptoms, and outcomes

---

## ❓ Problem Statements

| Problem | ML Task | Objective | Suggested Models |
|--------|---------|-----------|------------------|
| **Geographic segmentation** | Clustering | Identify high-risk regions | K-Means, DBSCAN |
| **Risk factor identification** | Classification | Predict severe dengue risk | XGBoost |
| **Seasonal epidemic forecasting** | Time Series | Predict peaks | SARIMA, LSTM |
| **Education level & prevention** | Regression | Evaluate policy effectiveness | Linear/Logistic Regression, Random Forest Regression |

---

## 🧮 Evaluation Metrics

| Task | Metrics |
|------|---------|
| **Classification** | Accuracy, Recall, F1-Score, AUC-ROC |
| **Regression / Time Series** | MSE, R², Forecast plots |
| **Clustering** | Silhouette score, SSE, Davies-Bouldin, Calinski-Harabasz |

---

## 🧠 Tools & Technologies

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, Statsmodels)
- **YData Profiling**
- **PhiK correlation**
- **Jupyter Notebooks**
- **Git/GitHub** for version control

---

## 🏛️ Target Audience

This work is especially relevant for:

- **Public health decision-makers**: to design targeted interventions
- **Urban planners and municipalities**: for risk-aware infrastructure planning
- **Data scientists & researchers**: as a case study in health data analysis

---

## 💡 Key Insights

- There are correlations between race, education level, and clinical outcomes.
- Geographic and seasonal trends influence dengue spread.
- Machine learning models can help predict complications and outbreaks.
- Tailored health campaigns could be more effective based on educational level and location.

---

## 📚 References

1. Penna, M. L. F. (2003). *Um desafio para a saúde pública brasileira: o controle do dengue*. Cadernos De Saúde Pública. https://doi.org/10.1590/S0102-311X2003000100034
2. Oliveira et al. (2021). *Arbovirus clinical data, Brazil, 2013–2020*. Mendeley Data. [https://doi.org/10.17632/2d3kr8zynf.2](https://doi.org/10.17632/2d3kr8zynf.2)
3. Tejo et al. (2023). *Severe dengue in the intensive care unit*. Journal of Intensive Medicine. [[https://doi.org/10.17632/2d3kr8zynf.2](https://doi.org/10.17632/2d3kr8zynf.2)](https://doi.org/10.1016/j.jointm.2023.07.007)

---

## 📌 Disclaimer

This project is **purely academic** and part of a collaborative group effort. It does not contain real-time predictions and should not be used for clinical diagnosis or policy decisions without further scientific validation and support from public health authorities.
