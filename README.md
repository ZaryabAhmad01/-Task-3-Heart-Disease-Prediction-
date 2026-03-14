# Heart Disease Prediction - Task 3

## ❤️ Predicting Heart Disease Risk Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10.11-blue)
![Accuracy](https://img.shields.io/badge/Accuracy-98.5%25-brightgreen)
![AUC](https://img.shields.io/badge/AUC-0.999-success)

## 📋 Project Overview
Building classification models to predict heart disease risk using the UCI dataset. This is Task 3 of my internship program.

## 📊 Dataset
- **Source:** Heart Disease UCI Dataset
- **Records:** 1,025 patients
- **Features:** 12 medical attributes
- **Target:** Binary (0 = No disease, 1 = Disease present)

## 🛠️ Technologies
- Python, pandas, numpy
- scikit-learn, matplotlib, seaborn

## 🧠 Models Used
- Logistic Regression
- Decision Tree
- **Random Forest** (Best Performance)

## 📈 Results

| Model | Accuracy | False Positives | False Negatives |
|-------|----------|-----------------|-----------------|
| Logistic Regression | 78.54% | 26 | 18 |
| Decision Tree | 84.39% | 20 | 12 |
| **Random Forest** | **98.54%** | **0** | **3** |

### Random Forest Performance
- **Accuracy:** 98.54%
- **AUC Score:** 0.999
- **Precision:** 98.5%
- **Recall:** 98.5%
- **F1-Score:** 99%

### Confusion Matrix
```
[[102   0]
 [  3 100]]
```
- ✅ **Zero False Positives** - No healthy patients wrongly diagnosed
- ✅ **Only 3 False Negatives** - 97% of disease patients correctly identified

## 🔑 Key Insights
- Random Forest outperformed other models significantly
- Zero false positives is ideal for medical screening
- Near-perfect AUC (0.999) shows excellent discrimination ability

## ✅ Task Requirements Completed
- [x] Data cleaning & EDA
- [x] Feature encoding & scaling
- [x] Trained 3 classification models
- [x] Evaluated with accuracy, confusion matrix, ROC-AUC
- [x] Feature importance analysis
- [x] Model comparison

## 📌 Submission
| | |
|---|---|
| **Author** | DeveloperHC Intern |
| **Date** | March 2026 |
| **Best Model** | Random Forest |
| **Accuracy** | **98.54%** |

---

*For educational purposes only. Not for medical diagnosis.*


