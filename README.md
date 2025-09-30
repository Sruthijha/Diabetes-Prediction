## 🩺 Diabetes Prediction System  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)  
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn)  
![LightGBM](https://img.shields.io/badge/LightGBM-Model-success?logo=lightgbm)  
![XGBoost](https://img.shields.io/badge/XGBoost-Compared-success?logo=xgboost)  
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)  

A machine learning project that predicts the likelihood of diabetes in patients based on health data.  
Built using the **Pima Indians Diabetes Dataset** and trained with multiple classifiers, with **LightGBM** chosen as the final model.  

---

## Features
- Data preprocessing (handling missing values, imputing, scaling where needed).  
- Trained & compared **Logistic Regression**, **Random Forest**, **XGBoost**, **AdaBoost**, and **LightGBM**.  
- Evaluated with **Accuracy, Recall, F1-score, ROC-AUC** (focus on Recall due to medical context).  
- Final model: **LightGBM (Accuracy ~78%, Recall ~67%)**.  
- Prediction function returns both **class (0/1)** and **probability of diabetes**.  
- Interactive **Streamlit web app** for user-friendly predictions.  

---

## Dataset
- **Source:** Pima Indians Diabetes Dataset  
- **Features (8):**  
  - Pregnancies  
  - Glucose  
  - Blood Pressure  
  - Skin Thickness  
  - Insulin  
  - BMI  
  - Diabetes Pedigree Function  
  - Age  
- **Target:** Outcome (0 = Not Diabetic, 1 = Diabetic)  

---
