🩺 Diabetes Prediction System  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-Model-success?logo=xgboost)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)

A machine learning project that predicts the likelihood of diabetes in patients based on health data.  
Built using the **Pima Indians Diabetes Dataset** and trained with multiple classifiers, with **XGBoost** chosen as the final model.

---

## Features
- Data preprocessing (handling missing values, imputing, scaling where needed).
- Trained & compared **Logistic Regression**, **Random Forest**, and **XGBoost**.
- Evaluated with **Accuracy, Precision, Recall, F1-score, ROC-AUC**.
- Final model: **XGBoost (Recall ~72%, Accuracy ~75%)**.
- Prediction function returns both **class (Diabetic/Not Diabetic)** and **probability**.
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
   git clone https://github.com/your-username/diabetes-prediction-system.git
   cd diabetes-prediction-system
