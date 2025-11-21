# Bussiness-analytics-project
A Machine Learning + Time Series based system to predict patient appointment no-shows, analyse patterns, and provide hospital-ready insights via a Streamlit dashboard.
Here is a **clean, professional, ready-to-use README.md** for your entire project.

It works perfectly for **GitHub**, **submission**, **documentation**, or **project report**.

---

# 📘 **README — Patient No-Show Prediction & Forecasting System**

## 🏥 **Project Title**

**Analytics-Driven Prediction and Forecasting of Patient Appointment No-Shows**

---

## 📌 **Overview**

This project predicts whether a patient will attend or miss their medical appointment.
It combines **Machine Learning**, **Time-Series Forecasting**, and **Business Analytics** to help hospitals:

* Reduce no-show rates
* Optimize scheduling and staffing
* Make data-driven decisions
* Provide early warnings for high-risk appointments

A **Streamlit web app** is included for live predictions, analytics dashboards, and AI-powered explanations (Gemini Assist).

---

## 🚀 **Key Features**

### ✔ **1. Data Preprocessing**

* Cleaning, standardization, fixing date formats
* Handling missing data
* Encoding categorical variables
* Removing unusable or high-variance features

### ✔ **2. Feature Engineering**

* Behavioural features:

  * prior_no_show_rate
  * comorbidity_count
  * risk_x_leadtime
* Temporal features:

  * lead_time_days
  * day_of_week
  * month
  * appointment_hour

### ✔ **3. Exploratory Data Analysis (EDA)**

* Distributions & boxplots
* Correlation heatmaps
* Patient behaviour statistics
* Neighbourhood risk analysis
* Temporal trends (daily, weekly, monthly)

### ✔ **4. Predictive Modelling**

Models implemented:

* Logistic Regression
* KNN
* Decision Tree
* Random Forest
* Gradient Boosting (Best model)
* MLP Classifier

Performance metric used:
✔ Accuracy
✔ Precision
✔ Recall
✔ F1-Score
✔ ROC-AUC

### ✔ **5. Time-Series Forecasting**

Algorithms:

* ARIMA
* SARIMA / SARIMAX

Outputs:

* Weekly no-show forecasts
* Confidence intervals
* STL decomposition (Trend, Seasonal, Residual)

### ✔ **6. Gemini Assist – AI Insights**

* Explains predictions in human language
* Highlights risk factors
* Suggests hospital actions (SMS, rescheduling, reminders)

### ✔ **7. Streamlit Web App**

Sections:

* Overview
* EDA
* Modelling & Evaluation
* Time Series
* Business Analytics
* Live Prediction
* Gemini Assist

---

## 🔧 **Technical Stack**

| Layer               | Tools / Libraries                |
| ------------------- | -------------------------------- |
| Language            | Python                           |
| Data                | Pandas, NumPy                    |
| EDA & Visualization | Matplotlib, Seaborn, Plotly      |
| ML Models           | Scikit-Learn                     |
| Time Series         | Statsmodels (ARIMA, SARIMA), STL |
| App Deployment      | Streamlit                        |
| AI Explanation      | Google Gemini API                |
| Storage             | Pick                             |
