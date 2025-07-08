# Tableau Sales Dashboard – Profit, Sales, and Order Quantity Analysis

📊 This project presents an interactive Tableau dashboard that analyzes sales, profit, and order quantity using custom calculated fields. It includes segmented profit insights, regional sales contribution, monthly order volume, and correlation between sales and profit.


---

## 📁 Dataset Overview

The dashboard is built using a modified **Superstore-style dataset**, composed of the following tables:

### 📦 Orders Table
- `Order ID`, `Order Date`, `Region`, `Customer Segment`, `Sales`, `Profit`, `Quantity`, `Unit Price`, `Customer Name`, etc.

### 🔁 Returns Table
- `Order ID`, `Status`

### 👤 Users Table
- `Region`, `Manager`

---

## 🔧 Calculated Fields Used

| Field Name       | Description |
|------------------|-------------|
| `Unit Price Group` | Custom binning or grouping of unit prices into categories (e.g., A, B, C) |
| `Year(Order Date)` | Extracted year from order date for trend analysis |
| `Sales Contribution %` | Region-wise sales as a percentage of total sales |
| `Top Regions` (parameter logic) | Dynamic focus on regions with highest sales |
| `Monthly Order Quantity` | Extracted month from `Order Date` to summarize quantity trends |

---

## 📊 Visualizations

| Visualization | Description |
|---------------|-------------|
| **Bar Chart** | Profit by Region and Customer Segment using stacked bars |
| **Pie Chart** | Region-wise % sales contribution with actual sales values |
| **Scatter Plot** | Profit vs. Sales to assess distribution and correlation |
| **Line Chart** | Monthly trend of order quantity with data labels |
| **Dashboard Filter** | `Unit Price Group` filter enables comparative analysis across pricing bands |

---

## 🧠 Insights from Dashboard

- **Central region** contributes the highest to overall sales (~31.5%)
- **Corporate and Home Office segments** generate more profit in most regions
- **No direct correlation** between very high sales and high profit – some high sales have low or negative profit
- **Order quantity peaks** in May, with steady performance across other months

---

## 📷 Dashboard Screenshot


![Dashboard 1](https://github.com/user-attachments/assets/b468de3b-33c1-49aa-aab4-7a8f402417a1)


---

## 🔗 Tableau Public Link

👉 [View on Tableau Public](https://public.tableau.com/views/TableauDashboard1_17511961325470/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


---

## 🛠️ Tools Used

- Tableau Desktop / Tableau Public
- Custom calculated fields
- Parameters and filters
- Dashboard layout design
- Pie, line, bar, and scatter visualizations

---

## 🔐 License

![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)
[![View License](https://img.shields.io/badge/View%20License-Here-blue)](https://creativecommons.org/licenses/by/4.0/)

This project is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to use and adapt it with attribution.

---



