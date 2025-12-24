# Student Performance Analysis & Prediction (Python)

## Overview
This project focuses on analyzing student academic performance and predicting final grades using supervised machine learning.
The objective is to understand and implement the complete machine learning workflow — from data preprocessing to model evaluation — using a real-world educational dataset.

This project is designed as a learning-oriented, explainable ML implementation suitable for internship-level roles.

---

## Dataset
The project uses the **Student Performance Dataset** from Kaggle.

Dataset link:  
https://www.kaggle.com/datasets/larsen0966/student-performance-data-set

The dataset contains academic and behavioral attributes of students, including:
- Study time
- Past failures
- Absences
- Previous exam grades (G1, G2)
- Final grade (G3)

The final grade (**G3**) is used as the prediction target.

> Note: The dataset is downloaded manually from Kaggle and is not uploaded to this repository in compliance with Kaggle’s data usage policy.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Project Workflow
1. Loaded the student performance dataset and explored its structure.
2. Checked for missing values and performed basic data preprocessing.
3. Conducted exploratory data analysis to understand grade distributions.
4. Selected relevant numerical features for modeling.
5. Trained a **Linear Regression** model to predict students’ final grades.
6. Evaluated model performance using **Root Mean Squared Error (RMSE)**.
7. Analyzed model coefficients to interpret feature influence on predictions.

---

## Model Evaluation
- **Model:** Linear Regression  
- **Metric:** RMSE (Root Mean Squared Error)

The model achieved an RMSE of approximately **1.15**, indicating that predictions are, on average, within about one grade point of the actual final grade.

---

## Key Insights
- Previous academic performance (especially G2) has the strongest impact on final grades.
- Past failures negatively affect final performance.
- Study time shows a moderate positive influence.
- Absences have relatively lower impact compared to prior grades.

---

## Conclusion
This project demonstrates a simple and interpretable supervised learning approach for predicting student performance.
It reinforces core machine learning concepts such as data preprocessing, model training, evaluation, and result interpretation.

The focus of this project is on clarity, correctness, and learning rather than model complexity.

---

## Author
**Tarun Tripathi**

