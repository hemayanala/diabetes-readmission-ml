# 🩺 Diabetes Readmission Prediction using Machine Learning

## Project Overview
Hospital readmissions among diabetic patients are costly and often preventable.  
This project focuses on predicting whether a diabetic patient will be **readmitted after discharge** using historical clinical and encounter-level data.

The project demonstrates an **end-to-end machine learning workflow**, including data exploration, preprocessing, feature engineering, model training, and evaluation using Python.

This work was completed as part of a graduate-level data analytics / machine learning course and is intended as a **portfolio project**.

---

## Problem Statement
Given patient encounter data, predict whether a diabetic patient will be readmitted.

**Task:** Binary classification  
**Target:** Readmitted vs. Not Readmitted

---

## Dataset
The dataset contains anonymized hospital encounter records for diabetic patients.

### Files Used
- `diabetic_data.csv` – Main dataset with patient demographics, diagnoses, medications, and encounter details  
- `features_diab.csv` – Feature descriptions and metadata  
- `IDS_mapping.csv` – Mapping file for encoded categorical values  

**Key characteristics**
- Real-world healthcare data
- Large number of categorical features
- Missing values and encoded medical codes requiring preprocessing

---

## Approach & Methodology

### 1. Exploratory Data Analysis (EDA)
- Examined class distribution and potential imbalance
- Analyzed patient demographics and encounter characteristics
- Identified missing values, outliers, and low-information features
- Visualized feature distributions and relationships

### 2. Data Preprocessing
- Handled missing and unknown values
- Mapped encoded categorical variables using metadata files
- Applied categorical encoding techniques
- Removed redundant or low-variance features
- Prepared final dataset for modeling

### 3. Modeling
The following supervised machine learning models were trained and compared:
- Logistic Regression (baseline)
- Random Forest Classifier
- Gradient Boosting Classifier

### 4. Evaluation
- Evaluated models using accuracy, precision, recall, and F1-score
- Used confusion matrices to analyze prediction performance
- Compared models to select the best-performing approach

---

## Results
- Tree-based models outperformed baseline logistic regression
- Random Forest and Gradient Boosting showed improved performance on readmission prediction
- Results highlight the importance of feature engineering and categorical handling in healthcare data
