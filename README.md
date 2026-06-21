# 🫀 Heart Attack Risk Prediction Pipeline

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Framework-Scikit--Learn-orange.svg)](https://scikit-learn.org/)
[![Imbalance-Learn](https://img.shields.io/badge/Oversampling-SMOTE-red.svg)](https://imbalanced-learn.org/)

This repository presents an end-to-end machine learning engineering workflow designed to predict heart attack risk using clinical metrics and patient lifestyle data. 

The architecture features programmatic solutions to complex data challenges, including **stratified train-test partitioning**, custom **non-linear biological feature engineering**, **SMOTE oversampling** to correct class imbalance, and a **GridSearchCV hyperparameter tuning matrix** for model optimization.

---

## 🚀 Key Framework Enhancements & Tutor Feedback Solved

This updated pipeline features custom engineering adjustments to resolve critical analytical gaps highlighted in the feedback:

* **📊 Numeric Correlation Matrix:** Upgraded visual heatmaps to use explicit Pearson annotations (`annot=True`), displaying precise quantitative weights for every single multi-variable intersection.
* **⚖️ Synthetic Minority Over-sampling (SMOTE):** Fixed baseline class imbalance drop-offs by applying a balanced oversampler *post-split* to safeguard the pipeline against data leakage.
* **🧪 Hyperparameter Optimization Matrix:** Replaced default baseline algorithms with comprehensive 5-fold cross-validation tuning grids (`GridSearchCV`), resolving zero-division score drops across Precision and Recall.
* **🧬 Biological Feature Engineering:** Built strong predictive indicators including `Pulse_Pressure` (Systolic - Diastolic BP) and `Cardio_Age_Interaction` (Age $\times$ Cholesterol) to capture complex non-linear clinical signals.

---

## 🛠️ Installation & Setup

To reproduce the data processing, visualization plots, and cross-validation model scores on your local machine, follow these steps:

### 1. Clone the Repository
Download the project source files to your local workspace:
```bash
git clone [https://github.com/nadeemalisyed/heart-disease-prediction-ml.git](https://github.com/nadeemalisyed/heart-disease-prediction-ml.git)
cd heart-disease-prediction-ml


## 2. Set Up Your Environment
```bash
python -m venv venv

## 3. Activate Virtual Environment
###For Windows:
```bash
venv\Scripts\activate

###For macOS / Linux:
```bash
source venv/bin/activate

## 3. Install Required Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn

#🖥️ How to Run the Project
##Launch Jupyter: Open your notebook environment inside your project directory:
```bash
jupyter notebook

###Open the Notebook: Navigate to and click on heartDiseasePredictor_enhanced.ipynb.Execute the Code: Select Cell $\rightarrow$ Run All from the top menu to run the entire end-to-end pipeline sequentially.
##🌐 Author: Nadeem Ali Syed
##🎓 Project Scope: Academic Machine Learning Research and Model Evaluation Workflow.