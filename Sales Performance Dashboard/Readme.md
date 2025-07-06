# 📈 Sales Performance Dashboard Report

## 📝 Project Title  
**Sales Performance Dashboard: Insight-Driven Sales Optimization**

---

## 📚 Table of Contents
1. [Introduction](#introduction)  
2. [Problem Statement](#problem-statement)  
3. [Objectives](#objectives)  
4. [Dataset Source](#dataset-source)  
5. [Methodology](#methodology)  
6. [Analysis](#analysis)  
7. [Dashboard Visualization](#dashboard-visualization)  
8. [Findings](#findings)  
9. [Recommendations](#recommendations)

---

## 📌 Introduction  
This project focuses on building a **Sales Performance Dashboard** to monitor and evaluate the performance of products, salespersons, and revenue across various dimensions. By leveraging **Power BI** and **Power Query**, the dashboard offers real-time, actionable insights into key sales metrics.

---

## ❗ Problem Statement  
Sales data often remains scattered and underutilized, making it difficult for decision-makers to identify high-performing sales reps, products, and revenue patterns across different regions. Without a centralized performance view, strategic decisions may be delayed or misinformed.

---

## 🎯 Objectives  
- Develop an interactive dashboard that provides a holistic view of sales performance  
- Track key performance indicators (KPIs) such as total boxes sold, revenue, and market coverage  
- Identify top-performing salespersons, products, categories, and regions  
- Enhance business decisions through data visualization and slicing/filtering options

---

## 📂 Dataset Source  
The dataset was provided internally and includes sales records containing the following fields:
- Salesperson  
- Product  
- Revenue  
- Boxes Sold  
- Region  
- Category  
- Market/Location  
- Team  

Data was imported and cleaned using **Power Query** in **Excel**.


### 📌 Dataset Preview
![Dataset Preview](https://github.com/AkinsDiaries/Excel-Projects/blob/main/Sales%20Performance%20Dashboard/DATA.png)

---

## 🔧 Methodology  

### 1. Data Cleaning & Transformation (Power Query)
- Removed blank and duplicate rows  
- Standardized column names (e.g., `sales person` → `Salesperson`)  
- Converted data types (e.g., Revenue to Decimal, Date columns to Date)  
- Replaced null values where appropriate  
- Merged supporting tables (e.g., category or team lookup)

### 2. Data Modeling
- Created relationships between tables: Sales, Product, Region, Team  
- Created DAX measures for KPIs (e.g., Total Revenue, Boxes Sold)

### 3. Data Visualization
- Built visuals with bar charts, cards, tables, and slicers  
- Used slicers to enable interactivity across Teams and Categories  


---

## 📊 Analysis  

### 📈 Sales Analysis Section
![Sales Analysis](https://github.com/AkinsDiaries/Excel-Projects/blob/main/Sales%20Performance%20Dashboard/ANALYSIS.png)

### 📌 Key Performance Indicators (KPIs)
- **Sales Source**  
- **Total Boxes Sold**  
- **Total Products Sold**  
- **Number of Active Salespersons**  
- **Market Coverage** (number of distinct regions/markets)  
- **Total Revenue**

### 🔝 Ranking Visuals
- **Top 10 Salespersons by Revenue**  
- **Top 5 Products by Revenue**  
- **Revenue by Category**  
- **Revenue by Location**  
- **Revenue by Region**

### 🎚️ Slicers
- **Team**  
- **Category**

---

## 📈 Dashboard Visualization  
The dashboard design includes:

### 📊 Sales Performance Dashboard
![Dashboard Overview](https://github.com/AkinsDiaries/Excel-Projects/blob/main/Sales%20Performance%20Dashboard/DASHBOARD.png)

---

## 🔍 Findings  
- **Top 10 salespersons** contributed to over 60% of total revenue  
- **Product X, Y, Z** led in revenue across multiple markets  
- **Region A** outperformed all others in revenue and market share  
- **Category B** dominates the product portfolio in value  
- **Team 3** showed exceptional month-over-month growth

---

## ✅ Recommendations  
- **Reward Top Performers**: Incentivize the top 10 sales reps  
- **Promote Best Products**: Focus marketing on top 5 revenue-generating products  
- **Expand into High-Growth Regions**: Scale operations in top-performing regions  
- **Evaluate Low-Performing Categories**: Consider product rebranding or retirement  
- **Upskill Underperforming Teams**: Use slicer insights to identify training needs

---

