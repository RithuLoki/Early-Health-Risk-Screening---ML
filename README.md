# 🩺 Early Health Risk Screening using Machine Learning (Non-Diagnostic)

## 📌 Project Overview
This project demonstrates how machine learning can be applied in a **responsible and ethical way** to support **early health risk screening** using basic lifestyle information.

The system is **non-diagnostic** and **non-clinical**. It is intended only for **educational and preventive awareness purposes** and does not replace professional medical advice.

All data used in this project is **synthetic**, ensuring privacy and academic safety.

---

## 🎯 Problem Statement
Many lifestyle-related health risks develop gradually and often remain unnoticed until they become serious.  
This project explores whether common lifestyle indicators—such as sleep, stress, diet, physical activity, and habits—can help **identify early risk patterns** before clinical intervention is required.

---

## 🧠 Approach
The project follows an end-to-end machine learning workflow:

- Synthetic data generation  
- Exploratory Data Analysis (EDA)  
- Rule-based risk scoring  
- Machine learning model training  
- Model evaluation and comparison  
- Explainability and interpretation  
- Interactive user interface for real-time screening  

---

## 🧾 Features Used
Only **non-medical and privacy-safe lifestyle inputs** were used:

- Age  
- Gender  
- Diet Quality  
- Exercise Frequency  
- Sleep Duration  
- Stress Level  
- Smoking Status  
- Alcohol Consumption  
- BMI  

These features are commonly associated with lifestyle-related health risks and are suitable for preventive screening.

---

## ⚙️ Machine Learning Models
The following supervised learning models were trained and evaluated:

- **Logistic Regression** (primary model)  
- Random Forest Classifier  
- Gradient Boosting Classifier  

Logistic Regression was selected as the final model due to its **good performance and high interpretability**, which is important for health-related applications.

---

## 📊 Model Evaluation
Models were evaluated using standard classification metrics:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC Score  

Special emphasis was placed on **recall**, as missing a high-risk individual is more critical than a false alert in preventive health screening.

---

## 🧠 Explainability
Explainability techniques were applied to understand which lifestyle factors contributed most to predicted risk levels.

This helps avoid black-box predictions and supports **transparent and responsible use of machine learning**.

---

## 🖥️ Interactive Health Risk Assessment Tool
An interactive interface built using `ipywidgets` allows users to:

- Enter lifestyle details manually  
- View predicted risk category (Low / Moderate or High)  
- Receive simple, non-clinical lifestyle suggestions  

This simulates a real-world preventive screening tool and improves user understanding.

---

## ⚠️ Ethical Disclaimer
- This system **does not diagnose diseases**
- Uses **synthetic data only**
- No real medical or patient records are involved
- Outputs are for **educational awareness**, not medical decisions

Users are encouraged to consult healthcare professionals for medical concerns.

---

## 🚀 Future Enhancements
Potential future improvements include:

- Validation using anonymized real-world datasets  
- Time-series tracking of lifestyle changes  
- Integration with wearable data (sleep and activity trends)  
- Preventive health analytics for public health and policy use  

---

## 👩‍💻 How I Built This
This project was developed step-by-step as follows:

1. Generated a synthetic dataset representing lifestyle factors  
2. Performed exploratory data analysis to understand feature behavior  
3. Designed a rule-based risk score as a baseline reference  
4. Preprocessed data using encoding and feature scaling  
5. Trained and evaluated multiple classification models  
6. Selected an interpretable model for final predictions  
7. Added explainability to understand model behavior  
8. Built an interactive interface for real-time risk assessment  
9. Included ethical safeguards and non-diagnostic disclaimers  

---
