# 💳 UPI Transaction Data Analysis Dashboard (Power BI)

## 🔗 Dashboard Tool
**Microsoft Power BI**

---

## 📌 Problem Statement

UPI (Unified Payments Interface) transactions generate large volumes of data across **banks, cities, devices, payment methods, and user demographics**.  
Analyzing this data manually is complex and time-consuming.

This dashboard provides a **centralized and interactive analytical view** to help:
- Track **monthly transaction trends**
- Monitor **balance movement over time**
- Analyze transactions by **city, bank, device type, gender, and purpose**
- Understand **customer spending behavior**
- Support **data-driven financial decisions**

---

## 📊 Dashboard Preview

### 🔹 Transaction Trend – Line Chart
![UPI Transaction Data Analysis](https://raw.githubusercontent.com/Pranay25o/UPI_Transaction_Data_Analysis/main/Line%20Chart.png)


### 🔹 Transaction Trend – Column Chart
![UPI Transaction Data Analysis](https://raw.githubusercontent.com/Pranay25o/UPI_Transaction_Data_Analysis/main/Column%20Chart.png)


### 🔹 Monthly Balance Trend – Line Chart
![UPI Transaction Data Analysis](https://raw.githubusercontent.com/Pranay25o/UPI_Transaction_Data_Analysis/main/Line%20Chart%20Balance.png)

### 🔹 Monthly Balance – Column Chart
![UPI Transaction Data Analysis](https://raw.githubusercontent.com/Pranay25o/UPI_Transaction_Data_Analysis/main/Column%20Chart%20Balance.png)

### 🔹 Detailed City-wise & Currency-wise Table
![City & Currency Table](https://raw.githubusercontent.com/Pranay25o/UPI_Transaction_Data_Analysis/main/City%20%26%20Currency-wise%20detailed%20table.png)



---

## 📂 Dataset Description

- **Source:** Sample UPI Transaction Dataset  
- **Format:** CSV / Excel  
- **Domain:** Digital Payments / FinTech  

### Key Fields:
- Transaction Date  
- Bank Name (Sent / Received)  
- City  
- Device Type  
- Gender  
- Age Group  
- Merchant Name  
- Payment Method  
- Transaction Type  
- Purpose  
- Transaction Amount  
- Remaining Balance  
- Currency  

---

## 🔄 Data Architecture & Flow

1. **Data Source**
   - CSV / Excel transactional data

2. **Power BI Desktop**
   - Data imported into Power BI
   - Cleaned and transformed using **Power Query**

3. **Semantic Model**
   - Relationships created
   - Business logic implemented using **DAX measures**

4. **Power BI Report**
   - Interactive visuals
   - Slicers and filters for dynamic analysis

---

## 🧹 Data Cleaning (Power Query)

Data preparation was performed using **Power Query Editor**, including:

- Removed duplicate records  
- Handled missing and null values  
- Standardized column names  
- Converted data types (numeric, date, text)  
- Created **Age Group categories**  
- Cleaned invalid transaction amounts  
- Ensured consistent city and bank naming  

---

## 📐 DAX Measures Used

DAX (Data Analysis Expressions) was used to create dynamic calculations:

- Total Transaction Amount  
- Monthly Transaction Amount  
- Remaining Balance by Month  
- Transaction Count  
- City-wise Transaction Amount  
- Purpose-wise Transaction Analysis  

These measures enable **real-time filtering and interactive insights**.

---

## 📊 Dashboard Components

### 🔹 Slicers & Filters
- Bank Name (Sent / Received)  
- City  
- Device Type  
- Gender  
- Age Groups  
- Merchant Name  
- Payment Method  
- Purpose  
- Transaction Type  

### 🔹 Visuals
- Line Chart: Transactions by Month  
- Column Chart: Transactions by Month  
- Line Chart: Balance by Month  
- Column Chart: Balance by Month  
- City & Currency-wise detailed table  

### 🔹 Navigation Buttons
- Line Chart ↔ Column Chart  
- Transaction View ↔ Balance View  

---

## 🔧 Steps Followed

1. Imported UPI transaction dataset into Power BI  
2. Cleaned data using Power Query Editor  
3. Created calculated columns and DAX measures  
4. Designed slicers for filtering  
5. Built line and column charts  
6. Created balance analysis visuals  
7. Added detailed tables  
8. Applied consistent formatting  
9. Optimized report layout  
10. Validated insights using filters  

---

## 📈 Key Insights

- Monthly transactions show significant variation  
- Certain months have sharp transaction drops and spikes  
- Balance peaks align with high transaction periods  
- Food-related transactions dominate selected filters  
- Spending behavior differs across cities and currencies  

---

## 🛠 Tools & Technologies

- Power BI Desktop  
- Power Query Editor  
- DAX (Data Analysis Expressions)  
- Excel / CSV  

---

---

## 👤 Author

**Pranay Ogale**  
Aspiring Data Analyst | Power BI | SQL | Data Visualization  

🔗 LinkedIn: https://www.linkedin.com/in/pranay-ogale/
