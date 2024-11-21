# Pizza Sales Analysis and Dashboard Creation Using Microsoft Excel

## Table of Contents
1. [Project Overview](#project-overview)
2. [Problem Statement](#problem-statement)
3. [Methodology](#methodology)
4. [Technologies Used](#technologies-used)
5. [Folder Structure](#folder-structure)
6. [How to Use the Project](#how-to-use-the-project)
7. [Data Collection](#data-collection)
8. [Data Preparation](#data-preparation)
9. [Dashboard Overview](#dashboard-overview)
10. [Key Findings](#key-findings)
11. [Limitations](#limitations)
12. [Future Improvements](#future-improvements)

---

## Project Overview
This project analyzes pizza sales data to uncover insights into customer preferences, top-selling items, and seasonal trends. Using Microsoft Excel, the project demonstrates skills in data cleaning, analysis, and dashboard creation.

The goal is to provide actionable insights for improving inventory management and marketing strategies.

---

## Problem Statement
The pizza chain lacks a clear understanding of its sales trends and customer preferences, leading to inefficiencies in inventory management and missed marketing opportunities. This project addresses the following:
- Identifying top-performing pizza types.
- Analyzing seasonal and daily sales patterns.
- Creating a dashboard for better decision-making.

---

## Methodology
1. Data import and cleaning to ensure quality.
2. Data analysis using Excel formulas and PivotTables.
3. Dashboard creation to visualize key insights interactively.

---

## Technologies Used
- **Microsoft Excel 365:**
  - Formulas (`SUMIFS`, `AVERAGEIFS`, `COUNTIFS`)
  - PivotTables
  - Conditional Formatting
  - Charts (Bar, Line, and Pie Charts)
  - Slicers for interactivity

---

## Folder Structure
Here’s how the project is organized:


---

## How to Use the Project
1. Open the dataset file located in `data/pizza_sales.csv` to explore the raw data.
2. Navigate to `dashboard/Pizza_Sales_Dashboard.xlsx` to interact with the final dashboard.
3. Refer to the `images/` folder for screenshots of key steps in the process.

---

## Data Collection
The dataset contains one year of pizza sales data with the following columns:

| **Column Name**   | **Description**                  |
|-------------------|----------------------------------|
| `Order Date`      | Date when the order was placed  |
| `Pizza Type`      | Name of the pizza sold          |
| `Quantity`        | Number of pizzas sold           |
| `Revenue`         | Total sales revenue in USD      |

---

## Data Preparation
The following steps were performed to clean the dataset:
1. **Remove Duplicates:** Identified and removed duplicate entries using Excel's "Remove Duplicates" feature.
2. **Handle Missing Values:** Filled missing revenue values with the average revenue for the respective pizza type.
3. **Format Data:** Standardized the `Order Date` format and cleaned up the `Pizza Type` column using Excel functions.

---

## Dashboard Overview
The final dashboard includes:
- **Bar Chart:** Shows revenue contribution by pizza type.
- **Line Chart:** Displays monthly sales trends.
- **Interactive Slicers:** Filter data by pizza type or date.

Here’s a preview of the dashboard:

![Dashboard Screenshot](images/dashboard_screenshot.png)

---

## Key Findings
1. **Pepperoni Pizza** contributes 35% of total revenue, making it the top-selling item.
2. Sales peak on **weekends**, especially on Saturdays.
3. **December** is the highest-performing month, indicating strong seasonal demand.

---

## Limitations
- Dataset only covers one year, limiting long-term trend analysis.
- Customer demographic data is unavailable, preventing deeper segmentation.

---

## Future Improvements
- Incorporate demographic data for enhanced insights.
- Use a larger dataset covering multiple years for better trend analysis.
- Create an advanced dashboard using Power BI for better visualization.


