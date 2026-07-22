# 📊 Retail Sales Analytics Dashboard | Power BI

<p align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analytics-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![SQL](https://img.shields.io/badge/SQL-Database-orange)
![Git](https://img.shields.io/badge/Git-Version%20Control-red)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black)

</p>

---

# 📌 Project Overview

The **Retail Sales Analytics Dashboard** is an interactive Business Intelligence solution built using **Microsoft Power BI** to transform retail sales data into meaningful business insights.

The dashboard enables stakeholders to monitor sales performance, profitability, product trends, customer behavior, and regional performance through intuitive visualizations and interactive reports.

This project demonstrates end-to-end Power BI development including data modeling, Power Query transformations, DAX calculations, dashboard design, and business storytelling.

---

# 🎯 Business Problem

Retail organizations generate large amounts of transactional data every day. Without centralized reporting, business users struggle to answer questions such as:

- Which products generate the highest revenue?
- Which regions are performing well?
- How are sales changing over time?
- Which product categories contribute the most profit?
- What are the key KPIs that leadership should monitor?

The goal of this dashboard is to transform raw sales data into actionable insights that support strategic decision-making.

---

# 💡 Solution

This dashboard provides a centralized reporting solution that enables users to:

- Monitor overall sales performance
- Analyze profitability
- Evaluate regional performance
- Track sales trends over time
- Compare product categories
- Filter reports dynamically using slicers
- Gain deeper insights using custom tooltips

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI Desktop | Dashboard Development |
| DAX | Business Calculations |
| Power Query | Data Transformation |
| Data Modeling | Relationship Management |
| SQL | Data Preparation |
| Git | Version Control |
| GitHub | Project Repository |

---

# 📊 Dashboard Walkthrough

## 🏠 Executive Dashboard

The Executive Dashboard provides a high-level overview of business performance through interactive KPI cards and visualizations.

### KPIs

- 💰 Total Sales
- 📈 Total Profit
- 📦 Quantity Sold
- 🛒 Total Orders

### Visuals Used

- KPI Cards
- Column Chart
- Bar Chart
- Donut Chart
- Pie Chart
- Matrix
- Slicers

### Business Value

Business leaders can quickly monitor company performance without navigating multiple reports.

---

## 🌍 Region Analysis

The Region Analysis page helps stakeholders understand geographical business performance.

### Highlights

- Regional Sales
- Regional Profit
- Sales Distribution
- Map Visualization
- Regional Comparison

### Business Value

Enables managers to identify high-performing and underperforming regions for strategic planning.

---

## 📈 Trend Analysis

The Trend Analysis page focuses on historical business performance.

### Features

- Monthly Sales Trend
- Year-over-Year Growth
- Product Trend Analysis
- Interactive Filtering

### Business Value

Helps management identify seasonal trends and long-term business growth patterns.

---

## 🎯 Custom Tooltip

A dedicated tooltip page enhances user experience by displaying additional contextual information when hovering over report visuals.

This improves report usability without overcrowding the dashboard.

---

# 📷 Dashboard Preview

## Executive Dashboard
<img width="1906" height="938" alt="Executive_Dashboard" src="https://github.com/user-attachments/assets/e5073854-a836-4c1f-8d01-a1661c200f26" />

---

## Region Analysis

<img width="1888" height="947" alt="Region_Analysis" src="https://github.com/user-attachments/assets/91f935e6-494c-4583-9602-72b731373357" />

---

## Trend Analysis

<img width="1862" height="951" alt="Trend_Analysis" src="https://github.com/user-attachments/assets/9588fe19-ff0d-41d1-a2c1-97453ba49353" />

---

## Data Model

<img width="1515" height="903" alt="Model_View" src="https://github.com/user-attachments/assets/86e123ac-2f26-450a-a6c9-8e7baec74d52" />

---

## Custom Tooltip

<img width="1917" height="902" alt="Custom Tooltip" src="https://github.com/user-attachments/assets/0c3a94d9-60c7-4b2b-ba7b-40ec5a23893a" />

---

# 🎥 Dashboard Demo

A short walkthrough demonstrating dashboard navigation, slicers, tooltips, and interactive reporting.

📹 **Demo Video:** Demo/Demo.mp4

---

# 🗄 Data Model

The report follows dimensional modeling principles using a centralized fact table and supporting dimension tables.

### Fact Table

- Sales

### Dimension Tables

- Customers
- Products
- Region
- Ship Mode
- Segment
- Returns
- Address
- Date Table

### Benefits

- Improved query performance
- Simplified report development
- Scalable architecture
- Better DAX performance

---

# 📅 Date Dimension

A dedicated Date Table supports advanced time intelligence calculations.

Includes:

- Year
- Quarter
- Month
- Month Name
- Week Number
- Fiscal Year
- Fiscal Quarter

This enables accurate trend analysis and future time-based calculations.

---

# ⚙ Power Query (ETL)

Power Query was used to prepare the dataset before modeling.

### Transformations

- Data Cleaning
- Data Type Conversion
- Removing Unnecessary Columns
- Creating Date Dimension
- Data Validation
- Loading into Power BI Model

---

# 🧮 DAX Measures

The report utilizes DAX measures to calculate business KPIs.

Examples include:

- Total Sales
- Total Profit
- Quantity Sold
- Total Orders
- Parent Sales %
- Profit Margin
- Time Intelligence Measures

---

# 🚀 Key Features

✅ Interactive Dashboard

✅ Cross Filtering

✅ Cross Highlighting

✅ Dynamic Slicers

✅ KPI Cards

✅ Matrix Visual

✅ Custom Tooltips

✅ Time Intelligence

✅ Responsive Visual Design

---

# 📈 Business Insights

Some key insights generated through the dashboard include:

- Sales exceeded **$2.3M** with an overall profit of approximately **$286K**.
- Technology is the highest revenue-generating product category.
- Sales show a consistent upward trend across multiple years.
- Regional analysis identifies areas with strong and weak business performance.
- Product-level analysis helps identify high-performing product segments.
- Interactive filtering enables users to analyze business performance across different dimensions.

---

# 💼 Skills Demonstrated

### Business Intelligence

- Dashboard Development
- KPI Reporting
- Executive Reporting
- Business Storytelling

### Power BI

- Power BI Desktop
- DAX
- Power Query
- Data Modeling
- Relationships
- Time Intelligence

### Data Analytics

- Trend Analysis
- Regional Analysis
- Sales Analytics
- Interactive Reporting

### Version Control

- Git
- GitHub

---

# 📂 Repository Structure

```
Retail-Sales-Analytics
│
├── README.md
├── Demo
│   └── Demo.mp4
│
├── Screenshots
│   ├── Executive Dashboard.png
│   ├── Region Analysis.png
│   ├── Trend Analysis.png
│   ├── Data Model.png
│   ├── Date Table.png
│   └── Custom Tooltip.png
│
├── Retail_Project.pbip
├── Retail_Project.Report
└── Retail_Project.SemanticModel
```

---

# 🔮 Future Enhancements

- Row-Level Security (RLS)
- Incremental Refresh
- Microsoft Fabric Integration
- Deployment Pipelines
- Forecasting
- AI Visuals
- Mobile Layout Optimization

---

# 👨‍💻 About Me

I am a **Power BI Developer** with experience in Business Intelligence, SQL, DAX, Power Query, and interactive dashboard development. I enjoy transforming raw data into actionable insights that enable organizations to make informed business decisions.

---

# 📬 Connect With Me

**LinkedIn:** https://www.linkedin.com/in/sourabh-sharma2396

**GitHub:** https://github.com/er-sourabh

---

## ⭐ If you found this project helpful, consider giving it a Star!

If you have feedback or suggestions, feel free to open an Issue or connect with me on LinkedIn.
