# blinkit-delivery-analysis
Blinkit delivery performance and operational delay analysis using Excel.


# Blinkit Delivery Performance & Operational Delay Analysis

## 📌 Project Overview

This project analyzes Blinkit's delivery performance to identify the key operational factors contributing to delivery delays.

The analysis focuses on different stages of the delivery process, including picking, packing, rider assignment, rider waiting, and final delivery time.

The project was developed using Microsoft Excel to perform data analysis, create PivotTables, identify trends, and build an interactive dashboard.

---

## ⭐ Project Highlights

- Analyzed **240 delivery orders** to understand operational delays.
- Identified **13.57 minutes** as the average peak-hour delivery time compared with **11.67 minutes** during non-peak hours.
- Found rider assignment time increased to **1.89 minutes** during peak hours.
- Identified **19:00–22:00** as a key period for delivery delays.
- Evaluated store-level performance and peak-hour rider availability.
- Built an interactive Excel dashboard with **Hour, Store, and City slicers**.
- Converted analytical findings into actionable operational recommendations.

--- 

## 🎯 Business Problem

Blinkit aims to provide fast delivery to customers. However, delivery time can increase during certain periods and locations.

The main business questions addressed in this project are:

- Why does delivery time increase during peak hours?
- Which operational stage contributes most to delivery delays?
- Which stores experience higher delivery delays?
- Does rider availability affect delivery performance?
- When should additional riders be positioned?
- What operational improvements can reduce delivery delays?

---

## 🛠️ Tools Used

- Microsoft Excel
- PivotTables
- Excel Charts
- Slicers
- Data Cleaning
- Exploratory Data Analysis
- Dashboard Development

---

## 📊 Key Metrics

The analysis focuses on:

- Total Orders
- Average Delivery Time
- Peak Delivery Time
- Rider Assignment Time
- Rider Waiting Time
- Picking Time
- Packing Time
- Delivery Time
- Peak Orders per Active Rider

---

## 🔄 Analysis Workflow

The analysis followed a structured data analytics workflow:

1. **Data Preparation**
   - Reviewed the order-level delivery dataset.
   - Checked the available delivery process metrics.
   - Prepared the data for analysis.

2. **Exploratory Data Analysis**
   - Analyzed delivery performance by week.
   - Compared peak and non-peak periods.
   - Analyzed delivery time by hour.
   - Compared performance across stores and cities.

3. **Operational Analysis**
   - Examined rider assignment time.
   - Examined rider waiting time.
   - Compared peak orders with active rider availability.
   - Investigated relationships between operational factors and delivery time.

4. **Dashboard Development**
   - Created KPI cards.
   - Built charts for trends and comparisons.
   - Added interactive slicers for Hour, Store, and City.

5. **Business Recommendations**
   - Identified operational bottlenecks.
   - Recommended improvements to rider allocation and dispatch.
   - Recommended further investigation of store handoff and readiness processes.
     
---

## 📁 Dataset Structure

The project uses two main datasets:

### Delivery Data

Contains order-level delivery information and operational time metrics such as:

- Order ID
- Date
- Store ID
- City
- Picking Time
- Packing Time
- Rider Assignment Time
- Rider Waiting Time
- Delivery Time
- Total Delivery Time

### Store Data

Contains store-level operational information including:

- Store ID
- City
- Store Capacity
- Active Riders
- Peak-hour Orders

These datasets were used together to analyze delivery performance and investigate operational delays.

---

## 🔎 Key Findings

### 1. Peak-hour delivery delays

Average delivery time during peak hours was **13.57 minutes**, compared with **11.67 minutes** during non-peak hours.

This indicates that peak-hour delivery performance is significantly slower.

### 2. Rider assignment is a major contributor

Average rider assignment time increased from **1.04 minutes during non-peak hours** to **1.89 minutes during peak hours**.

This suggests that rider assignment and dispatch efficiency are important areas for investigation.

### 3. Rider waiting also increases

Average rider waiting time increased from **0.74 minutes** during non-peak hours to **1.03 minutes** during peak hours.

This indicates potential issues around store readiness and rider-store handoff.

### 4. Evening hours show higher delays

The analysis identified **19:00–22:00** as an important period where delivery times and rider-related delays increase.

### 5. Rider capacity alone does not explain delays

The correlation between peak orders per active rider and rider assignment time was approximately **0.15**.

This is a weak positive relationship, suggesting that rider workload alone does not fully explain assignment delays.

---

## 💡 Recommendations

Based on the analysis, the following actions are recommended:

1. **Optimize rider allocation during 19:00–22:00**
   
   Position additional riders at stores experiencing high peak demand and operational delays.

2. **Improve rider assignment and dispatch**
   
   Investigate the rider assignment process to reduce the time required to assign riders to orders.

3. **Investigate store handoff processes**
   
   Analyze whether delays in picking, packing, or order readiness are causing riders to wait.

4. **Monitor store-level performance**
   
   Identify stores with consistently high delivery times and rider waiting times and investigate their operational processes.

---

## 📈 Dashboard

The Excel dashboard provides an interactive view of delivery performance using:

- KPI cards
- Weekly delivery trends
- Peak vs non-peak analysis
- Evening-hour analysis
- Store performance
- City and store slicers
- Hour-based filtering

---
### Dashboard Preview

The dashboard provides an interactive view of delivery performance across time, stores, and cities.

![Blinkit Delivery Performance Dashboard](screenshots/blinkit-dashboard.png)

---

## 📌 Project Outcome

The analysis identified peak-hour rider assignment and waiting time as important operational areas affecting delivery performance.

The findings suggest that improving rider allocation, dispatch efficiency, and store handoff processes during high-demand evening periods could help reduce delivery delays.

---

## 💼 Skills Demonstrated

- Data Cleaning & Preparation
- Exploratory Data Analysis
- Excel PivotTables
- Excel Charts & Visualization
- Interactive Dashboard Development
- Slicer-based Analysis
- KPI Development
- Trend Analysis
- Operational Performance Analysis
- Business Insight Generation
- Data-driven Recommendations

---

## 📂 Project Files

The repository contains:

- Excel analysis file
- Dashboard screenshots

---

## 👩‍💻 My Role

I independently performed the data preparation, exploratory analysis, PivotTable analysis, dashboard development, and business interpretation for this project.

---

## 👩‍💻 Author

**Vaishnavi Dahilkar**

Data Analyst | Excel | Data Analysis
