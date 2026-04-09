# -ATM-Cash-Demand-Forecasting
# 💳 ATM Cash Demand Forecasting using PySpark

## 📌 Overview

This project focuses on predicting ATM cash demand using machine learning techniques. The goal is to forecast the amount of cash required for the next day based on historical transaction data and contextual factors such as withdrawals, deposits, holidays, and previous cash levels.

Efficient ATM cash management is crucial for banks to avoid shortages and reduce operational costs. This project demonstrates how data-driven approaches can improve decision-making in banking systems.

---

## 🚀 Features

* Data preprocessing using PySpark
* Feature engineering (Day of Week, Holiday Flag, etc.)
* Machine learning model using Linear Regression
* Model evaluation using RMSE and R²
* Visualization of actual vs predicted demand
* Scalable solution using Apache Spark

---

## 🧠 Technologies Used

* Python
* PySpark (Apache Spark MLlib)
* Pandas
* Matplotlib

---

## 📊 Dataset

The dataset contains ATM transaction-related information such as:

* Total Withdrawals
* Total Deposits
* Previous Day Cash Level
* Holiday Indicator
* Weather Conditions
* Cash Demand Next Day (Target Variable)

---

## ⚙️ Methodology

1. Load dataset into Spark DataFrame
2. Handle missing values and clean data
3. Perform feature engineering
4. Build Linear Regression model
5. Evaluate model using RMSE and R²
6. Visualize predictions

---

## 📈 Results

The model successfully predicts ATM cash demand with reasonable accuracy. It captures patterns such as higher withdrawals during weekends and holidays.

---

## 🎯 Applications

* ATM cash replenishment optimization
* Banking operations management
* Financial demand forecasting

---

## 🔮 Future Improvements

* Implement advanced models (Random Forest, LSTM)
* Include real-time and external data
* Improve feature selection

---

## 🤝 Contribution

Feel free to fork this repository and contribute improvements!

---

## 📜 License

This project is open-source and available under the MIT License.
