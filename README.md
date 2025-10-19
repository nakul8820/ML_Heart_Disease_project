# Heart Disease Prediction Project

## Overview 🚀
```
This project predicts the likelihood of heart disease using machine learning techniques.

| 🧾 Section      | 📌 Details                                                                                                     |
| --------------- | -------------------------------------------------------------------------------------------------------------- |
| 👨‍💻 Author    | Nakul Patel                                                                                                    |
| 🗂️ GitHub Repo | [https://github.com/nakul8820/ML_Heart_Disease_project](https://github.com/nakul8820/ML_Heart_Disease_project) |
| 🎯 Goal         | Heart Disease Risk Prediction                                                                                  |
| 🛠️ Status      | In Progress (Modeling & Evaluation)                                                                            |
```
## Dataset 📊

* **Source:** UCI Heart Disease Dataset
* **Number of Records:** 303 patient records
* **Key Features Used:**

  * Age
  * Sex
  * Chest Pain Type (cp)
  * Resting Blood Pressure (trestbps)
  * Cholesterol (chol)
  * Fasting Blood Sugar (fbs)
  * Resting ECG Results (restecg)
  * Maximum Heart Rate Achieved (thalach)
  * Exercise-Induced Angina (exang)
  * ST Depression (oldpeak)
  * Slope of the Peak Exercise ST Segment (slope)
  * Number of Major Vessels (ca)
  * Thalassemia (thal)

## Feature Engineering 🧠
```
* ✅ Handled missing values (removed/filled using median strategy)
* 🔢 Encoded categorical variables using One-Hot Encoding
* 📏 Scaled numerical features using StandardScaler
* 🧪 Created derived features (e.g., cholesterol-to-age ratio for better risk insight)
* 🎯 Ensured balanced class distribution for target variable
 ```
## Model Used

* Model: (e.g., Random Forest, Logistic Regression, XGBoost)
* Reason for selection: High performance, handles non-linearity, interpretable

## Evaluation Metrics

* Primary metric: (e.g., F1-score / Accuracy / AUC-ROC)
* Cross-validation: (e.g., Stratified K-Fold)

## Results

* Training accuracy:
* Test accuracy:
* Observations: (e.g., no overfitting, model generalizes well)

## Future Improvements

* Hyperparameter tuning
* Model explainability using SHAP
* Deployment (Flask/FastAPI)

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook "Heart Disease Prediction.ipynb"
```

## Author

* Name: Nakul Patel
* GitHub: [https://github.com/nakul8820/ML_Heart_Disease_project](https://github.com/nakul8820/ML_Heart_Disease_project)

