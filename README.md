# AIML-Project-RollNo-2024318
Heart Disease Prediction Using Logistic Regression
Problem Statement
Heart disease can be difficult to identify without examining relevant health indicators. A hospital wants a first-pass screening model that flags patients at higher risk of heart disease based on clinical measurements such as blood pressure, cholesterol, and heart rate.
Dataset
•	Name: Heart Disease Dataset
•	Source: Kaggle – johnsmith88
•	Link: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
•	Original Dataset: 1,025 rows, 14 columns
•	After Duplicate Removal: 302 rows, 14 columns
•	Target Variable: target (0 = No disease, 1 = Disease)
Tools Used
•	Python
•	Pandas, NumPy
•	Matplotlib, Seaborn
•	Scikit-learn
•	Google Colab
Workflow
1.	Data Collection: Imported the Heart Disease dataset from Kaggle.
2.	Data Cleaning: Checked missing values, identified and removed duplicate records, and inspected categorical values.
3.	Exploratory Data Analysis (EDA): Analysed target distribution, gender, chest pain types, correlations and maximum heart rate.
4.	Feature Engineering: Applied one-hot encoding to categorical features and StandardScaler to numerical features.
5.	Model Building: Trained a Logistic Regression classification model using an 80:20 train-test split.
6.	Evaluation: Evaluated the model using accuracy, precision, recall, F1-score, ROC-AUC and a confusion matrix.
7.	Insights: Examined Logistic Regression coefficients to identify influential features.
Results
•	Model: Logistic Regression
•	Accuracy: 85.25%
•	Precision: 87.50%
•	Recall: 84.85%
•	F1-score: 86.15%
•	ROC-AUC: 89.83%
Top Factors / Drivers:
•	Chest Pain Type: Categories cp_2 and cp_3 had the highest coefficient magnitudes.
•	Sex: Showed a strong contribution to the model's predictions.
•	Exercise-Induced Angina: Was among the important predictive features.
These factors are based on absolute Logistic Regression coefficients and indicate model associations, not causal relationships.
Screenshots
 
 
 

Future Improvements
•	Compare Logistic Regression with Random Forest and other classification algorithms.
•	Evaluate the model using cross-validation and additional performance metrics.
•	Use a larger, well-documented dataset with verified patient records.
•	Explore model deployment through a simple web application.
Limitations
•	Duplicate removal reduced the dataset from 1,025 to 302 unique rows.
•	Some categorical values differ from the ranges stated in the dataset description.
•	The dataset may not represent the wider population.
•	The model is developed for educational purposes and is not intended for medical diagnosis.
Author
Lavi

