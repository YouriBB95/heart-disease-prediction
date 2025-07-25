# 🫀 Heart Disease Prediction

This project predicts the likelihood of heart disease based on patient data using Logistic Regression, Decision Tree, and Random Forest classifiers.

## 📊 Project Summary

- Cleaned and preprocessed healthcare data
- Replaced invalid (zero) values for Cholesterol and RestingBP with the median
- One-hot encoded categorical features
- Trained and evaluated 3 classification models
- Tuned the Random Forest using GridSearchCV
- Analyzed feature importance to interpret model decisions

## ✅ Model Comparison

| Model              | Accuracy | F1-score (1) | ROC AUC |
|--------------------|----------|--------------|---------|
| Logistic Regression | 0.89     | 0.90         | 0.933   |
| Decision Tree       | 0.78     | 0.80         | 0.773   |
| Random Forest       | 0.88     | 0.89         | 0.933   |
| **Tuned RF**        | 0.86     | 0.88         | 0.930   |

## 📌 Top Features (Random Forest)

- **ST Slope (Up/Flat)** – Key indicator of heart function from ECG
- **MaxHR** – Max heart rate during a stress test
- These features match known clinical indicators of heart disease risk

## 📁 Files

- `heart_disease_prediction.ipynb` – Full notebook
- `requirements.txt` – Python packages used

## 🔗 Links

- 📂 [Dataset (Kaggle)](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
