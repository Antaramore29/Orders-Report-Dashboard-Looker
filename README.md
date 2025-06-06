# Orders_Report_Dashboard_Looker
This project showcases a detailed, interactive dashboard of a hypothetical company’s sales order data using Google Looker Studio. It features dynamic filters, KPI summary cards with icons, and engaging charts (donut, bar, line). Designed for clarity, usability, and visual appeal to make data exploration intuitive and insightful.

# 📊 Orders Dashboard – Built with Google Looker Studio

## 🎯 Project Objective

The objective of this project is to design and build an **interactive business intelligence dashboard** using Google Looker Studio. The dashboard provides a dynamic overview of key metrics related to customer orders, allowing users to analyze performance across regions, categories, and customer segments. It supports decision-making through visually engaging charts, KPIs, and filters that enable real-time data exploration.

---

## 📁 Datasets

The dashboard is powered by a retail orders dataset consisting of:

- **Rows**: 9,994
- **Columns**: 21
- **Key Attributes**:
  - Customer Name
  - Segment
  - State
  - Region
  - Order ID
  - Order Date
  - Ship Mode
  - Sales
  - Profit
  - Quantity
  - Category
  - Sub-Category
  - Discount

Files included:
- `Data Source.xlsx` – primary dataset used in the dashboard
- `nba.csv` – optional exploratory dataset for future enhancement

---

## Key Business Questions (KPIs)

The dashboard answers the following questions through scorecards and charts:

- What are the **total sales**, **profit**, and **order count**?
- How many **unique customers** placed orders?
- What is the **distribution of orders** across:
  - 📍 Regions
  - 🛍️ Categories
  - 🧑 Segments
  - 🚚 Shipping Modes
- How does **order quantity** vary **over time**?
- Which **cities** contribute most to order volumes?
- What are the detailed **order-level metrics** across different fields?

---

## 🧩 Dashboard Interactions

Users can interact with the dashboard using dropdown and fixed filters for:

- **Region**
- **Segment**
- **Category**
- **Ship Mode**

These filters dynamically update charts and KPIs in real time, enabling users to drill down into specific segments of interest.

<a href="https://github.com/Antaramore29/Orders_Report_Dashboard_Looker/blob/main/Dasboard-image.png">View Dashboard</a>

---

## ⚙️ Process Overview

1. **Data Preparation**:
   - Cleaned and structured order data in Google Sheets
   - Connected Google Sheets as a data source in Looker Studio

2. **Layout Design**:
   - Created a custom background using shapes and headers
   - Applied a consistent theme and styling across all visuals

3. **Filter Setup**:
   - Added dropdowns and fixed lists for interactive filtering
   - Styled filters for visual clarity and alignment

4. **KPI Cards**:
   - Designed scorecards for Sales, Profit, Orders, Customers, States, and Segments
   - Added icons to improve visual engagement

5. **Chart Creation**:
   - Built donut charts for Region, Category, and Segment distribution
   - Used bar charts for city-level order counts
   - Plotted a line chart to show order quantity trends over time

6. **Tables**:
   - Created interactive tables with adjustable columns for detailed analysis

---

## 🖼️ Dashboard Preview

<img width="1470" alt="Dasboard-image" src="https://github.com/user-attachments/assets/01ee0735-9bfa-4b13-98b7-889c06cffc31" />

---

## 🎓 Learning Objectives / Conclusion

Through this project, the following objectives were achieved:

- Developed an end-to-end dashboard solution using Google Looker Studio
- Learned how to structure and filter real-world business data
- Gained hands-on experience in visual storytelling through KPI cards and charts
- Practiced UI/UX design principles for better readability and user experience
- Delivered an interactive tool for analyzing orders data by multiple dimensions

This project serves as a robust foundation for building scalable, client-ready dashboards for retail or sales analytics.


