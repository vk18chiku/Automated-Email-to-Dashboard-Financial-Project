# 📊 Automated Financial ETL & Dashboard Pipeline

![Automation](https://img.shields.io/badge/Workflow-Automated-green?style=for-the-badge&logo=microsoftpowerautomate) ![Python](https://img.shields.io/badge/Python-ETL-blue?style=for-the-badge&logo=python) ![Power BI](https://img.shields.io/badge/Power_BI-Analytics-yellow?style=for-the-badge&logo=powerbi)

## 📌 Project Summary
This project eliminates manual data entry by automating the ingestion, processing, and visualization of daily financial survey data. By integrating **Power Automate, Google Drive, custom APIs, Python, and Power BI**, the solution reduces operational costs and delivers real-time business insights to stakeholders with zero manual intervention.

---

## 🔁 Automated Workflow Architecture

| Step | Tool | Description |
| :--- | :--- | :--- |
| **1** | **Outlook + Power Automate** | Automatically extracts email attachments received at 3 PM daily. |
| **2** | **Google Drive** | Serves as the central cloud repository for incoming raw data. |
| **3** | **Custom API** | Acts as a bridge to serve files from Google Drive to the processing environment. |
| **4** | **Python (Pandas)** | Performs ETL: cleans data, calculates financial metrics (LTV), and merges datasets. |
| **5** | **Power BI** | Visualizes processed data into interactive executive dashboards. |

---

## 🖼️ Dashboard Walkthrough

### 1. Financial Performance & Risk Metrics
This view tracks income distribution, payment delays, and credit utilization patterns to identify financial risks early.
![Financial Performance](https://raw.githubusercontent.com/vk18chiku/Automated-Email-to-Dashboard-Financial-Project/main/Screenshot%202025-12-31%20131858.png)

### 2. Customer Segmentation & Credit Behavior
Analyzes demographics and loan product popularity, including Life-Time Value (LTV) calculations for promotional eligibility.
![Customer Analysis](https://raw.githubusercontent.com/vk18chiku/Automated-Email-to-Dashboard-Financial-Project/main/Screenshot%202025-12-31%20131909.png)

---

## 📈 Key Insights Delivered
* **Financial Health:** Real-time tracking of balance vs. credit utilization.
* **Risk Patterns:** Identified correlations between age demographics and payment delays.
* **LTV Analysis:** Automated customer segmentation to identify "High Value" individuals for marketing promotions.
* **Product Popularity:** Trends in loan ownership across different age groups and locations.

---

## ⏱️ Automation Timeline
* **3:00 PM:** Raw survey data received via email.
* **3:01 PM:** Power Automate triggers, uploads files to cloud storage.
* **3:05 PM:** Python script executes ETL (Cleaning & Transformation).
* **3:15 PM:** Power BI dashboard refreshes.
* **By 8:00 PM:** Fully updated insights are ready for stakeholder review.

---

## 🛠️ Tech Stack
* **Automation:** Microsoft Power Automate (Flow)
* **Processing:** Python (Pandas, NumPy, Requests)
* **Storage:** Google Drive API
* **Visualization:** Power BI (DAX & Power Query)
* **Communication:** Microsoft Outlook

---

## 🧑‍💻 Contact
**Uttam Kumar Mahato** 📧 [uttammahato379@gmail.com](mailto:uttammahato379@gmail.com)  
📂 [GitHub Profile](https://github.com/vk18chiku)

---
*If you find this project helpful for your automation needs, feel free to ⭐ the repository!*



