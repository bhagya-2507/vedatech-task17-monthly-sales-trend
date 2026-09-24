# 📊 Monthly Sales Trend Analysis — VedaTech Task 17

![Excel](https://img.shields.io/badge/Excel-Data%20Analysis-green)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Monthly%20Sales-blue)
![VedaTech](https://img.shields.io/badge/VedaTech-Task%2017-orange)

## 📌 Project Overview

This project was completed as part of **VedaTech Data Analytics Track – Task 17**.

The objective of this task was to **summarize sales by month and visualize the monthly sales trend** using Microsoft Excel.

The analysis focuses on date grouping, monthly aggregation, chronological ordering, and time-series visualization.

---

## 🎯 Objective

- Summarize total sales for each month.
- Group sales data by month.
- Maintain months in chronological order from January to December.
- Create a monthly sales summary table.
- Visualize the sales trend using a Line Chart.
- Identify important patterns and insights from the monthly sales data.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- Excel Formulas
- Data Formatting
- Data Aggregation
- Line Chart
- Date & Time Grouping

---

## 📂 Dataset

The dataset contains retail sales records with the following fields:

| Column | Description |
|---|---|
| Order Date | Date of the sales transaction |
| Product | Product sold |
| Category | Product category |
| Sales | Sales amount |
| Month | Extracted month from Order Date |

---

## 📊 Analysis Performed

### 1. Date Formatting
The `Order Date` column was converted and formatted correctly to ensure accurate date handling.

### 2. Month Extraction
A separate `Month` column was created using the Order Date.

### 3. Monthly Sales Calculation
Monthly sales were calculated using Excel's `SUMIF` function.

### 4. Chronological Sorting
Months were arranged correctly:

**Jan → Feb → Mar → Apr → May → Jun → Jul → Aug → Sep → Oct → Nov → Dec**

### 5. Data Visualization
A **Line Chart** was created to visualize changes in sales across the months.

---

## 📈 Monthly Sales Summary

| Month | Total Sales |
|---|---:|
| January | ₹5,631.63 |
| February | ₹6,924.21 |
| March | ₹5,765.65 |
| April | ₹7,376.35 |
| May | ₹5,231.15 |
| June | ₹5,636.20 |
| July | ₹7,125.85 |
| August | ₹5,640.95 |
| September | ₹5,331.05 |
| October | ₹5,606.05 |
| November | ₹9,131.30 |
| December | ₹6,640.95 |

---

## 💡 Key Insights

- November recorded the highest monthly sales at **₹9,131.30**.
- May recorded the lowest monthly sales at **₹5,231.15**.
- Monthly sales show noticeable fluctuations throughout 2025.
- The Line Chart makes monthly sales movements easier to identify.
- Total recorded sales for the year were **₹76,041.34**.

---

## 📈 Visualization

The project includes a **Monthly Sales Trend Line Chart** showing sales performance from January to December 2025.

The chart includes:
- Month-wise sales
- Data markers
- Sales values
- Month axis
- Total Sales axis

---

## 📁 Project Structure

```text
vedatech-task17-monthly-sales-trend/
│
├── Monthly_Sales_Trend.xlsx
├── README.md
