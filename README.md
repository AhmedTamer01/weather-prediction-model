# Extreme Weather Prediction Model 🌤️⛈️

A machine learning pipeline designed to forecast severe weather conditions based on historical meteorological and atmospheric data.

## 🚀 Project Overview

Extreme weather events—such as storms, heatwaves, and heavy rainfall—pose significant risks to agriculture, infrastructure, and human life. Predicting these events accurately requires analyzing complex, multidimensional atmospheric data.

This project implements robust machine learning classifiers to predict the occurrence of specific weather conditions using features like temperature, humidity, wind speed, and atmospheric pressure.

## ⚙️ Methodology

1. **Data Preprocessing**: 
   - Handled anomalous sensor readings and missing data points using interpolation techniques.
   - Scaled and normalized features (like pressure and wind speed) which operate on vastly different numerical scales.
2. **Feature Selection**: Identified the highest-correlating meteorological factors leading up to extreme events.
3. **Modeling**:
   - Built and trained classification models (such as Random Forests and XGBoost) to predict categorical weather states.
4. **Evaluation**: Evaluated the models heavily on Recall and F1-Score to ensure dangerous weather events are not missed.

## 🛠️ Tech Stack & Libraries Used

- **Data Handling:** Pandas, NumPy
- **Machine Learning Algorithms:** Scikit-learn, XGBoost
- **Data Visualization:** Matplotlib, Seaborn

## 📈 Key Outcomes

- Built a predictive model capable of flagging high-risk weather conditions hours in advance.
- Demonstrated the ability to handle highly imbalanced datasets (as extreme weather is relatively rare compared to normal days).

---
*This repository is part of my AI Engineer / Data Scientist Portfolio.*
