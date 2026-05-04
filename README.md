# 📊 Loan Default Analysis Dashboard (End-to-End Power BI Project)

## 📌 Project Overview
This project is an end-to-end **Loan Default Analysis Dashboard** built using **SQL Server, Power BI Dataflows, and Power BI Desktop**.

It focuses on analyzing:
- Loan distribution & customer demographics  
- Default risk patterns  
- Financial trends (YOY & YTD)  
- Credit score & income segmentation  

The project also demonstrates **dataflow architecture, advanced DAX measures, and enterprise-level deployment**.

---

## 🛠️ Tech Stack
- **Database:** Microsoft SQL Server  
- **ETL Layer:** Power BI Dataflows  
- **Visualization:** Power BI Desktop & Service  
- **Data Processing:** Power Query  
- **Language:** SQL & DAX  

---

## 📂 Dataset
- `Loan_default.csv`  
- Column Definitions (Excel)  
- Power BI Report (`LoanDefaultReport.pbix`)  

---

## 🚀 Project Workflow

### 🔹 1. On-Premises Gateway Setup
- Installed and configured **On-Premises Data Gateway (Std)**  
- Connected local environment with Power BI Service  

<img width="786" height="803" alt="image" src="https://github.com/user-attachments/assets/a8de3a8b-35a2-426c-a8a5-55ede2f6afa2" />


---

### 🔹 2. SQL Server Setup & Data Import
- Installed Microsoft SQL Server  
- Imported loan dataset into SQL Server  
- Verified tables and schema  

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/03bbf5c7-315d-4c19-af5c-a4511ad4f82e" />


---

### 🔹 3. Dataflow Creation (Power BI Service)
- Created Dataflow in Power BI Service  
- Connected Dataflow to SQL Server  
- Loaded and structured data  

<img width="1901" height="563" alt="image" src="https://github.com/user-attachments/assets/e69734c9-b380-489c-8c05-e711af35701c" />
<img width="1912" height="976" alt="image" src="https://github.com/user-attachments/assets/431ffc7d-d138-4127-b673-52956d69d83a" />


---

### 🔹 4. Data Loading & Transformation
- Connected Power BI Desktop to Dataflow  
- Defined column metadata & descriptions  
- Performed data cleaning & profiling  
- Applied data type corrections  

<img width="1684" height="932" alt="image" src="https://github.com/user-attachments/assets/ec381d14-cbac-4f88-b654-45662ead401f" />
<img width="1901" height="1036" alt="image" src="https://github.com/user-attachments/assets/8a6a880f-cea4-4fb8-9000-8c7ae5d49735" />


---

### 🔹 5. Dashboard Development (Core Analytics)
Built interactive dashboards covering:

#### 📊 Loan & Customer Insights
- Loan Amount by Purpose  
- Average Income by Employment Type  
- Default Rate by Employment Type  
- Average Loan by Age Group  

#### 📊 Risk & Trend Analysis
- Default Rate by Year  
- YOY Loan Amount Change  
- YOY Default Loan Change  
- YTD Loan Analysis  

#### 📊 Customer Segmentation
- Median Loan by Credit Score Category  
- Loan Distribution by Credit Score Bins  
- Loan by Marital Status & Age Group  
- Loans by Education Type  

#### 📊 Advanced Visuals
- Donut Charts  
- Line Charts (YOY trends)  
- Clustered Column Charts  
- Decomposition Tree  

<img width="1172" height="651" alt="image" src="https://github.com/user-attachments/assets/6f10ba87-0d1d-453e-b86e-8f9f4f0e35ca" />




---

### 🔹 6. DAX Measures & Calculations
Implemented advanced DAX functions:
- `CALCULATE()`, `SUMX()`, `AVERAGEX()`  
- `MEDIANX()`, `FILTER()`  
- `ALL()`, `ALLEXCEPT()`  
- `DIVIDE()`, `COUNTROWS()`  
- `SWITCH()`  

Used for:
- Default rate calculation  
- YOY/YTD metrics  
- Median & average analysis  
- Segmentation logic  

📸 *Add DAX screenshots here*

---

### 🔹 7. Data Validation
- Validated calculated measures  
- Verified visual outputs  
- Ensured consistency across dashboard  

📸 *Add screenshots here*

---

### 🔹 8. Deployment & Data Refresh
- Configured Dataflow refresh schedule  
- Implemented Incremental Refresh  
- Published report to Power BI Service  
- Scheduled report refresh  

📸 *Add screenshots here*

---

### 🔹 9. Report Sharing
- Shared report via Power BI Service  
- Managed access for stakeholders  

📸 *Add screenshots here*

---

## 📊 Key Insights
- Default rates remain stable (~11–12%) across years  
- Income groups drive majority of loan distribution  
- Credit score significantly impacts loan patterns  
- YOY trends highlight fluctuations in financial risk  

---

## 🔐 Features Implemented
- Dataflow-based architecture  
- Incremental refresh optimization  
- Advanced DAX analytics  
- Interactive dashboard design  

---

## 📈 Future Improvements
- Predictive modeling for default risk  
- Real-time data integration  
- ML-based segmentation  

---

## 📎 Project Files
- `Loan_default.csv`  
- `Column Definitions.xlsx`  
- `LoanDefaultReport.pbix`  

---

## ▶️ How to Run
1. Import dataset into SQL Server  
2. Create Dataflow in Power BI Service  
3. Connect Power BI Desktop to Dataflow  
4. Open `.pbix` file  
5. Refresh & publish  

---
