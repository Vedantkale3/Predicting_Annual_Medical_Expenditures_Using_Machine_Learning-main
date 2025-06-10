# Predicting Annual Medical Expenditures Using Machine Learning

This project focuses on building a predictive model to estimate the **annual medical charges** of a customer based on their personal and lifestyle attributes. It is intended to support health insurance companies in setting fair and accurate premiums.

## 👨‍💻 Student Information

- **Name:** Shehjad Shabbir Sayyad  
- **College:** Pimpri Chinchwad University  
- **Department:** CSE (AI & ML)  
- **Email:** shehjad.sayyad05@gmail.com  
- **AICTE Student ID:** STU673700317ab281731657777

---

## 📌 Problem Statement

ACME Insurance Inc. needs a reliable system to estimate the annual medical expenses of new customers using basic data such as:
- Age
- Gender
- BMI
- Number of children
- Smoking status
- Region of residence

---

## ✅ Proposed Solution

The system leverages **Machine Learning regression algorithms** to predict annual medical expenses. It uses:
- Historical insurance data (from Kaggle)
- Data preprocessing and feature encoding
- Two ML models: **Linear Regression** and **Random Forest Regressor**
- RMSE (Root Mean Squared Error) for evaluation

---

## 🛠️ Technologies & Tools

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn**

---

## 🔍 Features Used

- `age`
- `bmi`
- `children`
- `sex_code` (encoded gender)
- `smoker_code` (encoded smoking status)
- One-hot encoded regions: `northeast`, `northwest`, `southeast`, `southwest`

---

## 📊 Model Evaluation

| Model              | RMSE Score |
|--------------------|------------|
| Linear Regression  | ~6180.24   |
| Random Forest Regressor | ~4602.75   |

> Random Forest performs better due to its ability to capture non-linear relationships.

---

## 🧪 Sample Prediction

**Input:**  
- 19 years old  
- BMI: 24  
- 0 children  
- Non-smoker  
- Female  
- Region: Southwest

**Predicted Charge:** `$1759.61`

---

## 📈 Visual Results

- Actual vs Predicted Charge (scatter plot)
- Feature Importance (Random Forest)

---

## 🚀 Future Scope

- Include medical history, income, and habits for better accuracy
- Deploy using Flask or Streamlit as a web app
- Try advanced models like Gradient Boosting or Neural Networks
- Real-time prediction on mobile or agent dashboards

---

## 📚 References

- Dataset: [Kaggle Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Course: Machine Learning with Python – Coursera by Andrew Ng

---

## 📎 Project Files

- `python_sklearn_regression.ipynb` - Full notebook
- `presentation.pptx` - Final output presentation
