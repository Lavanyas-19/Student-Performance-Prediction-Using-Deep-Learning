# Student-Performance-Prediction-Using-Deep-Learning

## Overview
This project predicts the final grades (G3) of students using machine learning and deep learning techniques. It explores the impact of various factors such as study time, health, paid classes, alcohol consumption, and more on student performance.

## Dataset
- **Source:** [UCI Machine Learning Repository: Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)
- **Size:** 395 records
- **Features:** 33 attributes including demographic, academic, and social aspects
- **Target:** `G3` (Final grade)

## Project Structure
- **Data Loading & Preprocessing:** Handling categorical variables, normalization, checking for missing values, and outliers.
- **Exploratory Data Analysis (EDA):** Visualizing distributions, correlations, and patterns in data.
- **Modeling:** 
  - Linear Regression
  - Random Forest Regressor
  - Deep Learning (MLP)

## Technologies Used
-Python 3.x
-Pandas, NumPy
-Matplotlib, Seaborn
-Scikit-learn
-TensorFlow / Keras

## Key Insights from EDA
-Study time positively correlates with final grades.
-Paid extra classes have a noticeable impact on performance.
-Students’ health and workday alcohol consumption influence grades moderately.
-Gender and guardian type show minor differences in performance.

- **Evaluation & Visualization:** 
  - Metrics: MSE, MAE, RMSE, R²
  - Visualizations: Error plots, prediction vs actual, feature importance, loss curves

- **Conclusion & Future Scope:** Summary of findings and suggestions for improvement
