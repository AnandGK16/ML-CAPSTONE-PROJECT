# ML-CAPSTONE-PROJECT

# OBESITY LEVEL PREDICTION MODEL

## Author: Anand Krishna G K
## Organization: Entri
## Date: 10/07/2024

---

## TABLE OF CONTENTS

1. **Problem Statement**
2. **Objective**
3. **Data Collection**
4. **Data Description**
5. **Exploratory Data Analysis (EDA)**
6. **Data Preprocessing**
7. **Visualization**
8. **Feature Engineering**
9. **Data Splitting**
10. **Model Selection**
11. **Feature Selection**
12. **Model Training**
13. **Model Evaluation**
14. **Hyperparameter Tuning**
15. **Results**
16. **Model Deployment**
17. **Limitations**
18. **Conclusion**
19. **Future Work**

---

## Problem Statement

This project aims to develop a predictive model to assess obesity levels based on a range of features related to eating habits, physical activity, and other lifestyle factors. The dataset comprises 2,111 records from individuals in Mexico, Peru, and Colombia, including various attributes such as demographic information, dietary habits, physical activity levels, and other health-related behaviors.

Given the rising prevalence of obesity and its associated health risks, early and accurate detection of obesity levels is crucial for timely intervention and prevention of related diseases such as diabetes, cardiovascular diseases, and certain cancers. This project seeks to contribute to public health efforts by providing a reliable tool for predicting obesity levels, which can aid healthcare providers and individuals in making informed decisions about lifestyle changes and medical interventions.

## Objective

The objective of this project is to develop an accurate obesity level prediction model using features related to eating habits, physical activity, and other lifestyle factors. The primary goal is to train a classification model capable of predicting obesity levels based on various attributes such as demographic information, dietary habits, physical activity levels, and other health-related behaviors in individuals from Mexico, Peru, and Colombia.


## Data Collection

The dataset used in this project is available [here](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition).
It comprises information collected from individuals in Mexico, Peru, and Colombia, focusing on their eating habits, physical activity, and other lifestyle factors to estimate obesity levels. Each row represents a different individual, and the columns encapsulate various attributes including:

- Gender
- Age
- Height
- Weight
- Family history with overweight
- Frequency of high-calorie food consumption (FAVC)
- Frequency of vegetable consumption (FCVC)
- Number of main meals per day (NCP)
- Frequency of food consumption between meals (CAEC)
- Smoking habits (SMOKE)
- Daily water intake (CH2O)
- Monitoring of calorie consumption (SCC)
- Frequency of physical activity (FAF)
- Time spent using technological devices (TUE)
- Frequency of alcohol consumption (CALC)
- Main mode of transportation (MTRANS)
- Obesity level (NObeyesdad)

The dataset contains 2,111 records, with each feature contributing to the assessment of an individual's obesity level. The target variable, NObeyesdad, is classified into categories representing different levels of obesity, allowing the predictive model to classify individuals accurately based on the provided attributes.


## Conclusion

### Summary of Findings

This project aimed to develop a predictive model for assessing obesity levels based on a dataset encompassing demographic information, dietary habits, physical activity levels, and other health-related behaviors of individuals. The dataset, containing 2,111 records, was classified into seven categories of obesity levels: Insufficient_Weight, Normal_Weight, Overweight_Level_I, Overweight_Level_II, Obesity_Type_I, Obesity_Type_II, and Obesity_Type_III.

After rigorous feature selection using Recursive Feature Elimination (RFE) and SelectKBest methods, the following key predictors were identified: Age, Weight, FCVC (Food Consumption Frequency), Gender, family history with overweight, CAEC (Consumption of food between meals), CALC (Consumption of alcohol), and BMI Category. These features were found to significantly influence the accuracy and reliability of our predictive models.

Among various machine learning algorithms evaluated, including Logistic Regression, Decision Tree, Naive Bayes, K-Nearest Neighbors, and Random Forest, Random Forest and Decision Tree consistently outperformed others. Both models achieved an accuracy of approximately 97.36%, demonstrating robustness in predicting obesity levels across different categories.

The findings underscore the effectiveness of Random Forest and Decision Tree models in accurately predicting obesity levels based on diverse features related to lifestyle and health behaviors. These models offer valuable insights for healthcare providers and policymakers, facilitating early intervention strategies to mitigate the rising prevalence of obesity-related diseases such as diabetes and cardiovascular conditions.

Moreover, the project highlighted the importance of feature engineering, including the creation of the BMI_Category feature, which enhanced the model's predictive power by providing a nuanced understanding of weight status classifications.

While Logistic Regression and Naive Bayes also demonstrated respectable performance, their slightly lower accuracy compared to Random Forest and Decision Tree (approximately 95.43% and 81.25% respectively for Logistic Regression and Naive Bayes) suggests that ensemble methods are particularly well-suited for handling the complexities inherent in obesity prediction from diverse datasets.


