# 🫀 Heart Disease Prediction

## 📌 Project Overview

This project aims to predict the presence of heart disease using machine learning models.
By analyzing patient health data, the model can classify whether a person is likely to have heart disease.

---

## 🧰 Tools & Libraries

* Python 🐍
* Pandas
* NumPy
* Seaborn & Matplotlib
* Scikit-learn
* KaggleHub

---

## 📊 Dataset

The dataset includes medical attributes such as:

* Age
* Sex
* Chest Pain Type (cp)
* Cholesterol (chol)
* Resting Blood Pressure (trestbps)
* Maximum Heart Rate (thalach)
* Target (0 = No Disease, 1 = Disease)

---

## 🔍 Data Analysis

* Data exploration using `info()` and `describe()`
* Correlation analysis using heatmap
* Visualization of relationships between features

---

## 🤖 Models Used

### 🔹 Logistic Regression

* Baseline classification model
* Simple and interpretable

### 🌲 Random Forest Classifier

* Handles complex relationships
* Provides feature importance

---

## 📈 Model Performance

### Logistic Regression

* Accuracy: **80.5%**

### Random Forest 🔥

* Accuracy: **98.0%**

👉 Random Forest significantly outperformed Logistic Regression by capturing non-linear patterns in the data.

---

## 📊 Evaluation Metrics

* Accuracy
* Confusion Matrix
* Precision, Recall, F1-score

---

## ⭐ Feature Importance

Random Forest was used to identify the most influential features.

> Chest pain type (cp) and maximum heart rate (thalach) were among the most important features in predicting heart disease.

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
```

3. Run all cells step by step

---

## 💡 Future Improvements

* Apply Cross Validation
* Hyperparameter tuning
* Try advanced models (XGBoost, SVM)
* Deploy as a web application

---

## 👨‍💻 Author

* abdullahf-77
