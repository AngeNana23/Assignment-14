# Assignment-14

# Ethical AI: Fairness and Explainability Project

## Overview
This project demonstrates how to build a machine learning model while ensuring **fairness and explainability**. It focuses on ethical AI principles using Logistic Regression, Fairlearn, SHAP, and LIME.

---

## Dataset
- Adult Income Dataset (public)
- Target: Income (>50K or <=50K)
- Sensitive attribute: Sex (gender)

---

## Steps

### 1. Data Preprocessing
- Removed missing values
- Selected features: age, education level, hours per week
- Encoded target variable

### 2. Model Training
- Logistic Regression model from scikit-learn
- Train-test split (80/20)

### 3. Evaluation
- Accuracy score
- Confusion matrix
- Classification report

---

## Fairness Analysis
- Used Fairlearn library
- Metrics:
  - Selection rate
  - True positive rate
  - False positive rate
- Compared performance across gender groups

---

## Explainability

### SHAP
- Global feature importance
- Local prediction explanation (waterfall plot)

### LIME
- Explains individual predictions in human-readable format

---

## Ethical Considerations
- Gender bias may exist in predictions
- Model may favor one group over another
- Sensitive attributes must be carefully analyzed
- Transparency is essential in real-world AI systems

---

## Recommendations
- Use more balanced datasets
- Apply bias mitigation techniques
- Test multiple fairness metrics
- Avoid using sensitive attributes in training

---

## How to Run
1. Open Google Colab
2. Upload notebook
3. Run all cells
4. Export as PDF for submission

---
