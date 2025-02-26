Heart Disease Prediction 

This project focuses on predicting the risk of heart disease using machine learning techniques. The dataset consists of clinical variables such as age, blood pressure (BP), cholesterol levels, maximum heart rate, chest pain type, and exercise-induced angina. The primary goal is to develop a predictive model that can assist in early diagnosis and medical decision-making.

Kaggle Dataset: Predicting Heart Disease Risk (https://www.kaggle.com/datasets/thedevastator/predicting-heart-disease-risk-using-clinical-var)

Data Analysis & Preprocessing
Exploratory Data Analysis (EDA): Identified feature distributions using histograms and box plots, highlighting key trends and potential outliers.
Correlation Analysis: Showed that features like maximum heart rate and chest pain type strongly correlate with heart disease.

Model Development & Evaluation
Implemented Logistic Regression and Decision Tree classifiers to predict heart disease.
Performance Metrics:
  Logistic Regression achieved 85.18% accuracy, with a high recall of 92% for heart disease cases.
  Decision Tree performed slightly worse, with more false positives and negatives.
Confusion Matrices Analysis:
  Logistic Regression demonstrated better predictive balance.
  Decision Tree had a higher false positive rate, indicating potential overfitting.

Key Findings & Conclusion
Logistic Regression outperformed the Decision Tree model in terms of accuracy and stability.
Max Heart Rate and Chest Pain Type were the most influential features in predicting heart disease.
Exercise-Induced Angina had a significant correlation with the presence of heart disease.
