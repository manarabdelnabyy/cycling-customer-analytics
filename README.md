# 🚴‍♂️ Bike Sales Dashboard

This project showcases a **Bike Sales Dashboard** built in Excel to analyze customer purchasing behavior, demographics, and income levels.

---

## 📊 Project Overview
The purpose of this project is to analyze raw sales data and create an interactive dashboard that provides insights into:
- Customer demographics (age ranges, education, marital status, region)
- Average income by gender and purchase decision
- Distance traveled per customer
- Customer purchasing behavior

---

## 🛠 Data Cleaning & Preparation
Steps performed on the raw dataset:
1. Removed duplicates to ensure data accuracy.
2. Created a new **Age Range column** to categorize customers:
   - Child  
   - Young Adult  
   - Adult  
   - Middle Age  
   - Senior  
3. Ensured data consistency (e.g., formatting income values).
4. Prepared Pivot Tables for dashboard visualizations.

---

## 📈 Dashboard Features
The final dashboard includes:
- **Age ranges per #customers**: Line chart showing distribution by age groups.
- **Average income per gender & purchase**: Bar chart comparing male vs. female average income with purchase status.
- **Distance per customers**: Line chart analyzing commute distance effect on purchases.
- Filters (Slicers) for:
  - Marital status
  - Education
  - Region
  - Gender

---

## 📂 Files
- `data/bike_sales_raw.xlsx` → The original raw dataset.
- `data/bike_sales_dashboard.xlsx` → Cleaned dataset with pivot tables and the final dashboard.
- `images/dashboard_preview.jpg` → Dashboard preview.

---

## 🚀 How to Use
1. Open `bike_sales_dashboard.xlsx` in Microsoft Excel.
2. Use the slicers to interact with the dashboard.
3. Explore insights on customer demographics, income, and purchasing behavior.

---

## 📌 Tools Used
- **Excel**: Data cleaning, Pivot tables, Dashboard design

---

## 📷 Dashboard Preview
![Dashboard Preview](images/dashboard_preview.jpg)


bike-sales-dashboard/
│
├── data/
│   ├── bike_sales_raw.xlsx         
│   └── bike_sales_dashboard.xlsx   
│
├── images/
│   └── dashboard_preview.jpg       
│
└── README.md

