# Student Performance Prediction using SHAP and LIME

## Project Objective

This project predicts student final performance using a Machine Learning model
and explains the prediction using Explainable AI techniques.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Random Forest
- SHAP
- LIME
- Matplotlib

## Dataset

UCI Student Performance Dataset.

The target variable is:

G3 = Final Student Grade

## Machine Learning Model

Random Forest Regressor is used to predict the student's final grade.

## Explainable AI

### SHAP

SHAP explains how individual features contribute to the prediction.

### LIME

LIME creates a local interpretable explanation for an individual prediction.

## Project Workflow

Dataset
→ Data Preprocessing
→ Feature Encoding
→ Train/Test Split
→ Random Forest
→ Student Performance Prediction
→ SHAP Explanation
→ LIME Explanation

## Results

The model is evaluated using:

- MAE
- RMSE
- R² Score

SHAP and LIME are used to understand why the model produced a
particular prediction.

## Google Colab

The complete implementation is available in:

`student_performance_xai.ipynb`

## GitHub Repository

https://github.com/bharath18092006/student-performance-xai
