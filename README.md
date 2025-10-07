# 🚴‍♂️ Bike Sales Dashboard (Excel Project)

## 📘 Overview
The **Bike Sales Dashboard** is a data analysis project built using **Microsoft Excel** to explore customer demographics and bike purchase patterns.  
It provides valuable insights into how factors such as **age, gender, income, region, and commute distance** influence bike purchasing decisions.

---

## 🎯 Objective
- Analyze and visualize bike sales data to understand customer buying behavior.  
- Identify key trends affecting bike purchases.  
- Create an **interactive and visually appealing dashboard** using Excel.

---

## 🧩 Dataset Information

## 📂 Dataset Information

| Column Name | Description | Example |
|--------------|-------------|----------|
| **ID** | Unique identifier for each customer | 1001 |
| **Marital Status** | Marital status of the customer | Married / Single |
| **Gender** | Gender of the customer | Male / Female |
| **Income** | Annual income (in USD) | 45000 |
| **Children** | Number of children | 2 |
| **Education** | Highest level of education | Bachelors / Graduate Degree |
| **Occupation** | Profession of the customer | Skilled Manual / Professional / Clerical |
| **Home Owner** | Whether the customer owns a home | Yes / No |
| **Cars** | Number of cars owned | 1 |
| **Commute Distance** | Distance from home to work | 0–1 Miles / 1–2 Miles / 2–5 Miles / 5–10 Miles / 10+ Miles |
| **Region** | Geographical region of residence | North America / Europe / Pacific |
| **Age** | Age of the customer | 38 |
| **Age Brackets** | Categorized age groups for analysis | <30 / 30–40 / 40–50 / >50 |
| **Purchased Bike** | Indicates whether the customer purchased a bike | Yes / No |

📂 *Dataset file:* `Bike_Buyers.csv`

---

## 🛠 Tools & Skills Used
- **Microsoft Excel**
  - Data Cleaning (Remove duplicates, handle missing data)
  - Data Transformation (Create calculated columns)
  - Pivot Tables & Pivot Charts
  - Slicers for interactivity
  - Conditional Formatting
  - Data Visualization & Dashboard Design

---

## 📈 Dashboard Features

✅ **KPIs / Summary Metrics**
- Total Customers  
- Total Bikes Purchased  
- Purchase % by Gender  
- Average Income of Buyers  

✅ **Visual Insights**
- Bike Purchase by Age Group  
- Income vs. Purchase Decision  
- Commute Distance and Bike Purchase  
- Purchase Distribution by Region  

✅ **Interactive Filters (Slicers)**
- Gender  
- Region  
- Marital Status  

---

## 🔧 Steps to Build the Dashboard

### 1. Data Cleaning
- Import the dataset (`Bike_Buyers.csv`) into Excel.  
- Remove blank and duplicate rows.  
- Format data types appropriately.  
- Create an **Age Bracket** column using a nested IF formula:
  ```excel
  =IF(Age<30,"<30",IF(Age<=40,"30-40",IF(Age<=50,"40-50",">50")))
