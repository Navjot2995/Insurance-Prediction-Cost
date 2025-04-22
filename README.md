
# 🏥 Insurance Cost Prediction using Machine Learning

This project aims to build a predictive model that estimates health insurance costs based on an individual's demographic, lifestyle, and health history data. It uses a regression-based approach and compares various machine learning models for accuracy and performance.

---

## 📂 Dataset Description

The dataset includes 25,000 entries and 24 features related to:

- Demographics: Age, Gender, Location, Occupation
- Health Metrics: BMI, Glucose Level, Cholesterol, Heart/Other Disease History
- Lifestyle Factors: Smoking, Alcohol, Exercise, Adventure Sports, Steps
- Insurance History: Previous Insurers, Last Hospital Admission

**Target Variable**: `insurance_cost`

---

## 🧠 Project Goals

- Clean and preprocess real-world health insurance data
- Perform exploratory data analysis and correlation insights
- Train and evaluate multiple regression models
- Visualize feature importance and explore SHAP for interpretability

---

## ⚙️ Models Used

| Model                 | MAE       | RMSE      | R² Score |
|----------------------|-----------|-----------|----------|
| Linear Regression     | ✅ Baseline model |
| Random Forest Regressor | 🔥 Strongest performance |
| XGBoost               | ⚡ Fast & accurate |
| LightGBM              | *(Optional: install locally)* |

---

## 📊 Exploratory Data Analysis

- Correlation heatmaps
- Feature distribution analysis
- Impact of lifestyle choices (e.g., exercise/smoking) on cost

---

## 🔍 Feature Importance

- Age, BMI, Glucose, and Disease History are the most important predictors.
- SHAP values can be computed locally for deeper explainability.

---

## 🧾 Requirements

To run locally:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap
```

---

## 📁 Files Included

- `Insurance_Cost_Prediction_Notebook.ipynb` – Full notebook analysis
- `Data.csv` – Input data file (must be uploaded separately)
- `README.md` – Project documentation

---

## 🧠 Author

👤 Navjot Singh  
📬 navjot.python@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/navjot-singh-6a1012231)

---

## 📌 Notes

- This project is created as part of a machine learning learning track.
- SHAP visualizations are optional and suggested for local analysis due to system limitations.

---

