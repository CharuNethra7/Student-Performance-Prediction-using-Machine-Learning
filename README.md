# Student-Performance-Prediction-using-Machine-Learning

## Project Overview
This project aims to predict students **exam scores** based on academic, behavioral, and socio-economic factors using **machine learning regression models**.  
The objective is to identify key factors influencing student performance and build a predictive model that can help educators provide early academic support.

---

## Problem Statement
Educational institutions often struggle to identify students who may underperform in exams at an early stage.  
Using machine learning, this project predicts **Exam_Score** based on multiple student-related factors.

---

## Dataset
- **File:** StudentPerformanceFactors.csv  
- **Target Variable:** `Exam_Score`  
- **Features Include:**
  - Hours_Studied
  - Attendance
  - Previous_Scores
  - Sleep_Hours
  - Motivation_Level
  - Parental_Involvement
  - Internet_Access
  - School_Type
  - Gender
  - Extracurricular_Activities
  - Access_to_Resources
  - Tutoring_Sessions
  - Family_Income
  - Teacher_Quality
  - School_Type
  - and more

---

## Data Preprocessing
- Handled categorical variables using **Label Encoding**
- Separated features (X) and target (y)
- Performed **train-test split (80% training, 20% testing)**
- Ensured data consistency and avoided data leakage

---

## Models Used
1. **Linear Regression**
2. **Random Forest Regressor**

---

## Model Evaluation
Models were evaluated using:
- **R² Score**
- **Mean Absolute Error (MAE)**

### Results:
- Linear Regression provided a baseline performance
- Random Forest performed better due to its ability to capture **non-linear relationships**

---

## Feature Importance
Random Forest helped identify the most influential factors affecting exam scores, such as:
- Previous Scores
- Hours Studied
- Attendance
- Motivation Level

---

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Conclusion
The project demonstrates how machine learning can be applied to educational data to predict student performance.  
Such models can assist schools in identifying students who need academic intervention early.

---

## Future Enhancements
- Hyperparameter tuning
- Model deployment using Streamlit or Flask
- Trying advanced models like XGBoost
- Adding real-time prediction interface

---
