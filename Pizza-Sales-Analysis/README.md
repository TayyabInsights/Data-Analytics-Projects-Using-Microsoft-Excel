# 🍕 Pizza Sales Analysis: Ultimate Guide to Building an Interactive Dashboard Using MS Excel for a Data Analytics Project


## 📑 Table of Contents
1. [📋 Project Overview](#project-overview)
2. [❓ Problem Statement](#problem-statement)
3. [🛠 Methodology](#methodology)
4. [💻 Technologies Used](#technologies-used)
5. [📂 Folder Structure](#folder-structure)
6. [📝 How to Use the Project](#how-to-use-the-project)
7. [📊 Data Collection](#data-collection)
8. [🧹 Data Preparation](#data-preparation)
9. [📈 Dashboard Overview](#dashboard-overview)
10. [🔑 Key Findings](#key-findings)
11. [⚠️ Limitations](#limitations)
12. [🚀 Future Improvements](#future-improvements)

---

## Project Overview 📋
This project analyzes pizza sales data to uncover insights into customer preferences, top-selling items, and seasonal trends. Using Microsoft Excel, the project demonstrates skills in data cleaning, analysis, and dashboard creation.

The goal is to provide actionable insights for improving inventory management and marketing strategies.

---

## Problem Statement ❓
The pizza chain lacks a clear understanding of its sales trends and customer preferences, leading to inefficiencies in inventory management and missed marketing opportunities. This project addresses the following:
- 🍕 Identifying top-performing pizza types.
- 📅 Analyzing seasonal and daily sales patterns.
- 📊 Creating a dashboard for better decision-making.

---

## Methodology 🛠
1. 📥 **Data Import and Cleaning:** Ensured data quality for analysis.
2. 📊 **Data Analysis:** Used Excel formulas and PivotTables for insights.
3. 📈 **Dashboard Creation:** Built an interactive dashboard to visualize key metrics.

---

## Technologies Used 💻
- **Microsoft Excel 365:**
  - 🧮 Formulas (`SUMIFS`, `AVERAGEIFS`, `COUNTIFS`)
  - 📊 PivotTables
  - 🎨 Conditional Formatting
  - 📈 Charts (Bar, Line, and Pie Charts)
  - 🎛 Slicers for interactivity

---

## Folder Structure 📂
Here’s how the project is organized:



---

## How to Use the Project 📝
1. 📂 Open the dataset file located in `data/pizza_sales.csv` to explore the raw data.
2. 📊 Navigate to `dashboard/Pizza_Sales_Dashboard.xlsx` to interact with the final dashboard.
3. 🖼 Refer to the `images/` folder for screenshots of key steps in the process.

---

## Data Collection 📊
The dataset contains detailed information about pizza orders. Below are the column names and their descriptions:

| **Column Name**         | **Description**                                    |
|--------------------------|--------------------------------------------------|
| `order_details_id`       | Unique identifier for each order detail.         |
| `order_id`               | Identifier for each order.                       |
| `pizza_id`               | Unique identifier for each pizza type.           |
| `quantity`               | Number of pizzas sold per order detail.          |
| `order_date`             | Date when the order was placed.                  |
| `order_time`             | Time when the order was placed.                  |
| `unit_price`             | Price per unit of pizza.                         |
| `total_price`            | Total revenue generated per order detail.        |
| `pizza_size`             | Size of the pizza (e.g., Small, Medium, Large).  |
| `pizza_category`         | Pizza category (e.g., Classic, Veggie, Supreme). |
| `pizza_ingredients`      | Ingredients used in the pizza.                   |
| `pizza_name`             | Name of the pizza (e.g., "The Hawaiian Pizza").  |

---

## Data Preparation 🧹
The following steps were performed to clean the dataset:
1. 🗑 **Remove Duplicates:** Identified and removed duplicate entries using Excel's "Remove Duplicates" feature.
2. 🧮 **Handle Missing Values:** Filled missing revenue values with the average revenue for the respective pizza type.
3. 📅 **Format Data:** Standardized the `order_date` format and cleaned up the `pizza_name` column using Excel functions.

---

## Dashboard Overview 📈
The final dashboard includes:
- 📊 **Bar Chart:** Shows revenue contribution by pizza type.
- 📈 **Line Chart:** Displays monthly sales trends.
- 🎛 **Interactive Slicers:** Filter data by pizza type or date.

Here’s a preview of the dashboard:

![📊 Dashboard Screenshot](images/dashboard_screenshot.png)

---

## Key Findings 🔑
1. 🍕 **Pepperoni Pizza** contributes 35% of total revenue, making it the top-selling item.
2. 📅 Sales peak on **weekends**, especially on Saturdays.
3. 🎄 **December** is the highest-performing month, indicating strong seasonal demand.

---

## Limitations ⚠️
- 📆 Dataset only covers one year, limiting long-term trend analysis.
- 🙍‍♀️ Customer demographic data is unavailable, preventing deeper segmentation.

---

## Future Improvements 🚀
- 👥 Incorporate demographic data for enhanced insights.
- 📆 Use a larger dataset covering multiple years for better trend analysis.
- 🖥
