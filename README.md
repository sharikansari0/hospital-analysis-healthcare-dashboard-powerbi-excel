# 🏥 Hospital Analytics & Healthcare Dashboard (Power BI + Excel)

A complete end-to-end **Healthcare Analytics Dashboard** built using **Excel, Power Query, DAX, and Power BI**, designed to analyze patient workflow, diagnosis trends, bed occupancy, doctor feedback, billing, and health insurance performance across 7,157 records.

---

## 📊 Key Insights

- **Total Records Analyzed:** 7,157  
- **Peak Bed Occupancy:** Private wards (3.6K)  
- **Top Diagnosis:** Viral Infection (2,004 cases)  
- **Lowest Diagnosis:** Fracture (287 cases)  
- **Feedback Volume:** Highest feedback received by Dr. Jay Sinha  
- **Billing Amount:** Higher than Insurance Amount across all diagnosis types  
- **Patient Journey:** Clear Admit → Discharge → Follow-up timeline  
- **Feedback Trend:** Even distribution but identifies doctors with high patient load  

These insights help hospitals optimize operations, patient care, resource allocation, and revenue cycle management.

---

## 📝 Overview

Healthcare systems generate massive patient and operational data every day.  
This dashboard provides a **360° operational view** of hospital performance—covering patient journey, ward occupancy, doctor efficiency, diagnosis distribution, and financial performance.

The purpose of this project is to simulate **real-world hospital operations analytics** and practice building advanced Power BI dashboards for the healthcare domain.

---

## 🎯 Problem Statement

Hospitals face multiple data challenges:

1. No clear visibility into patient journey metrics (Admit → Discharge → Follow-up).  
2. Difficulty monitoring **bed occupancy** across Private, General, and ICU wards.  
3. Lack of analytical insights on **doctor-wise feedback** and performance.  
4. No structured view of diagnosis trends (which diseases increase demand).  
5. Billing vs Insurance mismatch leading to financial leakage.  
6. Manual reporting wastes time and reduces operational efficiency.

This dashboard solves these by offering a fully automated, interactive BI system.

---

## 📂 Dataset

- **Source:** Sample hospital operational dataset  
- **Total Rows:** 7,157  
- **Format:** Excel Workbook (Raw Data)

### **Columns Used in Dashboard**
- Patient_ID  
- Admit_Date  
- Discharge_Date  
- Diagnosis  
- Bed_Occupancy  
- Doctor  
- Followup_Date  
- Feedback  
- Billing_Amount  
- Health_Insurance_Amount  

*(Note: Column ‘Test’ exists in dataset but not used in dashboard.)*

---

## 🧰 Tools & Technologies

- **Excel** → Raw data cleaning  
- **Power Query** → Transformations & ETL  
- **Power BI** → Dashboard creation  
- **DAX** → Calculated KPIs, Measures  
- **Data Modeling** → Logical structure for analytics  

---

## 🔧 Methods & Approach

### **Data Cleaning (Excel + Power Query)**
- Removed blanks & null values  
- Converted date formats  
- Controlled datatype mismatches  
- Reduced inconsistencies in diagnosis & doctor names  
- Normalized billing & insurance fields  

### **Data Modeling**
- Single fact table with date intelligence  
- DAX measures for billing, feedback, count of diagnosis, occupancy  

### **DAX Calculations**
- Total Billing  
- Total Insurance  
- Diagnosis Count  
- Feedback Count  
- Bed Occupancy Distribution  

---

## 📊 Dashboard Features

### **1️⃣ Patient Journey Timeline**
Admit date → Discharge date → Follow-up date  
Helps measure patient cycle time.

### **2️⃣ Bed Occupancy Distribution**
Breakdown of Private, General, ICU ward usage.

### **3️⃣ Doctor Feedback Volume**
Shows which doctor receives the most feedback (workload indicator).

### **4️⃣ Diagnosis Trends**
Top diseases such as Viral Infection, Flu, Malaria, Typhoid, Pneumonia.

### **5️⃣ Billing vs Insurance Comparison**
Diagnosis-wise financial gap visualization.

### **6️⃣ Hospital Revenue Insights**
Billing overview with healthcare financial metrics.

---

## 📁 Folder Structure

hospital-analysis-healthcare-dashboard-powerbi-excel/
│
├── README.md
├── data/
│ └── healthcare_raw_data.xlsx
│
├── dashboard/
│ └── healthcare_dashboard.pbix
│
└── image/
   |___
       dashboard_image

---

## 📌 Results & Conclusion

This dashboard enables hospitals to:

- Optimize bed usage  
- Monitor diagnosis trends  
- Improve patient flow  
- Identify overloaded doctors  
- Track revenue leakage  
- Enhance data-driven decision-making  
- Improve operational efficiency and hospital performance  

---

## 🚀 Future Enhancements

- Predict future bed occupancy  
- Patient satisfaction scoring model  
- Diagnostic forecasting  
- Department-level profitability  
- Integration with SQL database  
- Automate refresh using Power BI Service  

---

## 👤 Author & Contact

**Sharik Ansari**  
📧 Email: sharikkha8900@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/sharikansari  
🐙 GitHub: https://github.com/sharikansari0  

---

## ⭐ Support  
If you found this project helpful, please give it a ⭐ on GitHub!

