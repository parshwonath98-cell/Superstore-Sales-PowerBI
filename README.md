# 🛒 Superstore Sales Analytics: Retail Performance Dashboard

A dynamic, interactive Power BI dashboard built to explore and analyze retail sales data from a global superstore — focusing on revenue performance, profitability, delivery efficiency, customer segments, and category-level trends.

---

## 📌 Short Description

The Superstore Sales Dashboard is a visually engaging Power BI report designed to help users explore sales and profit performance across product categories, customer segments, shipping modes, and US states. This tool is intended for retail analysts, business strategists, and data enthusiasts seeking actionable insights from transactional retail data.

---

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization platform used for report creation
- 📂 **Power Query** – Data transformation and cleaning layer for reshaping and preparing the data
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, KPI cards, and YoY comparisons
- 📝 **Data Modeling** – Relationships established among tables to enable cross-filtering and aggregation
- 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews

---

## 📂 Data Source

**Source:** Sample Superstore Dataset (widely used in BI and analytics education)

Data covers retail transactions including order details, customer segments, product categories, shipping modes, and geographic distribution across US states and regions — spanning the years 2019 and 2020.

---

## ✨ Features / Highlights

### 🔴 Business Problem
Retail managers and analysts often struggle to get a unified view of sales health across multiple dimensions simultaneously. Key questions such as:
- Which product categories and sub-categories drive the most revenue?
- How does profitability vary across customer segments and regions?
- What is the average delivery time and how does shipping mode impact sales?
- Which states contribute most to overall sales and profit?

...are difficult to answer quickly from raw transactional data.

### 🎯 Goal of the Dashboard
To deliver an interactive visual tool that:
- Enables users to monitor top-line KPIs at a glance
- Supports decisions around inventory, marketing, and logistics
- Uncovers trends in category performance, regional contribution, and delivery efficiency

### 🖥️ Walkthrough of Key Visuals

**KPI Cards (Top Center)**
- Total Sales: **1.57M**
- Total Profit: **175.26K**
- Average Delivery Time: **3.93 days**

**Region Filter Panel**
An interactive slicer lets users filter all visuals by region — Central, East, South, and West.

**Monthly Profit by YoY (Line Chart)**
Tracks monthly profit trends across 2019 and 2020, revealing seasonal patterns and growth trajectories.

**Monthly Sales by YoY (Line Chart)**
Side-by-side year comparison of monthly sales volume to identify peak periods and growth months.

**Sales by Category / Shipping Mode (Bar Chart)**
Ranks shipping modes — Standard Class, Second Class, First Class, Same Day — by total sales contribution.

**Top 5 Sub-Categories by Sales (Bar Chart)**
Highlights the highest-revenue sub-categories: Phones, Chairs, Binders, Storage, and Accessories.

**Sales by Segment (Donut Chart)**
Breaks down revenue by customer segment — Consumer (48%), Corporate (33%), Home Office (19%).

**Sales by Payment Mode (Donut Chart)**
Visualizes payment preferences — COD (43%), Online (35%), Cards (22%).

**Sales and Profit by State (Map)**
Geographic bubble map showing state-level sales and profit distribution across the US.

**Sales by Category — Product (Bar Chart)**
Compares the three main product categories — Office Supplies (0.64M), Technology (0.47M), Furniture (0.45M).

### 💡 Business Impact & Insights
- **Inventory Planning:** Office Supplies leads in sales volume — signals high reorder frequency and stock priority
- **Logistics Optimization:** Average delivery of 3.93 days with COD dominating at 43% suggests scope for digital payment incentivization
- **Segment Strategy:** Consumer segment drives nearly half of all revenue — targeted retention campaigns could significantly impact top-line growth
- **Regional Focus:** The region slicer enables territory managers to drill into their specific performance without noise from other regions

---

## 📸 Screenshots

![Dashboard Preview](your-screenshot-filename.png)

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository
2. Open it in **Power BI Desktop** (free download from Microsoft)
3. Use the **Region slicer** on the left to filter by geography
4. Hover over any visual for detailed tooltips
