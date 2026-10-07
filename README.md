# GCI World Competition — Matsuo-Iwasawa Lab (U-Tokyo)

This repository contains my solution and model pipeline for the final competition in **The University of Tokyo's Matsuo-Iwasawa Laboratory GCI World Program** (April Cohort).

## 📌 Project Overview
- **Goal:** Binary classification model predicting draft status (`1 = Drafted`, `0 = Not Drafted`), based on structured datasets provided in the GCI competition benchmark.
- **Features:** Physical performance metrics (40-yard dash, vertical jump, bench press, etc.) and player position categories.
- **Evaluation Metric:** ROC-AUC, Accuracy
- **Key Techniques:** Data Preprocessing, Feature Engineering, Gradient Boosting, Cross-Validation.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn, LightGBM / XGBoost, RandomForest, Seaborn

## 🚀 Key Pipeline Steps
1. **Data Preprocessing & Exploratory Data Analysis (EDA):** Identified missing values, distributions, and feature correlations.
2. **Feature Engineering:** Extracted interactions, encoded categorical variables, and handled outliers.
3. **Modeling & Validation:** Implemented stratified K-Fold cross-validation and hyperparameter tuning using Optuna / GridSearch.
4. **Results:** Achieved a top-tier metric score on the evaluation leaderboard.

## 📁 Repository Structure
```Learning materials are not to be disclosed; therefore, I'm only sharing the insights and paths of the project.
├── data/              # Dataset directory (gitignored)
├── notebooks/         # Exploratory analysis & experiments
├── src/               # Data cleaning, feature engineering, and model scripts
└── README.md
