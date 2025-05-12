
# **Heart Disease Prediction Using R**

## **Project Overview**
This academic project explores the influence of clinical and social behavioral factors on the incidence of heart diseases. It focuses on how healthcare professionals can leverage predictive analytics to apply targeted interventions and influence public health policies.

---

## **Technologies Used**
- R Programming  
- Statistical Libraries: `dplyr`, `ggplot2`, `stats`  
- PowerPoint for Final Presentation

---

## **Dataset Description**
- **Source:** Kaggle Heart Disease Dataset  
- **Key Features:**  
  - Demographics: Age, Sex  
  - Clinical Indicators: Chest Pain Type (CP), Resting Blood Pressure (Trestbps), Cholesterol, Max Heart Rate  
  - Lifestyle and Social Determinants: Smoking, Socioeconomic Status  

- **Target Variable:** Presence or Absence of Heart Disease (Binary)

---

## **Methodology**
- **Data Cleaning:**  
  - Handled missing values.  
  - Removed outliers using the IQR method.  

- **Statistical Tests:**  
  - Shapiro-Wilk Test for Normality  
  - t-tests and Welch’s t-test to compare cholesterol between heart disease groups  
  - ANOVA and Tukey’s HSD for pairwise analysis  

- **Predictive Modeling:**  
  - Logistic Regression Model  
  - Model Evaluation:  
    - Metrics Used: AIC, BIC, Accuracy, Sensitivity, Specificity, Kappa Score  

---

## **Key Findings**
- Strong predictors of heart disease include:
  - Cholesterol Levels  
  - Age  
  - Chest Pain Type  

- Males and middle-aged individuals exhibited higher risk patterns.  
- Significant interplay found between social determinants and clinical measures in predicting heart disease.

---

## **Future Enhancements**
- Integrate advanced machine learning models (e.g., Random Forest, XGBoost) for comparison.  
- Explore more complex interactions between variables using multivariate analysis.  
- Investigate longitudinal data to study heart disease progression over time.

---
