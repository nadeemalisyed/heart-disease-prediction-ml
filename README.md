Overview

This project compares multiple machine learning models to predict heart disease risk using structured clinical and lifestyle data.

Objectives
Perform exploratory data analysis (EDA)
Train multiple machine learning models
Evaluate models using appropriate metrics
Compare model performance and identify the best approach
Models Used
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
Gradient Boosting
AdaBoost
K-Nearest Neighbours (KNN)
Extra Trees
XGBoost
Results

Random Forest and XGBoost achieved slightly better performance compared to other models. Most models produced accuracy values between 63% and 64%, while recall remained low, indicating difficulty in identifying high-risk cases.

Limitations
Weak correlation between features and the target variable
Low recall across most models
Dataset limitations affecting predictive performance
Tools

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost

How to Run
Clone the repository:
git clone https://github.com/your-username/heart-disease-prediction-ml.git
Install required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
Open the project:
Navigate to the folder
Open the Jupyter Notebook file
Run the notebook:
Execute all cells step by step to reproduce results
