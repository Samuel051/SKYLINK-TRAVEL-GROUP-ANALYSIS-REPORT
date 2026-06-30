# SKYLINK-TRAVEL-GROUP-ANALYSIS-REPORT
# ✈️ Skylink Travel Analytics Dashboard

## 📖 Project Overview

This project was completed as part of the **June ZoomCharts Data Visualization Challenge**, where participants were tasked with analyzing a travel booking dataset using Power BI.

The objective was to transform raw travel booking data into an interactive dashboard capable of answering key business questions while providing actionable recommendations for revenue growth, customer segmentation, airline performance, booking channel effectiveness, and travel trends.

The project follows the complete analytics lifecycle—from data preparation and modeling to visualization and business recommendations.

---

## 🎯 Business Objectives

This project aimed to answer the following business questions:

- Which destinations generate the highest revenue?
- How do travel patterns change over time?
- Which traveler segments contribute the most revenue?
- Which airline partners drive the greatest profitability?
- Which booking channels perform best?
- What opportunities exist for increasing future revenue?

---

## 🛠️ Tools Used

- Power BI
- Power Query
- DAX
- Microsoft Excel

---

## 📂 Data Preparation (ELT)

An **ELT (Extract, Load, Transform)** workflow was followed to ensure the dataset was clean and analysis-ready.

### Data Cleaning

- Standardized airline names using a mapping table.
- Converted Excel serial dates into proper date format.
- Merged first and last names into a single Traveler Name field.
- Removed leading and trailing spaces.
- Standardized categorical values.
- Investigated missing values.
- Validated ticket prices.
- Created calculated columns for Route and Flight Type.

### Data Modeling

- Built a Date Dimension for time intelligence.
- Created relationships between tables.
- Developed reusable DAX measures for KPIs and business analysis.

---

## 📊 Dashboard Pages

### 1. Executive Summary

- Overall KPIs
- Revenue Trends
- Domestic vs International Performance
- Travel Purpose Analysis
- Executive Insights
- Strategic Recommendations

---

### 2. Time Intelligence

- Revenue Trend
- Booking Trend
- Monthly Seasonality
- Weekday Performance
- Revenue Heatmap

---

### 3. Routes & Destinations

- Domestic vs International Analysis
- Top Airport Routes
- Destination Country Performance
- Geographic Map Analysis

---

### 4. Customer, Airline & Booking Performance

- Travel Purpose
- Seat Class Analysis
- Airline Performance
- Booking Channel Performance

---

## 📈 Key Insights

### ✈️ Domestic vs International Travel

- Domestic flights accounted for **91.05% of bookings** but generated **57.37% of total revenue**.
- International flights represented only **8.95% of bookings** yet contributed **42.63% of total revenue**, demonstrating significantly higher revenue per booking.

### 📅 Time Intelligence

- Revenue peaked during **March, June, and October**.
- Tuesday generated the highest revenue.
- Sunday generated the lowest revenue.
- Revenue declined slightly in 2019, although rounded figures appear similar to 2018.
- Since the dataset only contains January 2020 data, further analysis is required to determine whether this decline continued.

### 💼 Traveler Segments

- Business travel generated the highest revenue.
- Personal Leisure generated the lowest revenue, presenting an opportunity for future growth.
- Business Class generated the highest revenue among seat classes, although differences between classes were relatively small.

### 🌍 Routes & Destinations

- Domestic travel remains the company's primary revenue engine.
- International airport routes dominated the highest-performing corridors despite lower booking volume.
- Europe, Asia, and Australia were the strongest international destination regions, while Africa and South America present opportunities for future expansion.

### ✈️ Airline Performance

- Southwest, American, Delta, and United dominated both revenue and booking volume.
- Airlines with the highest Average Ticket Value differed from those generating the highest overall revenue, demonstrating different pricing and volume strategies.

### 🌐 Booking Channels

- Booking channels performed consistently across revenue and customer acquisition.
- Expedia marginally outperformed other agencies in revenue.
- Direct bookings through airline websites were also significant, highlighting the importance of maintaining both direct and third-party sales channels.

---

## 💡 Business Recommendations

Based on the analysis, the following recommendations were identified:

- Increase international booking volume while maintaining high booking values.
- Promote leisure travel during weekends and holidays.
- Strengthen loyalty programs for business travelers.
- Improve premium cabin differentiation.
- Expand partnerships in underserved international markets.
- Maintain a diversified booking channel strategy.
- Improve customer data collection by introducing Customer IDs and booking status tracking.

---

## ⚠️ Project Limitations

Several limitations should be considered when interpreting the findings:

- The dataset contained only January data for 2020, limiting year-over-year trend analysis.
- Each traveler appeared only once, preventing customer retention and repeat booking analysis.
- The "Others" travel purpose category reduced segmentation quality.
- Booking outcomes (Completed, Cancelled, or Rebooked) were unavailable.
- Customer demographic information was not included.

---

## 🧠 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Power Query
- Data Modeling
- DAX
- Time Intelligence
- Business Intelligence
- Dashboard Design
- Data Visualization
- Data Storytelling
- Business Recommendation Development

---

## 📸 Dashboard Preview

> **Insert screenshots of the following pages:**

- Executive Summary
- Time Intelligence
- Routes & Destinations
- Customer, Airline & Booking Performance

---

## 🚀 Conclusion

This project demonstrates how Power BI can transform raw travel booking data into actionable business insights.

Through effective data cleaning, modeling, visualization, and storytelling, the dashboard highlights opportunities to improve revenue, optimize airline partnerships, strengthen customer segmentation, and support strategic decision-making.

---

## 👤 Author

**Samuel Muiruri**

If you found this project interesting, feel free to connect with me on LinkedIn or explore my other data analytics projects.
