# Cardiovascular Disease Prediction using Machine Learning

##  Overview
This project focuses on predicting the presence of cardiovascular disease using machine learning techniques. The goal is to analyze patient health data and build models that can assist in early detection of heart disease.

---

##  Dataset
- Dataset contains patient health information such as:
  - Age
  - Gender
  - Blood Pressure (ap_hi, ap_lo)
  - Cholesterol levels
  - Other medical attributes

---

##  Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

##  Project Workflow

### 1. Data Preprocessing
- Removed unnecessary columns (e.g., ID)
- Converted age into years
- Checked for missing values
- Standardized features using `StandardScaler`

### 2. Exploratory Data Analysis (EDA)
- Visualized:
  - Age distribution
  - Gender distribution
  - Disease vs non-disease count
  - Blood pressure trends
- Generated correlation heatmap

### 3. Model Building
Implemented and compared multiple ML models:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

### 4. Model Evaluation
- Evaluated models using accuracy score
- Generated classification report
- Compared performance across models

---

##  Results
- **Support Vector Machine (SVM)** achieved the highest accuracy (~73%)
- Identified key factors influencing cardiovascular disease:
  - Age
  - Blood pressure
  - Cholesterol levels

---

##  Key Learnings
- Importance of data preprocessing and feature scaling
- Model comparison for selecting best-performing algorithm
- Role of machine learning in healthcare analytics

---

##  Future Improvements
- Hyperparameter tuning for better accuracy
- Use of advanced models (XGBoost, Neural Networks)
- Deployment as a web application for real-time prediction

---

##  Author
V Charitha
