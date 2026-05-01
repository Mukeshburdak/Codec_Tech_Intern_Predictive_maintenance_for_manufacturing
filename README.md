# 🏭 Predictive Maintenance for Manufacturing

## 📌 Goal
The goal of this project is to predict machinery failures before they occur using machine learning techniques. This helps reduce unplanned downtime, optimize maintenance schedules, and improve overall operational efficiency in manufacturing environments.

## 🔍 Problem Statement
Unplanned equipment failures in manufacturing can lead to:

- Expensive production stoppages

- Increased maintenance costs

- Reduced equipment lifespan

This project leverages sensor data and machine learning to predict when machinery is likely to fail, allowing maintenance teams to take proactive actions.

## 📊 Dataset
The dataset contains time-series sensor readings from industrial machines, typically including:

- Temperature

- Pressure

- Vibration

- Rotation speed

- Failure indicators (labels)

Note: A publicly available dataset like NASA’s turbofan engine degradation or any simulated dataset can be used.

## ⚙️ Techniques Used
Exploratory Data Analysis (EDA)

- Feature Engineering (Rolling stats, lags, etc.)

- Data Preprocessing (Imputation, normalization)

- Machine Learning Models:

- Random Forest

- XGBoost

- Support Vector Machine (SVM)

- Logistic Regression

- Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

> git clone [(https://github.com/Mukeshburdak/Codec_Tech_Intern_Predictive_maintenance_for_manufacturing)]


## 📈 Results
The model achieved:
 - Best Accuracy.

These results demonstrate a reliable ability to detect upcoming failures before they occur.

## 🔮 Future Improvements
- Use real-time data from IoT sensors

- Integrate deep learning (LSTM, GRU) for time-series forecasting

- Deploy model with Flask/FastAPI for real-time predictions

- Dashboard with live KPIs using Streamlit or Dash.
