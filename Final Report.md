""# 🚀 Machine Learning Project Report

📊 Final Report – Data Science Internship

🔍 Overview

This internship involved working on two real-world data science problems using Python and Jupyter Notebooks.

## 📝 Introduction

This report presents the summary of three machine learning projects:

1. **Task 1: Financial Time-Series Anomaly Detection** 📈
2. **Task 2: Multi-Label Emotion Recognition from Text** 🎭
3. **Task 3: Credit Risk Analysis** 💰

Each project includes detailed steps for data preparation, model training, evaluation, and key findings.

---

## 📈 Task 1: Financial Time-Series Anomaly Detection

### 🎯 Objective:

To identify anomalies in stock price trends to detect unusual activities or market manipulations using historical financial data.

### 📌 Data Preparation:

* Dataset: **Yahoo Finance Stock Market Dataset**, covering historical stock prices.
* Processing steps included:

  * 📥 Downloading and preprocessing historical stock price data for selected companies.
  * 📊 Calculation of financial indicators such as:

    * SMA (Simple Moving Average)
    * EMA (Exponential Moving Average)
    * RSI (Relative Strength Index)
    * Bollinger Bands
  * 📅 Time-series indexing and outlier detection.

### ⚙️ Modeling Approach:

* **Unsupervised Anomaly Detection**:

  * Algorithms used: **Isolation Forest** and **DBSCAN**.
  * Purpose: To detect unusual deviations in stock price movements.
* **Time-Series Forecasting**:

  * Models used: **LSTM** and **Prophet**.
  * Purpose: To predict future price trends and identify unexpected deviations.

### 📊 Evaluation Metrics:

* Metrics used: **Mean Absolute Error (MAE)**, **Root Mean Square Error (RMSE)**, and **Anomaly Detection Scores**.
* Visualization of detected anomalies on stock price charts.

### ✅ Conclusion:

The model effectively identified anomalies in stock price movements, enabling early detection of market manipulations or unusual trading activities.

---

## 🎭 Task 2: Multi-Label Emotion Recognition from Text

### 🎯 Objective:

To classify multiple emotions present in textual data simultaneously using the **GoEmotions Dataset**.

### 📌 Data Preparation:

* Dataset: **GoEmotions**, containing text labeled with 27 emotions and a neutral category.
* Processing steps included:

  * 🔍 Loading and inspecting the dataset.
  * ✍️ Converting text into BERT-compatible input formats (input IDs, attention masks).
  * 🗂️ Multi-label binarization of emotion labels.

### ⚙️ Modeling Approach:

* Model: **BERT (BertForSequenceClassification)** with multi-label classification.
* Custom Data Collator was used to handle padding and tensor conversion.
* Optimizer: **AdamW**
* Loss Function: **BCEWithLogitsLoss** to handle multi-label outputs.

### 📊 Evaluation Metrics:

* Metrics used: **Hamming Loss**, **F1-Score (micro and macro)**, **Precision**, and **Recall**.
* The model demonstrated strong multi-label classification capabilities, with balanced precision and recall across emotions.

### ✅ Conclusion:

The model effectively handled multi-label emotion detection, showcasing the capacity of BERT to learn nuanced emotional contexts from textual data.

---

## 💰 Task 3: Credit Risk Analysis

### 🎯 Objective:

To predict the risk of financial distress among loan applicants using the **Give Me Some Credit** dataset.

### 📌 Data Preparation:

* Dataset: **Give Me Some Credit**, containing customer financial data.
* Processing steps included:

  * 🛠️ Handling missing values and imbalances using **SMOTE**.
  * ⚖️ Feature scaling and normalization.
  * ✂️ Splitting into training and test sets.

### ⚙️ Modeling Approach:

* Models used: **Random Forest**, **Gradient Boosting**, and **XGBoost**.
* Feature engineering on income, debt, and repayment history.
* Hyperparameter tuning for optimal results.

### 📊 Evaluation Metrics:

* Metrics used: **ROC-AUC Score**, **Precision**, **Recall**, and **F1-Score**.
* The models effectively distinguished between low and high-risk applicants.

### ✅ Conclusion:

The approach successfully identified credit risk patterns, providing a robust model for financial risk assessment.

---

## 🔎 Overall Summary

The three projects demonstrated proficiency in different machine learning domains:

1. **Anomaly Detection:** Identification of unusual market activities in financial time-series data 📈.
2. **Text Classification:** Multi-label emotion detection in textual content 🎭.
3. **Credit Risk Analysis:** Predictive modeling for financial risk assessment 💰.

Each project showcased end-to-end implementation, including data preprocessing, model development, evaluation, and interpretation of results.
""
