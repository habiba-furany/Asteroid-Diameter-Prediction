# 🌑 Asteroid Diameter Prediction

## 📌 Project Overview

This project aims to predict asteroid diameter using Machine Learning regression models.

The dataset contains astronomical and orbital characteristics of asteroids, and the goal is to build an accurate predictive model for estimating asteroid size.

---

## 📊 Dataset Features

The dataset includes:

### 🔹 Identifiers
- id, spkid, full_name, orbit_id

### 🔹 Flags
- neo → Near-Earth Object
- pha → Potentially Hazardous Asteroid

### 🔹 Physical Properties
- H (Absolute magnitude / brightness)
- albedo (reflectivity)
- diameter (Target variable)

### 🔹 Orbital Parameters
- Eccentricity
- Semi-major axis
- Perihelion & Aphelion distance
- Orbital speed
- And other orbital elements

🎯 **Target Variable:** `diameter`

---

## 🔍 Exploratory Data Analysis (EDA)

- Dataset inspection (shape, info, describe)
- Missing value percentage analysis
- Correlation heatmap
- Feature vs Target scatter plots
- Distribution analysis
- Outlier detection using IQR
- Outlier removal & capping

---

## 🧹 Data Preprocessing

- Dropping irrelevant identifiers
- Column renaming for clarity
- Missing value imputation:
  - Mean for normally distributed features
  - Median for skewed features
- Label Encoding for categorical variables
- Standard Scaling
- Train/Test split (80/20)

---

## 🤖 Models Implemented

### 🔹 Linear Models
- Linear Regression
- Ridge Regression
- Lasso Regression

### 🔹 Ensemble Models
- Random Forest Regressor
- XGBoost Regressor

Models were evaluated using:

- R² Score
- RMSE (Root Mean Squared Error)

---

## 📈 Model Comparison

The project compares multiple regression approaches to determine the best-performing model for asteroid diameter prediction.

(You can insert your best R² score here to strengthen the project 🔥)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🚀 Future Improvements

- Hyperparameter tuning (GridSearch / RandomSearch)
- Cross-validation
- Feature importance analysis
- Model deployment (Streamlit / Flask)

---

## 👩‍💻 Author

Habiba Furany  
AI & Machine Learning Enthusiast
