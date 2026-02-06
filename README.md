**AI / ML Engineer – Predictive Model for Real-World Data**

**Problem Statement:**

**Health metrices**:  Heart Disease Prediction

**Problem Understanding**
Heart disease is one of the leading causes of mortality worldwide. Early detection plays a crucial role in reducing risk and improving patient outcomes.
The goal of this project is to build a machine learning model that predicts whether a person is at risk of heart disease based on historical health metrics such as age, blood pressure, cholesterol levels, fasting blood sugar, heart rate, and other clinical indicators.

The dataset used is a publicly available heart disease dataset, containing patient health records along with a target variable indicating the presence or absence of heart disease.
This problem falls under the health metrics scenario, as it involves analyzing medical and physiological data to predict a future health outcome.

The prediction task is a binary classification problem, where:

1 → Presence of heart disease

0 → No heart disease

The objective is not only to achieve good performance but also to understand feature importance, model behavior, and real-world interpretability, which is critical in healthcare-related applications.

**Dataset Feature Description**

age – Age of the patient in years.

sex – Gender of the patient (1 = male, 0 = female).

cp – Type of chest pain experienced by the patient.

trestbps – Resting blood pressure measured in mm Hg.

chol – Serum cholesterol level in mg/dl.

fbs – Fasting blood sugar level (1 if >120 mg/dl, else 0).

restecg – Resting electrocardiographic results.

thalach – Maximum heart rate achieved during exercise.

exang – Exercise-induced angina (1 = yes, 0 = no).

oldpeak – ST depression induced by exercise relative to rest.

slope – Slope of the peak exercise ST segment.

ca – Number of major blood vessels colored by fluoroscopy.

thal – Thalassemia condition of the patient.

target – Indicates presence (1) or absence (0) of heart disease.

**Programming Language:**  Python

**Libraries:**

o	NumPy

o	Pandas

o	Matplotlib

o	Seaborn

o	Scikit-learn

**Model Pipeline Description:**

**1. Data Preprocessing:**

Checked for missing values and handled them using mean/median imputation.

Converted categorical features (such as chest pain type, ECG results) into numerical format using encoding.

Feature scaling was applied where required (especially for Logistic Regression).

Dataset was split into training and testing sets to evaluate generalization.

**2.Exploratory Data Analysis (EDA):**

Visualized relationships between features and the target variable

Used bar plots and count plots to understand categorical feature impat

Identified important patterns and trends in the data

**3. Model Selection & Training:**

Two models were selected to compare performance and reasoning:

**Logistic Regression:**

Simple, interpretable baseline model.

Helps understand how individual features influence prediction.

Suitable for binary classification problems.

**Random Forest Classifier:**

An ensemble learning model capable of handling non-linear relationships.

Reduces overfitting by averaging multiple decision trees.

Provides feature importance for better inference.

Both models were trained on the same processed dataset for fair comparison.

**Results & Evaluation Metrics:**

The models were evaluated using the following metrics:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

**Inference & Model Explanation:**

Features like age, cholesterol, resting blood pressure, and maximum heart rate were found to be strong predictors.

Logistic Regression coefficients explain the direction of influence of each feature.

Random Forest feature importance highlights which health indicators contribute most to predictions.

The model can assist doctors as a decision-support tool, not a replacement, by identifying high-risk patients early.
        
**Results & Observations:**

Logistic Regression performed well as a baseline model

Random Forest captured complex patterns and achieved better overall performance

Feature importance analysis showed which medical factors contribute most to heart disease prediction


**Conclusion:**

This project demonstrates how machine learning can be effectively applied in the healthcare domain to predict heart disease. Using both Logistic Regression and Random Forest ensured a balance between model interpretability and prediction accuracy.


