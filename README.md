# 🛒 Order & Sales Performance Analytics Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-blue)

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Data Source](#data-source)
- [Technology & Implementation](#technology--implementation)
- [Usage](#usage)
- [Screenshots / Demos](#screenshots--demos)
- [Benefits](#benefits)
- [Future Enhancements](#future-enhancements)
- [Author](#Author)

---

## 📊 Overview
This repository contains an **interactive Power BI dashboard** that provides a comprehensive view of **sales and order performance**. It includes insights into sales by region, category, segment, payment mode, and shipping metrics, along with a **15-day sales forecast** for future planning.  

The dashboard is designed to help business stakeholders make **data-driven decisions** and track sales trends, profits, and operational efficiency in a single, interactive view.

---

## ⚡ Features

### Interactive Dashboard Visualizations
1. **Sales by Payment Mode** – Pie chart showing the distribution of sales by payment method.  
2. **Sales by Region** – Pie chart visualizing the contribution of each region.  
3. **Sales by Segment** – Pie chart for customer segment analysis.  
4. **Orders, Sales, Profit, Ship Days** – KPI cards highlighting key metrics.  
   - *Ship Days* is calculated using a **DAX column `Average Delivery`** that computes the average delivery duration.  
5. **Monthly Sales (YoY)** – Stacked area chart comparing 2019 and 2020 monthly sales.  
6. **Monthly Profit (YoY)** – Stacked area chart comparing 2019 and 2020 profits.  
7. **Profit & Sales by State** – Interactive map displaying state-level performance.  
8. **Sales by Ship Mode** – Clustered bar chart analyzing shipping efficiency.  
9. **Sales by Category & Sub-Category** – Clustered bar charts providing product-level insights.  
10. **Regional Slicer** – Filter dashboard by Central, East, South, and West regions. Selecting a region dynamically updates all visuals including the map.  

### Forecast Sheet (15-Day Sales Forecast)
- Uses **DAX queries** to generate a summarized table with:
  - **Order Date** (unique dates)  
  - **Total Sales** on each summarized date  
- Provides **short-term sales predictions** for 15 days to assist in inventory and sales planning.

---

## 🗄️ Data Source
The dashboard pulls data from a **CSV file** with the following columns:

| Column Name       | Description |
|------------------|-------------|
| Row ID            | Unique identifier for each row |
| Order ID          | Unique order reference |
| Order Date        | Date when the order was placed |
| Ship Date         | Date when the order was shipped |
| Ship Mode         | Mode of shipment |
| Customer ID       | Unique customer identifier |
| Customer Name     | Customer's name |
| Segment           | Customer segment (Consumer, Corporate, Home Office, etc.) |
| Country           | Customer country |
| City              | Customer city |
| State             | Customer state |
| Region            | Region (Central, East, South, West) |
| Product ID        | Unique product identifier |
| Category          | Product category |
| Sub-Category      | Product sub-category |
| Product Name      | Product description |
| Sales             | Total sales value |
| Quantity          | Quantity sold |
| Profit            | Profit amount |
| Returns           | Returned quantity/value |
| Payment Mode      | Payment method used |

---

## 🛠️ Technology & Implementation
- **Tool Used:** Power BI Desktop  
- **Data Source:** CSV file  
- **Analytics:** DAX queries for:
  - Calculating **Average Delivery**  
  - Generating **forecast table for 15 days**  
- **Visualizations:** Pie charts, stacked area charts, clustered bar charts, KPI cards, and map charts  
- **Interactivity:** Slicers to filter data by region with dynamic updates to all charts  

---

## 🚀 Usage
1. Open the **Power BI file (`.pbix`)** in Power BI Desktop.  
2. Ensure the CSV data source is in the same directory or update the file path.  
3. Explore the dashboard using slicers and filters to analyze performance by region, segment, and category.  
4. Navigate to the **Forecast Sheet** to view the predicted sales for the next 15 days.  

---

## 🖼️ Screenshots / Demos 

Dashboard Overview 
<img width="1325" height="741" alt=" Order   Sales Performance Analytics Dashboard" src="https://github.com/user-attachments/assets/9dc52f0d-97c8-4ecb-83fb-191a3d590c86" />


Forecast Sheet
<img width="1324" height="741" alt="Sales Performance Forecast - 15 Days Forecast" src="https://github.com/user-attachments/assets/65c01519-bcbc-4661-80ee-f50f57df3cc2" />

---


🎯 Benefits
* Monitor sales performance across multiple dimensions.

* Track profitability and operational efficiency.

* Identify top-performing products, segments, and regions.

* Leverage short-term forecasts to plan inventory and optimize sales.

---

🔮 Future Enhancements
* Implement real-time data updates from APIs or databases.

* Include long-term forecasting models using advanced machine learning.

* Add trend analysis for returns and customer behavior.
  
---

👨‍💻 Author

Souvik Bose
- 🌐 [LinkedIn](https://www.linkedin.com/in/souvik-bose-7272ab1b3/)
