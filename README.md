
Health metrices :  Heart Disease Prediction

Project Overview:
This project focuses on predicting whether a person has heart disease based on medical attributes such as age, sex, chest pain type, blood pressure, cholesterol levels, and other health indicators.
Heart disease is one of the leading causes of death worldwide. Early prediction can help doctors take preventive actions and improve patient outcomes. This project uses machine learning techniques to build an accurate and reliable prediction system.
Dataset Description
The dataset contains medical attributes related to heart health, such as:
•	Age
•	Sex
•	Chest pain type (cp)
•	Resting blood pressure (trestbps)
•	Cholesterol (chol)
•	Fasting blood sugar (fbs)
•	Resting ECG results (restecg)
•	Maximum heart rate achieved (thalach)
•	Exercise-induced angina (exang)
•	Target (0 = No heart disease, 1 = Heart disease)

Programming Language: Python
Libraries:
o	NumPy
o	Pandas
o	Matplotlib
o	Seaborn
o	Scikit-learn
Ml model Workflow:
Data Preprocessing
•	Loaded the dataset using Pandas
•	 Checked for missing values and data types
•	Performed basic data cleaning
•	Converted categorical features where necessary
•	Split the data into training and testing sets

 Exploratory Data Analysis (EDA)
•	Visualized relationships between features and the target variable
•	Used bar plots and count plots to understand categorical feature impact
•	Identified important patterns and trends in the data

Model Selection
Why Logistic Regression?
•	Logistic Regression is simple, fast, and easy to interpret
•	It works well for binary classification problems
•	Helps understand how each feature influences the prediction
•	Used as a baseline model to compare with advanced models
Why Random Forest?
•	Random Forest is an ensemble learning algorithm
•	Captures non-linear relationships between features
•	Handles feature interactions better than linear models
•	More robust to noise and overfitting
•	Often provides higher accuracy for complex datasets
Why use both models?
•	Logistic Regression provides interpretability
•	Random Forest provides better predictive performance
•	Comparing both helps make a data-driven model selection

Model Training
•	Trained both Logistic Regression and Random Forest models using the training dataset
•	Tuned parameters where required
•	Generated predictions on the test dataset

 Model Evaluation
The models were evaluated using:
•	Accuracy
•	Precision
•	Recall
•	F1-score
•	Confusion Matrix
These metrics help understand how well the model predicts heart disease and how reliable the predictions are.

 Results & Observations
•	Logistic Regression performed well as a baseline model
•	Random Forest captured complex patterns and achieved better overall performance
•	Feature importance analysis showed which medical factors contribute most to heart disease prediction

Conclusion
This project demonstrates how machine learning can be effectively applied in the healthcare domain to predict heart disease. Using both Logistic Regression and Random Forest ensured a balance between model interpretability and prediction accuracy.



