# 🍫 Chocolate Sales Analysis — Power BI & MySQL

An interactive business intelligence project that analyzes chocolate sales data using **Microsoft Power BI** and **MySQL**. The project focuses on sales performance, product-level metrics, shipment analysis, and geographic reporting through data modeling, KPI measures, and interactive visualizations.

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/SQL-Data%20Management-CC2927?style=for-the-badge&logo=databricks&logoColor=white" alt="SQL"/>
</p>

## 📌 Project Overview

This project uses the Awesome Chocolates dataset to build a Power BI report connected to a MySQL database. It brings together sales transactions, product information, salesperson details, and geographic data to support business performance analysis.

The dashboard includes sales-related measures and shipment indicators to help users explore business performance and compare results across available dimensions.

## 🎯 Project Objectives

- Analyze overall chocolate sales performance.
- Track total sales and boxes sold.
- Examine customer and product-related metrics.
- Analyze shipment counts and low-box shipment indicators.
- Explore sales data by date and geographic location.
- Build an interactive dashboard for business reporting and decision-making.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard development and data visualization |
| MySQL | Relational database and data storage |
| SQL | Dataset import and database management |
| Power Query | Data loading and transformation within Power BI |
| DAX | Measures and KPI calculations in Power BI |

## 📊 Dashboard Metrics

The report includes the following fields and measures visible in the Power BI data model:

| Metric | Purpose |
|---|---|
| **Total Sales** | Measures overall sales value |
| **Total Boxes** | Tracks the number of boxes sold |
| **Shipment Counts** | Tracks shipment-related activity |
| **Customers** | Supports customer-related sales analysis |
| **LBS %** | Provides a percentage-based shipment metric |
| **Low Box Shipment** | Supports analysis of shipments with low box quantities |
| **SaleDate** | Enables date-based analysis |
| **Amount** | Contains the sales amount field |
| **Boxes** | Contains the box quantity field |

The report can be explored using the available date, product, salesperson, and geographic dimensions. Actual business findings should be added after reviewing the completed dashboard.

## 🗄️ Database Structure

The project uses four related tables from the Awesome Chocolates dataset:

| Table | Description |
|---|---|
| `sales` | Sales transaction records and related measures |
| `products` | Product-related information |
| `people` | Salesperson or employee-related information |
| `geo` | Geographic information |

These tables provide the data foundation for the Power BI report.

## 🔄 Project Workflow

1. **Data Import:** Load the supplied SQL script into MySQL.
2. **Database Setup:** Create and populate the `chocolate_analysis_db` database.
3. **Data Connection:** Connect Power BI Desktop to the MySQL database.
4. **Data Modeling:** Load the relevant tables and establish the required relationships.
5. **Measure Development:** Use Power BI measures to calculate sales and shipment KPIs.
6. **Visualization:** Build a report to explore business metrics across available dimensions.
7. **Analysis:** Use the dashboard to investigate sales performance and shipment patterns.

## 📁 Repository Structure

```text
Chocolate_Sales_Analysis_Report/
│
├── Chocolate_Sales_Analysis_Report.pbix
├── Chocolate_Sales_Analysis_Report.pdf
├── chocolate_analysis_import.sql.sql
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Microsoft Power BI Desktop
- MySQL Server
- MySQL Workbench (recommended for importing the SQL script)
- A compatible MySQL Connector/NET installation for Power BI's native MySQL connector

### Step 1: Clone the repository

```bash
git clone https://github.com/saurav13singh2003-crypto/Chocolate_Sales_Analysis_Report.git
cd Chocolate_Sales_Analysis_Report
```

### Step 2: Import the SQL dataset

1. Open MySQL Workbench and connect to your MySQL Server.
2. Open `chocolate_analysis_import.sql.sql`.
3. Review the SQL script and execute it to create and populate the project database.
4. Confirm that the `sales`, `products`, `people`, and `geo` tables exist.

**Important:** The script should create or use `chocolate_analysis_db`. Check the database and table names in the script before executing it.

### Step 3: Connect Power BI to MySQL

1. Open Power BI Desktop.
2. Select **Get Data → MySQL database**.
3. Enter your MySQL server address and port.
4. Select `chocolate_analysis_db` as the database.
5. Authenticate using your MySQL credentials.
6. Select the required tables and load the data.

For a local installation, use the server and port configured for your MySQL instance.

### Step 4: Open the report

Open `Chocolate_Sales_Analysis_Report.pbix` in Power BI Desktop.

If Power BI prompts you to configure the data source, update the connection to your own MySQL instance and refresh the data.

## 📄 Project Files

- **[Power BI Report](Chocolate_Sales_Analysis_Report.pbix)** — Interactive report file.
- **[PDF Report](Chocolate_Sales_Analysis_Report.pdf)** — PDF version of the report for convenient viewing.
- **[SQL Import Script](chocolate_analysis_import.sql.sql)** — SQL script for setting up the dataset.

## 💡 Skills Demonstrated

- Power BI dashboard development
- MySQL database connectivity
- SQL data import and management
- Data modeling and relationship management
- DAX measures and KPI analysis
- Business intelligence and data visualization
- Translating business data into actionable insights

## 🔮 Future Improvements

- Add month-over-month and year-over-year sales comparisons.
- Analyze top-performing products and salespeople.
- Add geographic sales comparisons.
- Improve dashboard interactivity with slicers and drill-through pages.
- Document verified findings and recommendations from the completed report.

## 👤 Author

**Saurav Singh**

Electronics and Instrumentation Engineering Student | Aspiring Data Analyst

- GitHub: [@saurav13singh2003-crypto](https://github.com/saurav13singh2003-crypto)

---

If you find this project useful, consider giving the repository a ⭐.
