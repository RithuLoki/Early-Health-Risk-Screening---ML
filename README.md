# Early Health Risk Screening using Machine Learning (Non-Diagnostic)

## Project Overview
This project demonstrates how Machine Learning can be responsibly applied to **early health risk screening** using **non-clinical lifestyle data**.  
The goal is to identify **potential risk patterns** early, before serious health conditions develop.

This system is **non-diagnostic**, **non-clinical**, and intended **only for educational and preventive screening purposes**.

---

## Problem Statement
Preventive healthcare focuses on early awareness rather than late-stage treatment.  
Many health risks are influenced by lifestyle factors such as sleep, stress, physical activity, diet, and habits.

This project explores whether these basic indicators can be used to **screen potential health risks**, without making any medical diagnosis.

---

## Key Features
- Synthetic lifestyle dataset generation
- Exploratory Data Analysis (EDA)
- Rule-based risk scoring system
- Machine Learning models for risk classification
- Model comparison and evaluation
- Explainable ML using feature importance
- Interactive user interface for manual input
- Ethical and privacy-safe design

---

## Input Features
The model uses the following **non-clinical lifestyle factors**:
- Age
- Gender
- Diet quality score
- Exercise frequency
- Sleep duration
- Stress level
- Smoking status
- Alcohol consumption
- Body Mass Index (BMI)

All inputs are **privacy-safe** and do not involve medical records.

---

## Methodology
1. **Synthetic Data Generation**  
   Realistic lifestyle data is generated using controlled ranges and correlations.

2. **Exploratory Data Analysis (EDA)**  
   Data distributions, correlations, and risk trends are analyzed using visualizations.

3. **Rule-Based Risk Scoring**  
   A human-interpretable risk score is calculated based on lifestyle factors.

4. **Machine Learning Models**
   - Logistic Regression
   - Random Forest
   - Gradient Boosting

5. **Model Evaluation**
   Models are evaluated using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - ROC-AUC Score

6. **Explainability**
   Feature importance is used to understand which lifestyle factors influence risk predictions.

7. **Interactive Risk Assessment Tool**
   Users can manually input values using sliders and dropdowns to receive:
   - Risk category
   - Risk probability
   - Personalized lifestyle suggestions

---

## Results Summary
- Logistic Regression achieved the best overall performance.
- Strong correlation observed between rule-based risk score and ML predictions.
- Lifestyle factors such as stress, age, BMI, and smoking status showed high influence.

---

## Ethical Considerations
- Uses **synthetic data only**
- No personal or medical records involved
- Outputs are **not medical advice**
- Designed for awareness and education
- Explicitly non-diagnostic

---

## Future Scope
- Validation using anonymized real-world datasets
- Time-series tracking of lifestyle changes
- Integration with wearable data
- Preventive health analytics at policy level

---

## How to Run the Project
1. Open the notebook in Google Colab or Jupyter Notebook
2. Run all cells sequentially from top to bottom
3. Use the interactive sliders to test different lifestyle inputs

### Note on Interactive Interface

The interactive components of this project are intended for **local execution or Google Colab** only.  
They are not executed in the GitHub preview to ensure reproducibility and avoid rendering issues.

---

## Conclusion
This project showcases a responsible, interpretable, and ethical application of Machine Learning for early health risk screening using lifestyle data.  
It highlights how AI can support preventive healthcare without replacing professional medical judgment.

---

## Author
**Rithikaa V**  
B.Tech – Information Technology
