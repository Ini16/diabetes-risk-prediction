[README_diabetes-risk-prediction.md](https://github.com/user-attachments/files/29746708/README_diabetes-risk-prediction.md)
# Diabetes Risk Prediction — Logistic Regression (R)

Predicting Type 2 diabetes risk from a health dataset of 500 patients (250 diabetic, 250 non-diabetic) drawn from a community-based study.

## What I did
- Explored and cleaned the data, then compared diabetic and non-diabetic groups using **descriptive statistics, independent-sample t-tests, and chi-square tests** to identify meaningful predictors.
- Built a **multiple logistic regression model**, removing variables that caused multicollinearity or quasi-separation to produce a stable final model.
- Evaluated model performance with an **ROC curve (AUC = 0.83)** and interpreted the results using odds ratios and confidence intervals.

## Key findings
- **Glucose** was the strongest predictor of diabetes (OR ≈ 1.32), followed by **BMI** (OR ≈ 1.13).
- The model performed well (AUC = 0.83), correctly separating diabetic from non-diabetic patients in most cases.

## Tools
R, tidyverse, logistic regression (`glm`), `pROC` / ROC analysis, ggplot2

## Files
- `diabetes_analysis.R` — analysis script
- `report.pdf` — full written report with tables and visualisations

## Note
Completed as part of my MSc (MATH515, Health Data and Medical Statistics) as a group coursework. This repository is shared with my groupmates' agreement.
