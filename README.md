# Diabetes Prediction using Machine Learning

## 📌 Project Overview
This project is a Machine Learning-based Diabetes Prediction System developed using Python and Scikit-learn. The model predicts whether a person is diabetic or non-diabetic based on medical attributes from the PIMA Indians Diabetes Dataset.

The project demonstrates the complete machine learning workflow including:
- Data Collection
- Data Preprocessing
- Feature Scaling
- Model Training
- Model Evaluation
- Prediction System

---

## 🚀 Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn

---

## 📂 Dataset Used

The project uses the **PIMA Indians Diabetes Dataset** which contains medical diagnostic data of patients.

### Features in Dataset
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target Variable
- Outcome
  - 0 → Non-Diabetic
  - 1 → Diabetic

---

## 🧠 Machine Learning Algorithm

The model uses:

### Support Vector Machine (SVM)

SVM is a supervised machine learning algorithm used for classification problems. It analyzes patient health parameters and predicts whether the person is diabetic or not.

---

## ⚙️ Project Workflow

1. Importing Dependencies
2. Loading Dataset
3. Data Analysis
4. Data Standardization
5. Splitting Training and Testing Data
6. Training the SVM Model
7. Evaluating Model Accuracy
8. Building a Predictive System

---

## 📊 Libraries Used

```python
import numpy as np
import pandas as pd
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn import svm
from sklearn.metrics import accuracy_score
