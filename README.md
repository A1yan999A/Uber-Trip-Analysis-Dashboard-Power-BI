# Uber-Trip-Analysis-Dashboard-Power-BI
🚖 Interactive Power BI dashboard developed to analyse Uber trip data including booking trends, revenue insights, trip efficiency, vehicle performance, location intelligence, and time-based demand analysis using DAX, data modeling, drill-through, bookmarks, and dynamic KPI selection.


## 📌 Project Overview

This project focuses on analysing Uber trip data using Power BI to generate business insights related to booking trends, revenue generation, trip efficiency, customer behavior, and operational performance.

The dashboard enables stakeholders to monitor ride demand, analyse revenue trends, identify peak booking periods, and optimize operational strategies through interactive visualizations and advanced analytics.

---

# 📊 Dashboard Pages

## 1️⃣ Overview Analysis Dashboard

Provides a high-level overview of Uber trip performance and operational KPIs.

### KPIs Included
- Total Bookings
- Total Booking Value
- Average Booking Value
- Total Trip Distance
- Average Trip Distance
- Average Trip Time

### Visualizations
- Total Bookings by Payment Type
- Total Bookings by Trip Type (Day/Night)
- Total Bookings by Day
- Vehicle Type Analysis
- Top 5 Booking Locations
- Most Frequent Pickup Point
- Most Frequent Drop-off Point
- Farthest Trip Analysis
- Most Preferred Vehicle Type

---

## 2️⃣ Time Analysis Dashboard

Focused on analysing trip demand across different time intervals.

### Visualizations
- Total Booking by Pickup Time (10-Minute Interval Area Chart)
- Total Booking by Pickup Day (Line Chart)
- Day & Hour Heatmap Analysis

### Key Insights
- Peak booking hours identification
- Weekday vs weekend demand analysis
- High-demand operational periods
- Ride trend fluctuations across time

---

## 3️⃣ Details Dashboard

Provides detailed trip-level records for granular analysis.

### Features
- Drill-through functionality
- Interactive filtering
- Detailed transaction records
- Full data exploration

---

# 🛠️ Power BI Features Used

## Data Modeling
- Star Schema Data Modeling
- Fact & Dimension Tables
- Relationship Management
- Inactive Relationship Handling

## DAX Functions
- CALCULATE()
- SUM()
- SUMX()
- DIVIDE()
- SELECTEDVALUE()
- USERELATIONSHIP()

## Power BI Functionalities
- Dynamic Measure Selector
- Dynamic Titles
- Drill-through
- Bookmarks
- Conditional Formatting
- Interactive Slicers
- Heatmap Visualization
- Tooltips

---

# 🧩 Data Model Architecture

## Fact Table
### Uber_Trip_Details
Contains transactional trip-level data such as:
- Fare Amount
- Passenger Count
- Pickup Time
- Trip Distance
- Vehicle Type
- Payment Type

## Dimension Tables
### Calendar_Table
Used for:
- Date Analysis
- Day-wise Reporting
- Time Intelligence

### Location_Table
Used for:
- Pickup & Drop-off Analysis
- City Filtering
- Location Intelligence

## Supporting Table
### New_Parameter
Disconnected table used for:
- Dynamic KPI Selection
- Dynamic Chart Titles

---

# 📈 Business Insights Generated

- UberX was identified as the most preferred vehicle category.
- Peak booking demand occurred during afternoon and evening hours.
- Day trips contributed higher booking volumes compared to night trips.
- Specific pickup and drop-off locations generated maximum bookings.
- Time-based heatmaps highlighted peak operational demand periods.
- Revenue and booking trends varied significantly across weekdays.

---

# 🚀 Key Learnings

- Built dynamic KPI switching using disconnected tables.
- Developed advanced DAX measures for interactive reporting.
- Implemented Star Schema data modeling.
- Created time-based and location-based analytical dashboards.
- Improved dashboard navigation using bookmarks and drill-through.

---

# 🛠️ Tools & Technologies

- Power BI Desktop
- DAX
- Power Query
- Data Modeling
- Excel / CSV Dataset

---

# 📂 Project Structure

Uber-Trip-Analysis-PowerBI/
│
├── Dashboard Screenshots/
│   ├── overview.png
│   ├── Time Analysis.png
│   ├── details.png
│   └── Data Model.png
│
├── Dataset/
│   └── Uber Trip Details.CSV
|    └──Location Table.CSV
│
├── Uber_trip
|        └──Problem Statement.docx
|         └──Uber_trip.pbix
│
└── README.md


# 🔗 Project Highlights

✔ Dynamic KPI Switching  
✔ Interactive Dashboards  
✔ Heatmap Analysis  
✔ Drill-through Reporting  
✔ Dynamic Titles  
✔ Star Schema Modeling  
✔ Advanced DAX Calculations  
✔ Location Intelligence Analysis  
✔ Time-Based Trend Analysis  


# 📌 Conclusion

The Uber Trip Analysis Dashboard successfully transforms raw trip-level data into meaningful business insights using Power BI.

This project demonstrates:
- Business Intelligence Reporting
- Data Visualization
- Advanced DAX
- Data Modeling
- Interactive Dashboard Development
- Analytical Problem Solving
