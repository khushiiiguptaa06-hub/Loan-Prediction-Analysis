#  Loan Prediction Data Analysis

##  Aim

The aim of this project is to analyze loan applicant data and build a machine learning model to predict loan approval status.

---

##  Dataset Overview

* Total Records: 614
* Features: 13
* Includes both categorical and numerical data

---

##  Exploratory Data Analysis (EDA)

* Checked missing values
* Analyzed data distribution
* Visualized key features using graphs

---

##  Data Cleaning

* Filled missing values:

  * Categorical → Mode
  * Numerical → Mean
* Converted categorical data using Label Encoding
* Handled special cases (e.g., Dependents column)

---

##  Model Used

* Logistic Regression

---

##  Model Performance

* Accuracy: ~78%
* Evaluated using Confusion Matrix and Classification Report

---

##  Key Insights

* Credit History is the most important factor
* Most loans are approved
* Data required preprocessing before model training

---

##  Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Perform hyperparameter tuning
* Deploy using Streamlit or Flask

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
