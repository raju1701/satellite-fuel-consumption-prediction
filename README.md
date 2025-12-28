# 🛰️ Satellite Fuel Consumption Prediction

## 📌 Overview
This project uses a **Linear Regression model** to predict satellite fuel consumption based on mission and orbital parameters.  
The goal is to understand how different factors influence fuel usage and support mission planning decisions.

---

## 🎯 Problem Statement
Satellite fuel is limited and critical for mission success.  
Accurate fuel consumption prediction helps in:
- Extending mission lifespan
- Planning orbital maneuvers
- Detecting inefficient usage

---

## 🧠 Approach
1. Created a realistic synthetic satellite dataset
2. Performed Exploratory Data Analysis (EDA)
3. Built a Multiple Linear Regression model
4. Evaluated the model using MAE, RMSE, and R²
5. Visualized model performance using prediction vs actual plots

---

## 📊 Features Used
- Satellite_Mass (kg)
- Orbit_Altitude (km)
- Mission_Duration (days)
- Orbit_Corrections (count)

**Target:** Fuel_Consumed (kg)

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📈 Results
The model demonstrates strong predictive performance with interpretable coefficients, making it suitable for engineering analysis and learning purposes.

---

## 🚀 Future Improvements
- Add regularization (Ridge/Lasso)
- Introduce anomaly detection
- Deploy as a cloud-based API
