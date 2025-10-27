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
* Model:  Random Forest Classifier, K-Neighbors Classifier, Support Vector Machine, Desicion Tree 
* Reason for selection: High performance, handles non-linearity, interpretable

## Evaluation Metrics

* Primary metric: ( Accuracy )

## Results

* Test accuracy: Random Forest Classifier:84% , K-Neighbors Classifier: 87%, Support Vector Machine:83%, Desicion Tree:79%

## Future Improvements


## How to Run

```bash
pip install -r requirements.txt
jupyter notebook "Heart Disease Prediction.ipynb"
```

## Author

* Name: Nakul Patel
* GitHub: [https://github.com/nakul8820/ML_Heart_Disease_project](https://github.com/nakul8820/ML_Heart_Disease_project)

