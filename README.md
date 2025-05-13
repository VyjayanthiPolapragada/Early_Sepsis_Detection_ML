# Early Sepsis Detection Using Machine Learning and Deep Learning Models

This project explores machine learning (ML) and deep learning (DL) approaches for early detection of sepsis, a life-threatening condition requiring timely intervention. Using clinical data from PhysioNet Sepsis Challenge 2019, MIMIC-IV Clinical Demo, and MIMIC-IV-ED Demo, we evaluate and compare models including Logistic Regression, Random Forest, XGBoost, LSTM, and a Stacking Ensemble (RF + LSTM)


## Datasets Used
**PhysioNet Sepsis Challenge 2019** – ICU time-series data for sepsis prediction.

**MIMIC-IV Clinical Demo** – Structured ICU patient data.

**MIMIC-IV-ED Demo** – Emergency Department data for early-stage identification.

All datasets are publicly available through PhysioNet under appropriate credentialed access.

## Methodology Overview
**Exploratory Data Analysis (EDA):** Handling missing values, class imbalance, feature distribution, correlation analysis.

**Preprocessing & Feature Engineering:** Rate of change features, time-window aggregation, normalization.

**Model Training & Evaluation:**

**Traditional ML models:** Logistic Regression, Random Forest, XGBoost

**Deep learning:** LSTM (with class weights)

**Ensemble:** Stacking Classifier (RF + LSTM)

## Metrics Used

Accuracy

Recall (TPR)

False Positive Rate (FPR)

ROC AUC

## Key Findings
**Stacking Classifier (RF + LSTM)** achieved the highest recall (87.69%) — crucial for medical diagnosis.

**LSTM (with class weights)** provided the best accuracy-recall balance.

Models trained on imbalanced data showed inflated accuracy but failed to detect true sepsis cases (low recall).
