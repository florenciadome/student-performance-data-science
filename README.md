# student-performance-data-science
Data science project analyzing student performance and predicting exam scores using Python and linear regression.

#Student Performance Analysis

This project analyzes the factors that influence students' academic performance using data science techniques. The main objective is to understand how behavioral, contextual, and historical variables impact the final exam score and to build a simple predictive model.

#Objective

To explore and model the relationship between different student-related variables and the final exam score (Exam_Score) in order to identify which factors have the strongest influence on academic performance.

#Dataset

The dataset contains information about students, including:

*Attendance
*Hours_Studied
*Previous_Scores
*Sleep_Hours
*Parental_Education_Level
*Exam_Score (target variable)

The data is cleaned and explored using exploratory data analysis (EDA) techniques.

#Analysis Steps

1)Data cleaning and preprocessing
2)Exploratory Data Analysis (EDA)
3)Statistical analysis (correlations, ANOVA)
4)Visualization of relationships
5)Feature comparison
6)Predictive modeling using Linear Regression
7)Model evaluation using R² and MAE

#Model

A Linear Regression model is used to predict Exam_Score based on:

Attendance
Hours_Studied
Previous_Scores
Sleep_Hours

Model performance:

R² ≈ 0.61

MAE ≈ 1.38

These results indicate a good baseline predictive performance for a simple linear model.

#Key Findings

Attendance is the most influential variable on exam performance.
Hours studied also show a strong positive impact.
Parental education level has a statistically significant but small practical effect.
Previous scores show limited predictive power.
Sleep hours do not present a relevant linear relationship with exam scores in this dataset.

#Technologies Used

Python
Pandas
NumPy
Matplotlib
Scikit-learn

#Author
      Florencia Domé
