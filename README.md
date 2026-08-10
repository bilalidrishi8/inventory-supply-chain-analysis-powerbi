# 📦 Inventory & Supply Chain Performance Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow)
![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-green)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Supply%20Chain-orange)

## 📊 Project Overview

The **Inventory & Supply Chain Performance Dashboard** is an interactive Power BI project designed to analyze inventory levels, warehouse capacity, supplier performance, transportation costs, order accuracy, lead times, and backorders.

The dashboard provides a centralized view of supply chain operations and helps identify **inventory risks, supplier performance issues, warehouse utilization, and operational inefficiencies**.

---

## 🎯 Project Objectives

* Monitor overall inventory performance.
* Analyze inventory levels across warehouses and categories.
* Measure warehouse capacity utilization.
* Track supplier performance.
* Analyze transportation and logistics costs.
* Monitor order accuracy.
* Identify backorder trends.
* Analyze supplier lead times.
* Compare operational performance across regions.
* Provide actionable business insights through interactive dashboards.

---

## 🛠️ Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* **Microsoft Excel / CSV**
* **Data Modeling**
* **Data Visualization**
* **Business Intelligence**

---

## 📁 Dataset

The project uses an inventory and supply chain dataset containing information related to:

* Products
* Categories
* Suppliers
* Warehouses
* Regions
* Inventory levels
* Units sold
* Orders
* Lead time
* Backorders
* Transportation costs
* Cost of Goods Sold (COGS)
* Warehouse capacity
* Order accuracy

**Dataset:** `Inventory_SupplyChain_Dataset.csv`

---

## 📌 Key KPIs

The dashboard tracks the following important KPIs:

| KPI                      | Description                                 |
| ------------------------ | ------------------------------------------- |
| 📦 Total Units Sold      | Total number of units sold                  |
| 💰 Total COGS            | Total cost of goods sold                    |
| 🚚 Transportation Cost   | Total logistics and transportation cost     |
| ⏱️ Average Lead Time     | Average supplier delivery time              |
| 🎯 Order Accuracy        | Percentage of accurate orders               |
| ⚠️ Backorder Rate        | Percentage of orders affected by backorders |
| 🏭 Warehouse Capacity    | Total available warehouse capacity          |
| 📊 Inventory Utilization | Inventory compared with warehouse capacity  |

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview

Provides a high-level summary of supply chain performance.

**Key visuals:**

* KPI Cards
* Monthly Units Sold
* COGS by Region
* Units Sold by Category
* Backorders by Region
* Order Status Distribution
* Inventory Overview

---

### 2️⃣ Inventory Analysis

Focuses on inventory health and warehouse utilization.

**Key visuals:**

* Inventory by Category
* Inventory by Warehouse
* Inventory Utilization
* Warehouse Capacity
* Inventory Trends
* Regional Inventory Analysis

---

### 3️⃣ Supplier & Logistics Analysis

Analyzes supplier and transportation performance.

**Key visuals:**

* Transportation Cost by Supplier
* Average Lead Time by Supplier
* Order Accuracy by Supplier
* Backorders by Supplier
* Supplier Performance Matrix
* Lead Time vs Transportation Cost

---

### 4️⃣ Warehouse & Operations

Analyzes warehouse efficiency and operational performance.

**Key visuals:**

* Units Sold by Warehouse
* Inventory by Warehouse
* Warehouse Capacity
* Capacity Utilization
* Backorders by Warehouse
* Order Status by Warehouse
* Transportation Cost by Warehouse

---

## 🧮 Important DAX Measures

### Total Units Sold

```DAX
Total Units Sold =
SUM('Inventory'[Units Sold])
```

### Total COGS

```DAX
Total COGS =
SUM('Inventory'[Cost of Goods Sold (COGS)])
```

### Total Transportation Cost

```DAX
Total Transportation Cost =
SUM('Inventory'[Transportation Cost])
```

### Average Lead Time

```DAX
Average Lead Time =
AVERAGE('Inventory'[Lead Time (Days)])
```

### Inventory Utilization

```DAX
Inventory Utilization % =
DIVIDE(
    SUM('Inventory'[Inventory Level]),
    SUM('Inventory'[Warehouse Capacity]),
    0
)
```

---

## 🔄 Data Preparation

The dataset was prepared using **Power Query**.

Main transformation steps included:

1. Importing the CSV dataset.
2. Checking column names and data types.
3. Handling missing values.
4. Removing duplicate records.
5. Converting date columns to Date format.
6. Converting numerical columns to appropriate data types.
7. Transforming Boolean fields where required.
8. Creating calculated columns where necessary.
9. Creating relationships between tables.
10. Preparing the final data model for reporting.

---

## 📈 Business Insights

The dashboard can help management answer questions such as:

* Which warehouses have the highest inventory?
* Which warehouses are approaching capacity?
* Which suppliers have the longest lead times?
* Which suppliers have poor order accuracy?
* Which regions generate the highest COGS?
* Where are backorders concentrated?
* Which product categories have the highest demand?
* How efficiently is warehouse capacity being utilized?
* Which suppliers have high transportation costs?
* Where are the major supply-chain bottlenecks?

---

## 🎨 Dashboard Design

The dashboard uses a professional business intelligence theme with:

* Dark navy background
* Cyan primary accent
* Orange warning indicators
* Red critical indicators
* KPI cards
* Interactive slicers
* Conditional formatting
* Drill-down analysis
* Interactive charts

---

## 📂 Repository Structure

```text
inventory-supply-chain-powerbi-dashboard/
│
├── Dataset/
│   └── Inventory_SupplyChain_Dataset.csv
│
├── PowerBI/
│   └── Inventory_SupplyChain_Dashboard.pbix
│
├── Screenshots/
│   ├── executive-overview.png
│   ├── inventory-analysis.png
│   ├── supplier-logistics.png
│   └── warehouse-operations.png
│
├── README.md
└── Insights.md
```

---

## 🚀 Key Skills Demonstrated

```text
Power BI
Power Query
DAX
Data Cleaning
Data Modeling
KPI Development
Business Analysis
Supply Chain Analytics
Inventory Analysis
Warehouse Analytics
Supplier Analysis
Data Visualization
Dashboard Design
```

---

## 💼 Business Value

This dashboard transforms raw supply-chain data into an interactive analytical solution that enables stakeholders to monitor operational performance, identify potential inventory and supplier risks, understand logistics costs, and make data-driven decisions.

---

## 👨‍💻 Author

**Data Analytics Portfolio Project**

**Skills:** Python | SQL | Power BI | DAX | Excel | Data Analytics

---

⭐ If you find this project useful, feel free to explore the repository and connect with me.
