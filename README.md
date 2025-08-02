# CyberSecurityBigDataAnalytics
## Cybersecurity Threat Detection & Anomaly Analysis Dashboard

## 📌 Overview
This project focuses on detecting cybersecurity threats and anomalies in network traffic data using Python for preprocessing & anomaly detection, and Power BI for interactive visualization.

The dashboards present:
- Overall network traffic statistics
- Anomaly detection insights
- Model performance metrics

---

## 📊 Dataset
**Name:** Refined Cybersecurity Dataset with Anomaly  
**Size:** ~X MB  
**Key Fields:**
- `src_bytes`, `dst_bytes` — Traffic byte counts
- `protocol`, `flag` — Network protocol details
- `label` — Benign or attack type
- `anomaly_label` — (-1 = anomaly, 1 = normal)
- `anomaly_score` — Outlier score from Isolation Forest
- `Actual_Label`, `Predicted_Label` — Classification results

---

## 🛠 Methodology
1. **Data Cleaning:** Removed missing values, encoded categorical columns
2. **Anomaly Detection:** Applied Isolation Forest algorithm to detect outliers
3. **Visualization:** Built interactive dashboards in Power BI

---

## 📊 Dashboard Pages

### 1️⃣ Traffic Overview Dashboard
- Total Records
- Total Benign Traffic
- Total Attacks
- Anomaly distribution (donut chart)
- Filters for `protocol`, `flag`, `predicted label`

### 2️⃣ Anomaly Detection & Model Evaluation Dashboard
- Anomalies Detected
- Anomaly Rate 
- Model Accuracy 
- Scatter plot of bytes vs anomaly status
- Confusion matrix

---

## 📈 Results
- **Anomalies Detected:** 100
- **Anomaly Rate:** 5%
- **Model Accuracy:** 70%

---

## 🛠 Tools & Technologies
- **Python:** pandas, scikit-learn
- **Power BI:** Interactive dashboard design
- **Isolation Forest:** Unsupervised anomaly detection

---

## 📌 Future Work
- Integrate real-time streaming data
- Experiment with advanced ML models (XGBoost, PyCaret)
- Build automated alerting system for anomalies

---

## 📥 Files & Resources

### 📊 PowerPoint Presentation
[🎯 View Presentation](./Cybersecurity_Capstone_Presentation.ppt) |(https://github.com/Serge731/CyberSecurityBigDataAnalytics/blob/main/Cybersecurity_Capstone_Presentation.pptx)

### 🖼️ Dashboard Screenshots
[📁 Screenshots Folder](./screenshots/) | [🔍 View Gallery](#dashboard-gallery)

### 📄 Documentation
- [📋 Dataset](./data/refined_dataset_with_anomaly.csv)

### 🔗 Quick Links
| 📊 Data Analysis | Complete Jupyter Notebook | [Open Notebook](http://localhost:8888/notebooks/CyberSecurity%20docs/CyberSecurityProject.ipynb) |

---
