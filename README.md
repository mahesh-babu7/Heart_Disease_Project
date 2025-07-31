# Heart Disease Analysis - Healthcare EDA Project
This project explores and analyzes a heart disease dataset using Python libraries such as Pandas, Seaborn, and Matplotlib. It aims to uncover trends and patterns related to heart disease risk factors based on clinical features.

📊 Project Overview
Objective
The goal is to perform Exploratory Data Analysis (EDA) on a heart disease dataset to identify key factors affecting the presence or absence of heart disease.

Dataset
The dataset contains 303 rows and 14 columns, with features such as:

age, sex, cp (chest pain type), trestbps (resting blood pressure), chol (cholesterol)

fbs (fasting blood sugar), restecg (resting ECG results), thalach (max heart rate)

exang (exercise-induced angina), oldpeak, slope, ca, thal, and target (disease presence: 1/0)

🔧 Tools and Technologies
Python 🐍

Pandas & NumPy (Data Handling)

Seaborn & Matplotlib (Data Visualization)

Jupyter Notebook (Interactive Analysis)

📈 Key Visualizations
Some of the visualizations included in the analysis:

Distribution plots (distplot) for numerical features like age, thalach, chol, oldpeak

Count plots for target analysis (target, sex, cp, fbs, exang)

Correlation Heatmap

KDE and Strip plots

Box plots for identifying outliers

Scatter plots with regression lines (e.g., age vs trestbps, chol vs thalach)

✅ Insights from EDA
Chest pain type (cp) and maximum heart rate (thalach) show strong positive correlation with heart disease.

Exercise-induced angina (exang) and ST depression (oldpeak) have negative correlation.

Males are more represented in the dataset, and they show a higher rate of heart disease.

Features like cholesterol and fasting blood sugar alone do not strongly indicate heart disease.

🧹 Data Quality
No missing values found.

All feature values are within valid ranges.

Data types verified and consistent.
