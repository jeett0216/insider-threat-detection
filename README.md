# 🔐 AI-Powered Insider Threat Detection System

## 📌 Project Overview

This project focuses on detecting **suspicious insider activities** using Machine Learning.
It uses an **unsupervised anomaly detection approach (Isolation Forest)** to identify abnormal employee behavior based on activity logs.

The system learns normal behavior patterns and flags deviations as potential insider threats.

---

## 🚀 Key Features

* Detects abnormal user behavior using anomaly detection
* Works without labeled data (unsupervised learning)
* Includes behavioral and time-based feature engineering
* Assigns risk levels: **High, Medium, Low**
* Visualizes anomalies using graphs
* Generates a report of suspicious users

---

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📊 Dataset

A simulated employee activity dataset was used with features such as:

* Login count
* File access count
* Failed login attempts
* Data download volume
* Login timestamp

---

## ⚙️ Project Workflow

1. **Data Collection**

   * Simulated user activity logs

2. **Data Preprocessing**

   * Handling structured data
   * Converting data into numerical format

3. **Feature Engineering**

   * Extracted `login_hour` from timestamp
   * Created `after_hours_login` feature

4. **Data Scaling**

   * Applied StandardScaler for normalization

5. **Model Training**

   * Used Isolation Forest algorithm
   * Learned normal behavior patterns

6. **Anomaly Detection**

   * Predicted anomalies (`-1`) and normal users (`1`)
   * Generated anomaly scores

7. **Risk Categorization**

   * Converted scores into:

     * High Risk
     * Medium Risk
     * Low Risk

8. **Visualization**

   * Scatter plots for anomaly detection
   * Distribution graphs for analysis

9. **Reporting**

   * Exported suspicious users to CSV file

---

## 📈 Model Evaluation

* Used **Confusion Matrix**
* Calculated **Precision, Recall, F1-score**
* Achieved high accuracy on simulated dataset

---

## 📂 Output

* Identifies suspicious employees
* Generates `suspicious_users.csv` report
* Provides risk-level classification

---

## 🎯 Real-World Use Case

This system can be used in organizations to:

* Detect insider threats
* Monitor abnormal employee activity
* Improve cybersecurity and data protection

---

## ⚠️ Note

This system detects **anomalies, not confirmed attacks**.
All flagged users should be reviewed by security teams.

---

## 🏆 Author

Smruti Ranjan Nayak
