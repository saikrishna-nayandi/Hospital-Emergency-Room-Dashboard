# 🚑 Hospital Emergency Room Dashboard - Power BI Project

## 📌 Project Overview

This project delivers a comprehensive Power BI solution to monitor, analyze, and improve the operations of a hospital’s emergency room. It enables stakeholders to track key performance indicators (KPIs), identify trends, and drill down to patient-level data to make data-driven decisions aimed at optimizing patient management and enhancing quality of care.

---

## 🎯 Objectives

✅ Measure and visualize the emergency room's operational performance  
✅ Provide insights into patient admissions, wait times, referrals, and satisfaction  
✅ Highlight patterns and anomalies in patient visits by demographics and time  
✅ Support stakeholders with actionable recommendations to optimize resources

---

## 🗂️ Data Sources

The solution uses an underlying dataset (loaded in Power BI) with the following core fields:

- **Patient ID**: unique identifier for each patient  
- **Patient Admission Date**  
- **Patient First Initial / Last Name** (with anonymization possible)  
- **Patient Gender**  
- **Patient Age**  
- **Patient Race**  
- **Department Referral**  
- **Patient Admin Flag** (Admitted / Not Admitted)  
- **Patient Satisfaction Score**  
- **Patient Wait Time**  
- **Case Manager (if applicable)**

A **date dimension table** supports time-based slicing and aggregation.

---

## 🛠️ Project Steps

1. Requirement gathering  
2. Data walkthrough and schema understanding  
3. Data connection (Power BI data model)  
4. Data cleaning and quality checks  
5. Data modeling (relationship building, star schema)  
6. DAX calculations (KPIs, measures, trends)  
7. Dashboard layout design  
8. Visualizations and formatting  
9. Testing and validation  
10. Insight generation and documentation

---

## 📊 Dashboard Details

The project delivers **Three interactive dashboards** within the Power BI file:

### 1️⃣ Monthly View Dashboard

- **Purpose**: Provides a month-by-month view of emergency room performance  
- **Time selector**: Year + Month slicer  
- **KPIs**:  
  - Number of Patients (daily trend)  
  - Average Wait Time (daily trend)  
  - Patient Satisfaction Score (daily trend)  
  - Number of Patients Referred (daily trend)

- **Breakdown charts**:  
  - Patient Admission Status (Admitted vs Not Admitted with percentage)  
  - % of Patients Seen by Doctor Within 30 Minutes (target met vs missed)  
  - Patient Age Distribution (grouped in 10-year age bands)  
  - Patient Gender Distribution (Male / Female / Not Confirmed)  
  - Patient Race Distribution  
  - Number of Patients by Department Referral  
  - Patient Volume by Day and Hour (heatmap)

---

### 2️⃣ Consolidated View Dashboard

- **Purpose**: Provides a holistic view of performance across any chosen time period  
- **Time selector**: Date range slicer (from Jan 2023 onward)  
- **KPIs**:  
  - Number of Patients (monthly trend)  
  - Average Wait Time (monthly trend)  
  - Patient Satisfaction Score (monthly trend)  
  - Number of Patients Referred (monthly trend)

- **Breakdown charts**:  
  - Patient Admission Status (Admitted vs Not Admitted)  
  - % of Patients Seen by Doctor Within 30 Minutes  
  - Patient Age Distribution  
  - Patient Gender Distribution  
  - Patient Race Distribution  
  - Patient Department Referrals  
  - Patient Volume by Day and Hour (heatmap)

---

### 3️⃣ Patient Details Dashboard

- **Purpose**: Offers a granular view of patient-level details for troubleshooting and analysis  
- **Data grid includes**:  
  - Patient ID  
  - Patient Full Name  
  - Gender  
  - Age  
  - Admission Date  
  - Patient Race  
  - Patient Wait Time  
  - Department Referral  
  - Admission Status

- **Filter**: Date range slicer to narrow down the displayed patient records

---

## 📈 Key KPIs Tracked

✅ Number of Patients (daily / monthly)  
✅ Average Wait Time (minutes)  
✅ Patient Satisfaction Score  
✅ Number of Patients Referred  
✅ % of Patients Seen by Doctor within 30 Minutes  
✅ Admission Rate (admitted vs. not admitted)  
✅ Demographic breakdowns (gender, race, age group)  
✅ Department referral trends  
✅ Time-of-day and day-of-week volumes

---
---

## 💡 Insights Generation

This dashboard supports key stakeholder questions such as:  
- Which days and times have the highest ER load?  
- What is the average patient wait time, and how can it be reduced?  
- Which departments receive the most referrals from ER?  
- How satisfied are patients, and when does satisfaction drop?  
- Are there demographic groups with different admission or wait patterns?

---

## Screenshots

### 1st
![1st](https://github.com/Debjit1729/Hospital-Emergency-Room-Dashboard/blob/main/Screenshot%202025-07-05%20010104.png)

### 2nd
![1st](https://github.com/Debjit1729/Hospital-Emergency-Room-Dashboard/blob/main/Screenshot%202025-07-05%20010127.png)

### 3rd
![1st](https://github.com/Debjit1729/Hospital-Emergency-Room-Dashboard/blob/main/Screenshot%202025-07-05%20010155.png)

