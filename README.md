Rock vs Mine Prediction using SONAR Data
🎯 Project Overview
Build a binary classification model in Python that can predict whether an underwater object, represented by SONAR signal data, is a rock or a mine. The project is based on Siddhardhan’s end-to-end machine learning walkthrough using libraries such as NumPy, Pandas, and scikit-learn 

Dataset
Uses the UCI Sonar Dataset, containing 60 sonar reflection measurements plus a label column (R for rock or M for mine).

Total of ~208–209 samples.

Included in the repo as sonar_data.csv .

📦 File Structure

├── sonar_data.csv
├── rock_mine_detection.ipynb
├── README.md

Key Learnings
How logistic regression works for binary classification

Data preprocessing using Pandas, NumPy, scikit-learn

Understanding evaluation metrics and model comparison

Introduction to kNN as an alternative classifier .

Future Enhancements
Explore Support Vector Machines (SVM) or Random Forest models

Try Principal Component Analysis (PCA) or feature engineering to reduce dimensionality

Deploy into a real-time prediction system or integrate onboard SONAR preprocessing

 Technologies Used
Python

Jupyter Notebook

NumPy

Pandas

Scikit-learn

Acknowledgements
Mentoring and tutorial provided by Siddhardhan on YouTube

Dataset courtesy of the UCI Machine Learning Repository

TL;DR
Problem: Classify a sonar signal as rock (R) or mine (M)

Model: Logistic Regression (can compare with kNN or SVM)

Tools: Python, Pandas, NumPy, scikit-learn

Data: 208 samples × 60 features + class label

Outcome: Predictive accuracy ~80–85% (often kNN slightly better than logistic)

 Author
Saniya Chhabra
Passionate about AI, ML & Data Science
LinkedIn

---


