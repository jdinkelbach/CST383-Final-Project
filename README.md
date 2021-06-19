# CST383-Final-Project

## Introduction

For our final project, we worked on Kaggle’s Heart Attack Analysis & Prediction Dataset. Heart disease is the leading cause of death in the United States and it’s the cause of 1 out of every 4 deaths. (Thomas) The objective of this project was to utilize patient data to classify the likelihood an individual has heart disease. Although heart disease is complex, understanding contributing signs can further understand and aid in risk mitigation.

## Selection of Data

The source of our dataset came from kaggle. In this dataset, we have different columns that represent age, sex, exercise induced angina, number of major vessels, chest pain type, resting blood pressure, cholesterol fetched via BMI sensor, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, target of heart attack. They are all related to heart attack analysis. Our data includes 304 rows for the record. 

We added a heart disease for our feature engineering. We dropped all but age, cholesterol, maximum heart rate achieved, oldpeak, sex, exercise induced angina, and slope.

## Methods

Tools:
  - Numpy, Pandas, Matplotlib, and Seaborn (Data Visualization)
  - Scikit-learn for inference
  - Git for version control
  - Spyder (IDE)
  - Jupyter Notebook

Inference :
  - Models: kNeighborsClassifier, DecisionTreeClassifier, Gaussian Naive Bayes
  - Features: Age, Cholesterol,  Thalach, Oldpeak, Sex, Exang, Slope

## Results

After a thorough exploration of different classification algorithms. Our tests found that the Gaussian Naive Bayes algorithm was the best for predicting heart disease from the dataset with an accuracy score of (81.33%).  From the data the highest correlation with heart disease is exercise induced angina. 

## Discussion

After a thorough exploration of different classification algorithms. Our tests found that the Gaussian Naive Bayes model resulted in the best classifications. The data was split 60% for training and 40% for testing and resulted in a test accuracy of 81.22%. Overall, we believe that the dataset may be insufficient for the classification task as it does not contain a large number of entries. We believe that we could potentially achieve higher with a larger dataset. Furthermore, it would be great to have demographic information to explore the relationships between heart disease and individual identifying characteristics. After examining, various notebooks used for competitive purposes on Kaggle, we realized that we could also use other regressive algorithms such as Logistic Regression.

## Summary

This heart disease prediction projects utilizes a supervised classification model (Gaussian Naive Bayes) to predict the presence of heart disease based on 7 features: Age, Cholesterol,  Thalach, Oldpeak, Sex, Exang, and Slope. After exploring various feature engineering techniques, the Gaussian Naive Bayes model’s testing accuracy is approximately 81%.
