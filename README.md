# Thyroid Cancer Recurrence Prediction Using Machine Learning

This project focuses on predicting thyroid cancer recurrence using machine learning techniques based on clinical and demographic patient data. Early prediction of recurrence can support clinicians in identifying high-risk patients and improving follow-up care.

---

## Problem Statement

Thyroid cancer generally has a good prognosis; however, recurrence remains a significant clinical challenge. Traditional prediction methods may fail to capture complex relationships among patient features. This project explores machine learning models to improve recurrence prediction accuracy.

---

## Objectives

- To preprocess and analyze thyroid cancer clinical data
- To build machine learning models for recurrence prediction
- To compare Logistic Regression and Random Forest models
- To identify important clinical features influencing recurrence

---

## Dataset Description

The dataset contains clinical and pathological information of thyroid cancer patients, including:

- Age, Gender
- Smoking and medical history
- Tumor staging (T, N, M)
- Risk level and treatment response

**Target Variable:**

- `Recurred` (0 = No recurrence, 1 = Recurrence)

---

## Tools & Technologies

- **Programming Language:** Python
- **Platform:** Google Colab
- **Libraries Used:**
    - pandas, numpy
    - matplotlib
    - scikit-learn

---

## Methodology

1. Data loading and inspection
2. Data cleaning and duplicate removal
3. Categorical encoding
4. Missing value handling using median imputation
5. Train-test split
6. Model training
7. Model evaluation
8. Feature importance analysis

---

## Machine Learning Models

- **Logistic Regression**
    
    Used as a baseline classification model.
    
- **Random Forest Classifier**
    
    Used to capture non-linear relationships and improve predictive performance.
    

---

## Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

Special emphasis was placed on **recall**, as identifying recurrence cases is critical in medical diagnosis.

### Key Results (Random Forest):

- **Accuracy:** 93.15%
- **Recall (Recurrence):** 95%

---

## Feature Importance

Feature importance analysis revealed that the following features had the greatest influence on recurrence prediction:

- Treatment response
- Risk level
- Tumor stage (T)
- Age

---

## Conclusion

The results demonstrate that machine learning, particularly Random Forest, can effectively predict thyroid cancer recurrence with high accuracy and recall. The model highlights clinically relevant features and can serve as a decision-support tool in healthcare settings.

---

## Future Scope

- Use of larger, multi-center datasets
- Application of advanced ML or deep learning models
- Integration of medical imaging data
- Deployment as a real-time clinical decision support system
- Use of explainable AI techniques (SHAP, LIME)

---

## Project Links

- **Google Colab Notebook:***(*https://colab.research.google.com/drive/1KjK7tNgQxqbJfYC3Bxu_z1Xw6m_f9Jm6?usp=sharing)
- **GitHub Repository:** *(This repository)*

---

## Author

Irtika.
