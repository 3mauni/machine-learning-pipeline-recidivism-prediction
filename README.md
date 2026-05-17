# Machine Learning Pipeline — Recidivism Prediction

## Project Overview
This project implements an end-to-end machine learning pipeline for recidivism prediction using Python and modern ML frameworks.

The pipeline includes:

- Data preprocessing
- Feature engineering
- Logistic Regression
- Random Forest Classification
- Neural Network using TensorFlow/Keras
- SHAP Explainability
- Fairlearn Bias/Fairness Evaluation
- Confusion Matrix Visualization
- Performance Evaluation Metrics

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- SHAP
- Fairlearn
- Matplotlib
- Seaborn

---

## ML Models Implemented

### Logistic Regression
- Accuracy: 72.6%
- F1 Score: 77.2%

### Neural Network
- Accuracy: 73.2%
- F1 Score: 77.5%

### Random Forest
- Feature importance analysis using SHAP

---

## Explainable AI (XAI)

Implemented SHAP explainability to identify the most influential features impacting prediction outcomes.

Top influencing features included:
- Percent_Days_Employed
- Gang_Affiliated
- Supervision_Risk_Score
- Jobs_Per_Year

---

## Fairness Analysis

Used Fairlearn to evaluate prediction fairness across demographic groups.

Example fairness evaluation:
- BLACK accuracy: 71.9%
- WHITE accuracy: 74.0%

---

## Visualizations

- Confusion Matrix
- SHAP Summary Plot
- Feature Importance Analysis

---

## Repository Structure

```bash
data/
models/
notebooks/
outputs/
README.md
requirements.txt
