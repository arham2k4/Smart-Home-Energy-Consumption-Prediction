# 🏠 Smart Home Energy Consumption Prediction

A Data Science and Machine Learning project that analyzes smart home energy usage patterns and predicts household energy consumption using regression models. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, and model comparison to identify the most effective prediction model.

## 📌 Project Overview

This project uses minute-level smart home energy data to understand consumption behavior and forecast total energy usage. Various machine learning models were trained and evaluated to achieve accurate predictions.

## 🎯 Objectives

* Clean and preprocess raw energy data
* Engineer time-based and appliance-based features
* Perform exploratory data analysis (EDA)
* Analyze consumption patterns and correlations
* Train and compare regression models
* Identify factors influencing energy consumption

## 📊 Dataset

* **Dataset:** HomeC.csv
* **Rows:** 503,911
* **Columns:** 32
* **Data Includes:**

  * Household energy consumption
  * Appliance power usage
  * Solar generation
  * Weather conditions
  * Time information

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## ⚙️ Data Preprocessing

* Removed corrupted rows
* Converted data types
* Handled missing values
* Removed redundant columns
* Engineered appliance and time-based features
* Applied IQR-based outlier removal

## 📈 Exploratory Data Analysis

* Energy usage distribution
* Hourly consumption patterns
* Appliance-wise power usage
* Temperature vs energy relationship
* Correlation heatmap analysis

## 🤖 Machine Learning Models

### Linear Regression

* MAE: 0.4452
* R² Score: 0.3952

### Decision Tree Regressor

* MAE: 0.1611
* R² Score: 0.8171

### Random Forest Regressor ⭐

* MAE: 0.1251
* R² Score: 0.9104

## 🏆 Best Model

Random Forest achieved the highest accuracy with an R² score of 0.91, making it the most effective model for predicting household energy consumption.

## 📂 Project Structure

```text
Smart-Home-Energy-Consumption/
│
├── data/
│   └── HomeC.csv
├── notebooks/
│   └── DS2.ipynb
├── images/
│   └── visualizations
├── SmartHomeEnergyReport.docx
├── requirements.txt
└── README.md
```

## 📌 Key Findings

* Furnace usage is the most influential factor affecting energy consumption.
* Appliance activity impacts energy demand more than weather conditions.
* Random Forest significantly outperformed Linear Regression and Decision Tree models.

## 🚀 Future Improvements

* Hyperparameter tuning
* XGBoost and Gradient Boosting models
* Real-time energy monitoring dashboard
* Streamlit web application deployment

## 👨‍💻 Authors

* Muhammad Arham
* Ammar Ahmed
* Hafiz Asad

⭐ If you found this project useful, consider giving it a star!
