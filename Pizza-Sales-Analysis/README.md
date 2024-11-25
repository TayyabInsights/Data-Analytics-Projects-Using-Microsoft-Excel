# 🍕 Pizza Sales Analysis

## How to Create an Excel Dashboard for Your Data Analytics Project
---
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
12. [🚀 Conclusion and Recommendations](#conclusion-and-recommendations)

---

## 1.📋 Project Overview <a id="project-overview"></a>

This project focuses on developing an interactive Excel dashboard to analyze pizza sales data effectively. By leveraging data visualization techniques, the dashboard aims to reveal critical trends, track key performance indicators (KPIs), and provide actionable insights into sales performance, customer preferences, and operational efficiency.

Through a comprehensive analysis of the dataset, this project will highlight top-selling pizza varieties, seasonal sales patterns, and customer purchasing behaviors. Utilizing Microsoft Excel's powerful data cleaning, analytical, and visualization tools, the project showcases essential skills in transforming raw data into meaningful visual representations that can guide strategic business decisions.

The goal is to provide actionable insights for improving inventory management and marketing strategies.

---

## 2.❓ Problem Statement <a id="problem-statement"></a>

**Operational Challenges**: Difficulty optimizing performance and capitalizing on market opportunities. ⚠️

**Key Areas**:
- **Product Performance** 📊:
  - Identify top-selling pizzas and revenue contributions.
  - Issues with menu optimization and inventory (over/understocking).
  
- **Sales Trends** 📈:
  - Analyze seasonal and daily patterns.
  - Insufficient insights lead to ineffective marketing and staffing.

- **Efficiency Dashboard** 🖥️:
  - Need for a centralized decision-making tool.
  - Current lack results in reactive strategies and inconsistent service.

**Root Causes** 🔍:
- Poor understanding of sales trends and customer preferences.
- Leads to missed marketing opportunities and suboptimal inventory.

**Project Objectives** 🎯:
- Provide actionable insights.
- Transform data into business intelligence.
- Enable informed decisions.

**Expected Outcomes** 🌟:
- Agile and responsive operations.
- Customer-centric approach.
- Competitive advantage in the food sector.

**Ultimate Goal**: Leverage data for business success! 🚀📊

---

## 3.🛠 Methodology <a id="methodology"></a>

8.1 [📥 Data Import and Extraction](#data-import-and-extraction)
8.2 [📋 Project Requirements and Data Familiarization](#project-requirements-and-data-familiarization)
8.3 [🧹 Data Cleaning and Formatting](#data-cleaning-and-formatting)
8.4 [🔄 Data Transformation](#data-transformation)
8.5 [📈 Key Performance Indicator (KPI) Definition](#key-performance-indicator-kpi-definition)
8.6 [🎨 Data Visualization and Analysis](#data-visualization-and-analysis)
8.7 [🖥️ Dashboard Development](#dashboard-development)

---

## 4.💻 Technologies Used <a id="technologies-used"></a>

### **Microsoft Excel 365**
Microsoft Excel serves as the primary tool for this project, showcasing its capabilities in data analysis, visualization, and dashboard creation. Key features and techniques include:

- **Advanced Formulas** 🧮:
  - `SUMIFS`, `AVERAGEIFS`, and `COUNTIFS` for conditional aggregations.
  - `TEXT` for formatting dates and extracting specific time components.
  - `ROUND`, `UNIQUE`, and `COUNTA` for calculating metrics like average order value and total orders.
  
- **PivotTables** 📊:
  - Dynamic summarization of large datasets for trends and pattern analysis.
  - Grouping features to organize data by time (e.g., hours, days, months).

- **Charts** 📈:
  - Bar Charts to visualize sales trends by hour, day, and size.
  - Line Charts for tracking monthly sales trends and seasonal patterns.
  - Doughnut Charts to showcase top and bottom-selling pizzas.

- **Conditional Formatting** 🎨:
  - Highlighting key insights such as peak sales periods and missing values.
  - Using color scales for quick identification of high and low-performing metrics.

- **Slicers** 🎛:
  - Interactive filtering of data by pizza size, category, and time periods.
  - Enhancing user interactivity in the dashboard, enabling customized views.

- **Dashboard Design** 🖥️:
  - A polished, user-friendly interface with a focus on professional branding.
  - Integration of KPIs, charts, and slicers for a cohesive analytical tool.
  - Dynamic linking of all dashboard elements to underlying data for real-time updates.

**Why Microsoft Excel?**
This project demonstrates Excel’s versatility in handling real-world business problems, transforming raw data into actionable insights. The interactive dashboard highlights Excel's strength in bridging data analytics and decision-making.

---

## 5.📂 Folder Structure <a id="folder-structure"></a>

The project is organized into the following structure for ease of navigation and clarity:

- **📄 About-Me/**:  
  Contains a README with information about the author’s expertise and professional background.

- **📊 Dashboard/**:  
  Includes the interactive Excel dashboard built during the project, which contains KPIs, charts, and slicers.

- **📁 Dataset/**:  
  Holds the raw dataset used for data analysis.

- **🖼️ Images/**:  
  Stores visuals, such as screenshots of the dashboard, to enhance project understanding.

- **📜 LICENSE**:  
  Specifies the licensing details for the project (e.g., MIT License).

- **📝 README.md**:  
  The main documentation file detailing the project methodology, technologies, findings, and usage instructions.

---

## 6.📝 How to Use the Project <a id="how-to-use-the-project"></a>

Follow these steps to explore and interact with the project:

1. **📂 Access the Dataset**:  
   - Locate the dataset in the `Dataset/` folder.  
   - Open the `Pizza_Sales_Dataset.xlsx` file to review the raw data, including order details, pizza sizes, categories, and sales figures.

2. **📊 Interact with the Dashboard**:  
   - Navigate to the `Dashboard/` folder.  
   - Open the `Pizza_Sales_Dashboard.xlsx` file to explore the interactive dashboard.  
   - Use slicers and filters to customize your analysis by pizza size, category, and time periods.  

3. **🖼 Refer to Visual Guides**:  
   - Visit the `Images/` folder for screenshots of key charts, insights, and the final dashboard layout. These visuals provide a quick reference to the project’s outcomes and design elements.

4. **🔗 Access the GitHub Repository**:  
   - Explore the complete project repository on GitHub for detailed documentation, project files, and additional resources.  

5. **📖 Read the Documentation**:  
   - Refer to the `README.md` file in the root folder for an in-depth explanation of the project methodology, technologies used, and key findings.

### Tips for Best Experience:
- Ensure you have **Microsoft Excel 365 or a compatible version** installed to interact fully with the dashboard and its features.
- Check out the **slicers** and **interactive charts** for a dynamic analysis experience tailored to your needs.

---

## 7.📊 Data Collection <a id="data-collection"></a>

The dataset provides a comprehensive overview of pizza sales, capturing essential details necessary for effective analysis. Below are the key columns and their descriptions:

| **Column Name**         | **Description**                                                                 |
|--------------------------|-------------------------------------------------------------------------------|
| `order_details_id`       | Unique identifier for each order detail, ensuring no duplicate entries.       |
| `order_id`               | Identifier for each transaction, linking all items within a single order.     |
| `pizza_id`               | Unique identifier for each type of pizza sold, facilitating categorization.   |
| `quantity`               | Number of pizzas sold for each order detail, crucial for sales volume analysis. |
| `order_date`             | The date when the order was placed, useful for analyzing daily, weekly, and seasonal trends. |
| `order_time`             | The time when the order was placed, enabling analysis of peak sales hours.    |
| `unit_price`             | Price per unit of pizza, supporting revenue and pricing strategy analysis.    |
| `total_price`            | Total revenue generated per order detail, essential for calculating KPIs like Total Revenue and Average Order Value. |
| `pizza_size`             | Size of the pizza (e.g., Small, Medium, Large), providing insights into customer preferences. |
| `pizza_category`         | Category of the pizza (e.g., Classic, Veggie, Supreme) for performance analysis. |
| `pizza_ingredients`      | List of ingredients for each pizza, offering insights into popular toppings and customization preferences. |
| `pizza_name`             | Name of the pizza (e.g., "The Hawaiian Pizza"), used to identify top- and bottom-selling items. |



### **Dataset Highlights**:
- **Scope**: Covers a wide range of sales data across multiple categories, sizes, and time periods, enabling a detailed analysis of trends and customer preferences.  
- **Time-Based Insights**: Includes fields like `order_date` and `order_time` to allow granular time-series analysis, such as peak sales hours or seasonal demand patterns.  
- **Performance Metrics**: Fields like `quantity` and `total_price` form the foundation for calculating KPIs, helping measure business performance and operational efficiency.  



### **Dataset Source**:
This dataset is sourced from **Kaggle** as part of the **Pizza Restaurant Sales** collection. The data can be accessed and downloaded from the following link:  
[Pizza Restaurant Sales on Kaggle](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)

### **Dataset Licensing**:
- License: **Other (as specified on Kaggle)**  
- Contributor: **Shi Long Zhuang**  
- Context: This dataset is part of the **Maven Analytics Pizza Challenge**, which focuses on using data for actionable business insights.



### **Acknowledgment**:
This project leverages the **Pizza Restaurant Sales** dataset made available on Kaggle by **Shi Long Zhuang**. It originates from the **Maven Analytics Data Playground** and is used exclusively for educational and analytical purposes in this project.

Special thanks to:
- **Shi Long Zhuang** for the data contribution.
- **Maven Analytics** for hosting the Pizza Challenge and inspiring analytics projects.

For detailed license terms and dataset usage guidelines, refer to the following resources:
- [Kaggle Dataset](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)  
- [Maven Analytics - Pizza Challenge](https://www.mavenanalytics.io/blog/maven-pizza-challenge)

---


## 8.🧹 Data Preparation <a id="data-preparation"></a>

### 8.1 📥 Data Import and Extraction <a id="data-import-and-extraction"></a>
- **Download the Dataset**: Sourced the dataset from Kaggle ([Pizza Sales Dataset](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)).
- **Load into Excel**: Imported the dataset into Excel, ensuring all fields were properly mapped and no data was corrupted during import.

---

### 8.2 📋 Project Requirements and Data Familiarization <a id="project-requirements-and-data-familiarization"></a>

Every successful data analytics project begins with a deep understanding of its **purpose** and **data**. Think of this phase as laying the cornerstone of a strong and lasting structure—without a solid foundation, the entire project risks faltering. This step is where you align your analytical approach with stakeholder goals while ensuring the dataset is ready to deliver accurate, actionable insights. Rushing through or neglecting this stage can lead to missed opportunities and unreliable outcomes.


#### 🌟 Why This Step Matters  
This foundational phase helps you address key questions that will shape your analysis and its impact:  
- **🎯 What are the main objectives of this analysis?**  
- **👥 Who will benefit from the insights?**  
- **📊 Is the dataset robust enough to answer these questions effectively?**

By tackling these questions upfront, you establish a clear roadmap for your analysis. Consider how this applies to pizza sales data:  
- 📅 Should we focus on daily sales trends to adjust staffing schedules?  
- 🍕 Do we need insights into top-performing pizza categories to refine marketing strategies?  
- ⏰ Is identifying peak sales hours vital for optimizing inventory management?  

Answering these questions ensures your analysis is both aligned with stakeholder priorities and equipped to drive meaningful results.


#### 🛠️ Steps to Build a Strong Foundation  

1. **Clarify Project Objectives** 📝  
   - Start by collaborating with stakeholders to understand their goals. Are they looking to:  
     - Boost operational efficiency? 🔄  
     - Drive higher revenue? 💹  
     - Gain a clearer picture of customer preferences? 👥🍕  
   - Refine broad goals into specific, actionable objectives, such as:  
     - "Identify peak sales hours to improve staffing schedules." ⏱️  
     - "Highlight best-selling pizza categories to shape promotional efforts." 📈  
     - "Analyze seasonal trends to plan marketing campaigns." 🌞❄️  
   
   Well-defined objectives act as your compass, guiding every decision throughout the analysis process.

2. **Explore the Dataset** 🔍  
   - Now that you've successfully imported and opened the pizza sales dataset, take a
     moment to delve into its structure and contents. Familiarizing yourself with the dataset
     is crucial for effective analysis. Focus on the following key columns:
  
     - `pizza_id`: Tracks sales by pizza type. 🍕  
     - `order_date` and `order_time`: Enable analysis of time-based trends. 📅⏰  
     - `total_price`: Reveals revenue contributions per order. 💰  
     - `pizza_size` and `pizza_category`: Highlight customer preferences by size and category. 📏  

   - Identify potential data gaps or inconsistencies early, ensuring you’re prepared to address them during cleaning and transformation.

3. **Ask Guiding Questions** ❓  
   Thoughtful questions can help prioritize areas of focus for your analysis. Examples include:  
   - "Which pizzas contribute the most to overall revenue?" 💸  
   - "At what times of the day do sales peak?" ⏰  
   - "Are smaller pizzas more popular on weekends compared to weekdays?" 🍕📏  

   These questions ensure your analysis stays targeted and stakeholder-aligned.

4. **Set Clear Analytical Goals** 🎯  
   - Define specific outcomes to achieve with your analysis, such as:  
     - Identifying high-performing pizzas to inform menu adjustments. 📋  
     - Uncovering seasonal sales trends to align marketing efforts. 🌼❄️  
     - Pinpointing peak hours for optimized staffing and inventory management. 🛒  

   Clear goals make your work purposeful, measurable, and directly impactful to decision-making processes.


#### 💡 Expert Insight  

**Pro Tip**: Engage with stakeholders early and often. Their insights might reveal hidden opportunities, such as targeting lunch-hour sales with promotions or introducing a new pizza size to meet untapped demand. 🍽️✨  

**Another Tip**: Start with a preliminary PivotTable or summary chart. This can quickly highlight trends, validate assumptions, and uncover unexpected patterns before diving into more complex analysis. 📊  


#### 📝 Final Thoughts  

Approaching this phase with diligence and expertise sets the tone for the entire project. It’s more than just getting to know your data—it’s about aligning your analysis with stakeholder goals and setting a strong foundation for meaningful insights. This is where raw data evolves into a strategic roadmap, ensuring that every step forward is intentional and impactful.

Remember, starting with clarity and purpose allows you to tell a compelling, data-driven story that goes beyond answering questions—it empowers stakeholders to act with confidence and precision. 💼🚀

---

### 8.3🧹 Data Cleaning and Formatting <a id="data-cleaning-and-formatting"></a>

Every data analytics project relies on clean, well-prepared data as its foundation. Think of this step as sharpening your tools before starting a big project—skipping it can lead to messy analysis and unreliable insights. By dedicating time to data cleaning and formatting, you ensure that your analysis is accurate, reliable, and actionable. Let’s break this process down into practical, expert-backed steps.


#### 🌟 Why Is Data Cleaning and Formatting Essential?
- **🚫 Removes Errors**: Ensures duplicate or irrelevant data doesn’t skew your analysis.  
- **📊 Enhances Readability**: Clean, consistent data makes it easier to interpret trends.  
- **🎯 Boosts Accuracy**: Standardized formats reduce errors during calculations and visualizations.  
- **📈 Sets a Strong Foundation**: Prepares your dataset for seamless transformations and reliable insights.


#### 🛠️ Steps to Clean Your Data  

#### 1. **Remove Duplicate Records** 🗂️  
Duplicates can distort your analysis, so let’s clear them out:  
- **How to Remove Duplicates**:  
  1. Select your data table.  
  2. Navigate to **Data > Remove Duplicates** in the Ribbon.  
  3. Review and confirm the columns to check for duplicates, then click OK.  
  - **Shortcut**: Use `Alt+A+M` (Windows) for quicker access.  

**💡 Pro Tip**: Always keep a backup of your dataset before removing duplicates to avoid accidental loss of important information.


#### 2. **Handle Missing Values** 🔍  
Missing values can lead to gaps in analysis. Here’s how to identify and manage them effectively:  
- **Identify Missing Values**:  
  1. Highlight your entire dataset with `Ctrl+A` (Windows) or `Command+A` (Mac).  
  2. Apply **Conditional Formatting** to make blanks stand out:  
     - Go to **Home > Conditional Formatting > Highlight Cells Rules > More Rules**.  
     - Choose **Format only cells that contain > Blanks**, then select a bright fill color 🌈 for visibility.  
- **Address Missing Values**:  
  - **Replace with Averages**: For numerical data, use averages or median values.  
  - **Mark as N/A**: If applicable, use “N/A” for qualitative data gaps.  

**🔍 Pro Tip**: Use filters to isolate blank cells and evaluate the context before deciding how to fill or remove them.


#### 🧾 Steps to Format Your Data  

#### 1. **Rename Your Table for Clarity** ✍️  
- Default names like "Table 1" can get confusing. Let’s make it easier:  
  1. Select your table and go to **Table Design > Table Name**.  
  2. Rename it to something intuitive, like `pizza_sales`.  
  3. Hit Enter to apply the change.  

**💡 Why Rename?** Clear table names make referencing data in formulas or charts simpler and more intuitive.


#### 2. **Format Data Columns for Consistency** 🧮  
Proper formatting ensures your data is uniform and ready for analysis:  

1. **Date Formatting** 📅:  
   - Select the `order_date` column.  
   - Press `Ctrl+1` (Windows) or `Command+1` (Mac) to open the **Format Cells** dialog.  
   - Choose a clear date format and apply it.  

2. **Time Formatting** ⏰:  
   - Repeat the above steps for the `order_time` column, selecting a time-specific format.

3. **Currency Values** 💵:  
   - Format `unit_price` and `total_price` columns as **Currency** to ensure clarity.  
   - Use the currency symbol relevant to your dataset (e.g., `$`).

4. **Quantity as Whole Numbers** 🔢:  
   - Format the `quantity` column as **Number** with zero decimal places, as it represents units sold.

5. **Text Fields** 📝:  
   - For columns like `pizza_name`, `pizza_category`, and `pizza_size`, ensure the format is set to **Text**.  
   - Scan for typos or inconsistencies that could affect analysis.


#### 🏁 Final Checks: Review and Standardize  

- After formatting, review the dataset to ensure:  
  - All columns are consistent and follow a logical structure.  
  - Any inconsistencies or anomalies are addressed before moving forward.  

**💡 Expert Insight**: Consider creating a summary table or small PivotTable to validate your cleaned data. This step can help identify lingering issues early in the process.  


#### 📣 Why This Step Is Critical  

Taking the time to clean and format your data is an investment in the success of your project. This phase transforms raw, messy datasets into a polished foundation, ensuring that every subsequent step—analysis, visualization, and decision-making—is built on reliable information.

Approach this step with precision and care, and you’ll be rewarded with insights that are accurate, meaningful, and actionable. After all, clean data is the bedrock of every impactful analysis. 🚀✨


---


### 8.4 🔄 Data Transformation <a id="data-transformation"></a>

Transforming raw data into actionable insights is the cornerstone of any successful data analytics project. In this phase, we enhance the dataset by adding calculated columns that help reveal patterns, segment data, and provide clarity. This process equips us to answer critical business questions and unlock valuable opportunities hidden within the data.

Think of data transformation as chiseling a rough diamond into a sparkling gem—it's all about refining your dataset to make it shine. Let’s dive into this essential process! 🌟

This guide outlines the steps to create three new columns in your Excel spreadsheet: `order_day`, `order_month`, and `order_hour`. These columns will deepen our understanding of sales patterns by providing insights into the day of the week, the month, and the hour when orders are placed.

#### Creating the `order_day` Column

The `order_day` column helps us identify sales trends based on the day of the week. Follow these steps to add this column:

1. **Locate an Empty Column**: 
   - Find an empty column to the right of your existing data table.
   - In the header cell of this column, type `order_day` and press Enter.

2. **Insert the Formula**:
   - Click on the first cell directly beneath the `order_day` header.
   - Type the following formula:
     ```excel
     =TEXT([@[Order Date]], "dddd")
     ```
   - Press Enter to apply the formula. Excel will automatically fill down the column, displaying the full day names (e.g., "Monday", "Tuesday").

#### Creating the `order_month` Column

The `order_month` column provides insights into monthly sales trends. To add this column, follow these steps:

1. **Find an Empty Column**: 
   - Locate the next empty column to the right of your table.
   - In the header cell, type `order_month` and hit Enter.

2. **Insert the Formula**:
   - Click on the first cell under the `order_month` header.
   - Enter the following formula:
     ```excel
     =TEXT([@[Order Date]], "mmmm")
     ```
   - Press Enter to apply the formula. Excel will auto-fill the column with full month names (e.g., "January", "February").

#### Creating the `order_hour` Column

The `order_hour` column allows us to analyze the distribution of orders by hour. Follow these steps to create this column:

1. **Find an Empty Column**: 
   - Identify an empty column to the right of your data.
   - In the header cell, type `order_hour` and press Enter.

2. **Insert the Formula**:
   - Click on the first cell beneath the `order_hour` header.
   - Input the following formula:
     ```excel
     =HOUR([@[Order Time]])
     ```
   - Press Enter to apply the formula. Excel will automatically fill down the column, displaying the hour for each order (e.g., "14" for 2:00 PM).

#### 🚀 Why These Columns Matter

By adding calculated fields like `order_day`, `order_month`, and `order_hour`, you create a dataset that’s primed for deeper insights. These columns unlock powerful opportunities to:

- 📊 **Visualize Data**: Create PivotTables and charts for trend analysis.
- 🎯 **Drive Decisions**: Inform strategies for staffing, inventory, and promotions.
- 🔑 **Uncover Opportunities**: Identify untapped markets, such as lunch-hour specials or seasonal promotions.

#### 📝 Final Thoughts

Data transformation is where the magic begins! It’s not merely about adding columns—it’s about enabling your dataset to tell a story that drives actionable results. By taking the time to thoughtfully transform your data, you set the stage for analysis that is insightful, precise, and impactful.

Remember, every calculated field you add is a step closer to uncovering the full potential of your data. Start small, ask questions, and let the insights guide you toward better decisions. 📈✨


---


### 8.5 🔑 Key Performance Indicator (KPI) Definition <a id="key-performance-indicator-kpi-definition"></a>

KPI are **essential metrics** that allow businesses to track progress, measure performance, and achieve their strategic goals. Incorporating KPI into data analysis and dashboards highlights key insights, enabling swift, data-driven decision-making. By focusing on KPI, we align analysis efforts with business objectives, delivering actionable insights that truly matter. Let’s dive into how to set up and calculate KPI in Microsoft Excel for a **Pizza Sales Analysis** project.


#### 📋 Setting Up Your KPI Worksheet

The KPI worksheet serves as a **dedicated space** to organize and calculate critical metrics. Here’s how to create one:

1. **Create a New Sheet**:  
   - At the bottom of your workbook, click the **“+” icon** to create a new worksheet.

2. **Rename the Sheet**:  
   - Right-click the new sheet’s tab, select **Rename**, and type `KPI` to give it a clear and descriptive name.

3. **Organize Your KPI**:  
   - Use this sheet as your central hub for all KPI calculations. This structured approach ensures clarity and easy referencing during analysis.


#### 🛠 Step-by-Step Guide to Calculating KPI

#### 1. **Total Sales** 💰

This metric tracks the total revenue generated from all pizza orders, providing a clear picture of overall sales performance.

#### Steps to Calculate:
1. **Label the KPI**:  
   - In cell `A1` of the `KPI` sheet, type `Total Sales`.

2. **Enter the Formula**:  
   - In cell `B1`, input the formula to calculate total sales:  
     ```excel
     =SUM(Pizza_sales[total_price])
     ```
   - This formula sums up the `Total Price` column from the dataset.

3. **Apply the Formula**:  
   - Press **Enter**. The result will display the total revenue (`$817,860`).

4. **Format the Result**:  
   - Right-click cell `B1`, select **Format Cells**, choose **Currency**, and click **OK**.

#### Why It Matters:  
The **Total Sales** KPI is the foundation for understanding revenue performance, identifying trends, and setting benchmarks.


#### 2. **Average Order Value (AOV)** 📊

The AOV reveals how much revenue is generated on average per order, offering insights into customer spending behavior.

#### Steps to Calculate:
1. **Label the KPI**:  
   - In cell `A2`, type `Average Order Value`.

2. **Enter the Formula**:  
   - In cell `B2`, input the following formula:  
     ```excel
     =SUM(Pizza_sales[total_price]) / COUNTA(UNIQUE(Pizza_sales[order_id]))
     ```
   - This formula divides the total revenue by the number of unique orders.

3. **Apply the Formula**:  
   - Press **Enter**. The result will display the average revenue per order (`$38.30`).

4. **Format the Result**:  
   - Right-click cell `B2`, select **Format Cells**, and apply **Currency** formatting with zero decimal places.

#### Why It Matters:  
The AOV helps in assessing customer purchasing power, refining pricing strategies, and monitoring the impact of promotions.


#### 3. **Total Pizzas Sold** 🍕

This KPI calculates the total number of pizzas sold, giving insight into sales volume and demand patterns.

#### Steps to Calculate:
1. **Label the KPI**:  
   - In cell `A3`, type `Total Pizzas Sold`.

2. **Enter the Formula**:  
   - In cell `B3`, input the formula:  
     ```excel
     =SUM(Pizza_sales[quantity])
     ```

3. **Apply the Formula**:  
   - Press **Enter**. The result will display the total pizzas sold (`49574`).

4. **Format the Result**:  
   - Right-click cell `B3`, select **Format Cells**, and choose **Number** formatting.

#### Why It Matters:  
Knowing the total pizzas sold helps identify demand trends, plan inventory, and allocate resources effectively.


#### 4. **Total Orders** 📦

This KPI provides the total number of unique orders, helping to understand transaction volume and customer activity.

#### Steps to Calculate:
1. **Label the KPI**:  
   - In cell `A4`, type `Total Orders`.

2. **Enter the Formula**:  
   - In cell `B4`, input the formula:  
     ```excel
     =COUNTA(UNIQUE(Pizza_sales[order_id]))
     ```

3. **Apply the Formula**:  
   - Press **Enter**. The result will display the total orders (`21350`).

4. **Format the Result**:  
   - Right-click cell `B4`, select **Format Cells**, and apply **Number** formatting.

#### Why It Matters:  
The **Total Orders** KPI tracks customer activity, providing a clear measure of transactional volume and operational workload.


#### 5. **Average Pizzas Per Order** 🔢

This metric calculates the average number of pizzas per transaction, offering insights into customer buying behavior.

#### Steps to Calculate:
1. **Label the KPI**:  
   - In cell `A5`, type `Average Pizzas Per Order`.

2. **Enter the Formula**:  
   - In cell `B5`, input the formula:  
     ```excel
     =ROUND(SUM(Pizza_sales[quantity]) / COUNTA(UNIQUE(Pizza_sales[order_id])), 2)
     ```

3. **Apply the Formula**:  
   - Press **Enter**. The result will display the average pizzas per order (`2.32`).

4. **Format the Result**:  
   - Right-click cell `B5`, select **Format Cells**, and choose **Number** formatting.

#### Why It Matters:  
This KPI provides insights into order size trends, helping to refine menu offerings and bundle deals.


#### 🚀 Final Thoughts

By thoughtfully calculating KPI such as **Total Sales**, **AOV**, and **Total Pizzas Sold**, you unlock actionable insights that drive strategic decisions. Each KPI serves as a lens, offering unique perspectives into performance, customer behavior, and operational efficiency.

**Pro Tip**: Always keep your KPI aligned with business goals. Regularly review and refine them to ensure they remain relevant and impactful. 📈✨


---


### 8.6 🎨 Data Visualization and Analysis <a id="data-visualization-and-analysis"></a>

#### 8.6.1 📊 ***<ins>Analyzing Sales by Hour of the Day</ins>*** 📊

**First** analyzing **sales trends by hour** is a cornerstone of data-driven decision-making. It reveals customer behavior and peak activity times, empowering businesses to optimize staffing, align inventory, and schedule targeted promotions. By leveraging **PivotTables**, **PivotCharts**, and **Slicers**, we can transform raw data into actionable insights. Let’s dive into this crucial step. 📊✨


#### 🌟 Why Analyze Hourly Sales?

This analysis answers pivotal business questions:
- **⏰ When are customers most active?**
- **📊 How can we align operations with peak hours?**
- **🍕 Which product sizes perform best at specific times?**

These insights enable resource optimization, time-specific promotions, and accurate inventory management.


#### Step 1: Create a PivotTable for Hourly Sales Analysis

A **PivotTable** structures and summarizes sales data, making it easy to identify revenue patterns by hour.

### Steps to Insert and Configure the PivotTable
1. **Insert the PivotTable**:
   - **Select the Dataset**: Click any cell within your dataset.
   - **Navigate to the Insert Tab**: Go to **Insert** > **PivotTable**.
   - **Choose New Worksheet**: In the dialog box, select **New Worksheet** and click **OK**.

2. **Rename the Worksheet for Clarity**:
   - **Right-Click the Worksheet Tab**: Select **Rename**.
   - **Enter "Sales by Hour"**: This descriptive name improves navigation.

3. **Set Up PivotTable Fields**:
   - **Drag `order_time` to Rows**: Group times by hour (e.g., "00:00," "01:00").
     - **Grouping Tip**: If not grouped, right-click a time value, select **Group**, and choose **Hours**.
   - **Drag `total_price` to Values**: Calculate total revenue for each hour.
   - **Ensure Summation**: Right-click `total_price` in the Values area, select **Value Field Settings**, and choose **Sum**.

4. **Sort the Data**:
   - **Highlight Peak Hours**: Click **Sort & Filter** in the PivotTable Tools.
   - **Sort by Revenue (Descending)**: Display hours from highest to lowest revenue.

#### 🎯 Outcome:
Your PivotTable now showcases hourly revenue, pinpointing peak customer activity periods.


#### Step 2: Create a Column Chart for Hourly Sales

Visualizing data with a **Column Chart** enables quick comparisons and actionable insights.

#### Steps to Create the Chart
1. **Insert the Chart**:
   - Highlight the PivotTable range.
   - Navigate to **Insert** > **PivotChart** > **Clustered Column**.

2. **Customize the Chart**:
   - **Rename the Chart Title**: Enter **"Sales by Hour of the Day"**.
   - **Adjust Visual Elements**: Use the **Chart Design** and **Format** tabs to modify colors, column widths, and fonts for improved readability.

3. **Enhance Chart Understanding**:
   - Add **Data Labels** to display exact revenue for each hour.
   - Add **Axis Titles**:
     - **X-axis**: Label as **"Hour"**.
     - **Y-axis**: Label as **"Revenue"**.

#### 🎯 Outcome:
Your Column Chart now highlights hourly sales trends, offering a visual guide to optimize operational strategies.


#### Step 3: Add a Slicer for Enhanced Interactivity

A **Slicer** introduces interactivity, allowing users to filter data dynamically by attributes like pizza size.

#### Steps to Add and Use the Slicer
1. **Add the Slicer**:
   - **Select the PivotTable**: Click the PivotTable linked to your chart.
   - **Insert Slicer**: Go to **PivotTable Analyze** > **Insert Slicer**.
   - **Choose `pizza_size`**: Select the field in the dialog box and click **OK**.

2. **Customize the Slicer**:
   - **Position and Style**: Place the slicer near your chart and use the **Slicer Tools > Options** tab to adjust its appearance.

3. **Filter Effectively**:
   - **Single Selection**: Click a size (e.g., "Medium," "Large") to update the chart and PivotTable with relevant data.
   - **Multiple Selections**: Hold **Ctrl** (Windows) or **Command** (Mac) to compare sizes.


#### 🧠 Insights and Applications

#### Identifying Trends:
- **Example**: If "Large" pizzas sell most during lunchtime, this indicates a preference for larger meals midday. Conversely, a preference for "Small" pizzas at dinner reflects a lighter dining trend.

#### Tailoring Promotions:
- **Actionable Insight**: Use these findings to design time-specific promotions, such as offering discounts on "Large" pizzas during lunchtime to boost revenue.

#### Optimizing Inventory:
- **Operational Efficiency**: Ensure sufficient stock for high-demand sizes at peak hours. For instance, prioritize "Medium" pizzas for dinner hours if they consistently dominate sales during that time.


#### 8.6.2 📊 ***<ins>Analyzing Sales by Day of the Week</ins>*** 📊

**Second** understanding **sales trends by day of the week** is a game-changer for optimizing operations and aligning strategies. This analysis helps businesses make informed decisions about **resource allocation**, **scheduling**, and **tailored marketing efforts**. Let’s dive into this critical step to turn raw data into actionable insights using **PivotTables**, **Bar Charts**, and **Slicers**. 📊✨


#### 🌟 Why Analyze Sales by Day of the Week?

This analysis addresses essential business questions:
- **📈 Which days generate the highest revenue?**
- **🛠️ How can we optimize staffing and inventory for peak days?**
- **🔍 Are there patterns tied to specific days of the week?**

Uncovering these insights equips businesses with the knowledge to fine-tune operations and maximize profitability.


#### Step 1: Insert the PivotTable

A **PivotTable** provides a structured summary of daily revenue, enabling precise analysis.

#### Steps to Create the PivotTable
1. **Activate Your Dataset**:  
   - Click on any cell within your dataset.

2. **Navigate to the Insert Tab**:  
   - Go to **Insert** > **PivotTable**.

3. **Choose Worksheet Location**:  
   - In the dialog box, select **New Worksheet** and click **OK**.  
   - This creates a blank PivotTable in a new worksheet.


#### Rename the Worksheet for Clarity
Organize your workbook for easy navigation:
1. **Right-Click on the Worksheet Tab**:  
   - Select **Rename**.

2. **Enter a Descriptive Name**:  
   - Name it **"Sales by Day"**.


#### Set Up the PivotTable Fields
1. **Drag `order_day` to the Rows Area**:  
   - This lists the days of the week (e.g., "Monday," "Tuesday").

2. **Drag `total_price` to the Values Area**:  
   - This calculates the total revenue for each day.

3. **Ensure Accurate Calculations**:  
   - Right-click on `total_price`, select **Value Field Settings**, and choose **Sum**.


#### Sort the Data for Clarity
1. **Highlight Top Days**:  
   - Click on **Sort & Filter** in the PivotTable Tools.

2. **Sort by Total Price (Descending)**:  
   - Display days from highest to lowest revenue.


#### Step 2: Create a Bar Chart for Daily Sales Visualization

A **Bar Chart** provides a clear and comparative view of daily sales performance, making patterns easily identifiable.

### Steps to Create the Bar Chart
1. **Go to the Insert Tab**:  
   - Navigate to the Ribbon.

2. **Select Bar Chart**:  
   - Click **PivotChart** > **Clustered Bar Chart**.

3. **Customize the Chart**:  
   - Rename the title to **"Sales by Day of the Week"**.  
   - Adjust visual elements (e.g., colors, bar width) using the **Chart Design** and **Format** tabs.


#### Add Chart Elements for Enhanced Understanding
1. **Include Data Labels**:  
   - Display exact revenue amounts for each day.

2. **Add Axis Titles**:  
   - X-axis: Label as **"Days of the Week"**.  
   - Y-axis: Label as **"Revenue"**.

This Bar Chart provides a clear visual comparison of daily revenue, helping businesses quickly identify peak days and plan accordingly.


#### Step 3: Add a Slicer for Dynamic Filtering

Adding a **Slicer** introduces interactivity, allowing users to filter data by attributes like pizza categories or sizes for tailored insights.


#### Benefits of Using a Slicer
- **Interactive Filtering**: Quickly explore data for specific attributes.  
- **Focused Insights**: Tailor the analysis to align with business objectives.


#### Steps to Add a Slicer
1. **Select Your PivotTable**:  
   - Click on the PivotTable associated with the Bar Chart.

2. **Navigate to PivotTable Analyze Tab**:  
   - Go to **PivotTable Analyze** > **Insert Slicer**.

3. **Choose a Relevant Field**:  
   - Check `pizza_category` (or another relevant attribute) and click **OK**.


#### Customize the Slicer
1. **Resize and Position the Slicer**:  
   - Place it near the Bar Chart for intuitive access.

2. **Adjust Style and Layout**:  
   - Use **Slicer Tools > Options** to ensure the slicer aligns visually with your dashboard.


#### Using the Slicer Effectively
1. **Filter by Category**:  
   - Click a category (e.g., "Classic," "Veggie") to dynamically update the chart and PivotTable.

2. **Compare Categories**:  
   - Hold **Ctrl** (Windows) or **Command** (Mac) to view multiple categories simultaneously.


#### 🧠 Insights from Slicer Interactions
1. **Comparative Performance**:  
   - Discover that "Classic" pizzas perform best on weekends, while "Veggie" pizzas dominate weekdays.

2. **Tailored Promotions**:  
   - Use insights to run category-specific promotions during peak days.

3. **Operational Optimization**:  
   - Align staffing and inventory with trends observed through filtered data.


#### 8.6.3 📊 ***<ins>Analyzing Sales by Month</ins>*** 📊


**Third** understanding **monthly sales trends** is a cornerstone of effective business planning. This analysis unveils **seasonal patterns**, supports **inventory optimization**, and enhances the timing of promotions. By leveraging **PivotTables**, **Line Charts**, and **Slicers**, raw data transforms into actionable insights. Let’s explore this step-by-step. 📊✨


#### 🌟 Why Analyze Sales by Month?

Monthly sales trends provide answers to vital business questions:
- **📈 Which months generate the highest revenue?**
- **❄️ How do seasonal changes affect sales performance?**
- **🛒 How can promotional campaigns align with peak demand periods?**

Visualizing monthly sales empowers businesses to make informed, strategic decisions, ensuring resources are allocated effectively.


#### Step 1: Create a PivotTable for Monthly Sales Analysis

A **PivotTable** is an essential tool for summarizing data, helping to identify patterns and totals efficiently. Here’s how to set one up.

#### Insert the PivotTable
1. **Activate Your Dataset**:  
   - Click on any cell within your dataset to enable it.  

2. **Navigate to the Ribbon**:  
   - Go to **Insert** > **PivotTable**.

3. **Choose Worksheet Location**:  
   - Select **New Worksheet** in the dialog box and click **OK**.  
   - This action creates a blank PivotTable in a new worksheet.


#### Rename the Worksheet for Clarity
1. **Right-Click on the Worksheet Tab**:  
   - Select **Rename**.  

2. **Enter a Descriptive Name**:  
   - Type **"Sales by Month"** to organize your workbook.


#### Set Up the PivotTable Fields
1. **Drag `order_month` to Rows**:  
   - Lists months (e.g., January, February) in the Rows area.  

2. **Drag `total_price` to Values**:  
   - Calculates total revenue for each month.

3. **Ensure Accurate Calculations**:  
   - Right-click `total_price`, select **Value Field Settings**, and choose **Sum**.


#### Review the Results
- **📊 Observe Monthly Revenue Totals**: Identify high-performing months.
- **🔍 Spot Seasonal Trends**: Recognize patterns and fluctuations indicative of seasonality.

This structured view provides the foundation for decisions related to staffing, promotions, and inventory planning during peak months.


### Step 2: Create a Line Chart for Monthly Sales Trends

A **Line Chart** offers a visual representation of trends over time, highlighting peaks, troughs, and seasonal changes.

### Steps to Create a Line Chart
1. **Go to the Insert Tab**:  
   - Navigate to the **Insert** tab in the Ribbon.

2. **Select Recommended Charts**:  
   - Click **Recommended Charts** > **Line Chart**.  
   - Opt for **Stacked Line with Markers** for a connected view of trends.


#### Customize the Chart for Clarity
1. **Rename the Chart Title**:  
   - Update it to **"Monthly Sales Trend"** for better context.

2. **Adjust Design Elements**:  
   - Use the **Chart Design** and **Format** tabs to customize colors, line styles, and contrast.


#### Add Chart Elements for Enhanced Understanding
1. **Click on Chart Elements (Plus Icon)**:  
   - Include the following elements:
     - **Data Labels**: Display exact revenue amounts.
     - **Axis Titles**:  
       - X-axis: Label as **"Month"**.  
       - Y-axis: Label as **"Revenue"**.


#### Interpretation
This Line Chart provides a visual summary of sales patterns, making it easy to:
- Identify high-demand months.
- Recognize seasonal fluctuations.
- Plan promotions and allocate resources effectively.


#### Step 3: Add a Slicer for Enhanced Interactivity

A **Slicer** enables users to filter data interactively, uncovering deeper insights and enhancing dashboard usability.


#### When to Use a Slicer
Slicers are indispensable for:
- **Interactive Filtering**: Allow users to refine data based on specific attributes.  
- **Focused Insights**: Explore segments of interest for targeted analysis.


#### Steps to Add a Slicer
1. **Select Your PivotTable**:  
   - Click on the PivotTable created earlier.

2. **Navigate to the PivotTable Analyze Tab**:  
   - Go to **PivotTable Analyze** > **Insert Slicer**.

3. **Choose a Relevant Field**:  
   - Check `pizza_category` (or another relevant field) and click **OK**.


#### Customize the Slicer
1. **Resize and Position**:  
   - Place the slicer near the Line Chart for intuitive access.

2. **Adjust Style and Layout**:  
   - Use **Slicer Tools > Options** to align the slicer with the dashboard design.


#### Using the Slicer Effectively
1. **Filter by Category**:  
   - Click on a category (e.g., Classic, Veggie) to dynamically update the chart and PivotTable.

2. **Select Multiple Categories**:  
   - Hold **Ctrl** (Windows) or **Command** (Mac) to compare multiple categories simultaneously.


#### Understanding Outcomes from Using a Slicer
A slicer enhances analysis by enabling:
- **Category-Specific Insights**: Observe trends for specific product categories.
- **Comparative Analysis**: Compare how multiple categories contribute to monthly sales.
- **Strategic Marketing**: Align campaigns with categories that perform well during specific months.


#### 🧠 Insights and Applications

Analyzing monthly sales data ensures businesses can:
- **Plan Ahead**: Align inventory and staffing with seasonal demand.  
- **Optimize Campaigns**: Launch promotions during high-demand months.  
- **Drive Revenue**: Focus resources on periods of peak performance.


#### 8.6.4 🍕 ***<ins>Analyzing Sales by Pizza Size</ins>*** 🍕

**Fourth** understanding sales trends by pizza size is fundamental. This step not only reveals customer preferences but also provides actionable insights for inventory management, promotional planning, and product offerings. By leveraging **PivotTables**, **Bar Charts**, and **Slicers**, we can make informed decisions that align with customer demand and enhance overall business strategy. 📊✨


#### 🌟 Why Analyze Sales by Pizza Size?

This phase answers several critical questions:
- **📏 Which pizza sizes are the most popular among customers?**
- **📦 How can we optimize inventory to meet demand for specific sizes?**
- **📈 Can we tailor promotions to boost sales for underperforming sizes?**

Analyzing sales by pizza size ensures a data-driven approach to meeting customer needs while optimizing resources.


#### Step 1: Create a PivotTable for Pizza Size Sales Analysis

A **PivotTable** is an essential tool for summarizing data and uncovering patterns. Let’s break down the steps to analyze sales by pizza size effectively:

#### Insert the PivotTable
1. **Activate Your Dataset**:  
   - Click on any cell within your dataset to activate it.

2. **Navigate to the Ribbon**:  
   - Go to the **Insert** tab and select **PivotTable**.

3. **Choose Worksheet Location**:  
   - In the dialog box, select **New Worksheet** and click **OK**.  
   - This creates a new worksheet with an empty PivotTable.


#### Rename the Worksheet for Clarity
To maintain organization:
- **Right-click on the New Worksheet Tab**: Select **Rename**.
- **Enter a Descriptive Name**: Type **"Pizza Size Sales"** to simplify navigation.


#### Set Up the PivotTable Fields
Configure the PivotTable to summarize pizza size sales:
- **Drag `pizza_size` to Rows**: This lists sizes like Small, Medium, and Large.
- **Drag `quantity` to Values**: This calculates the total number of pizzas sold per size.

Ensure the `quantity` field is set to Sum:
- **Right-click on `quantity`**: Select **Value Field Settings** and choose **Sum**.


#### Explanation
This PivotTable gives a clear breakdown of total sales by pizza size, allowing us to identify the most and least popular sizes. Such insights are critical for aligning inventory levels with customer demand and planning promotions effectively.


#### Step 2: Create a Bar Chart for Sales by Pizza Size

Visualizing the data makes it easier to interpret trends and communicate findings. A **Bar Chart** is ideal for comparing sales across pizza sizes.



#### Steps to Create a Bar Chart
1. **Go to the Insert Tab**:  
   - Navigate to the Ribbon and click on **PivotChart** in the Charts group.

2. **Select Bar Chart**:  
   - Choose **Clustered Bar** for clear and straightforward comparisons.


#### Customize the Chart for Clarity
Enhance the chart for better readability:
- **Rename the Chart Title**:  
   - Update it to **“Sales by Pizza Size”** for context.
- **Adjust Design Elements**:  
   - Use the Chart Design and Format tabs to modify colors, bar width, and spacing for improved visibility.


#### Add Chart Elements for Improved Understanding
Include essential chart elements:
- **Data Labels**: Show the exact number of pizzas sold for each size.
- **Axis Titles**:  
   - X-axis: Label as **"Pizza Size"**.  
   - Y-axis: Label as **"Quantity Sold"**.


#### Interpretation
This Bar Chart offers a quick, visual comparison of sales by pizza size, helping identify which sizes drive the most revenue. Such insights enable data-driven decisions regarding inventory management and promotional strategies.


### Step 3: Add a Slicer for Enhanced Interactivity

Adding a **Slicer** enables dynamic filtering, allowing users to explore data interactively and uncover deeper insights.


#### When to Use a Slicer
Slicers are valuable for:
- **Interactive Filtering**: Quickly narrow down data by specific attributes.  
- **Exploring Specific Segments**: Focus on data points that align with business goals.


#### Steps to Add a Slicer
1. **Select Your PivotTable**:  
   - Click on the PivotTable you created.

2. **Navigate to PivotTable Analyze Tab**:  
   - Go to the Ribbon and click on **Insert Slicer**.

3. **Select Relevant Field**:  
   - Check `pizza_category` (or another attribute) in the dialog box and click **OK**.


#### Customize the Slicer
Make the slicer visually appealing and functional:
- **Resize and Position**: Place it near the Bar Chart for easy interaction.
- **Adjust Style and Layout**: Use the **Slicer Tools > Options** tab to match the dashboard’s overall design.


#### Using the Slicer Effectively
1. **Filter by Category**:  
   - Click a category name (e.g., Classic, Veggie) to dynamically update the PivotTable and chart.
2. **Select Multiple Categories**:  
   - Hold **Ctrl** to filter data across multiple categories.


#### Outcomes from Using a Slicer
1. **Identify Trends**:  
   - Uncover how customer preferences vary by pizza size.
2. **Compare Categories**:  
   - Analyze performance across multiple pizza categories.
3. **Targeted Promotions**:  
   - Develop campaigns for sizes with specific trends or performance.


#### 🧠 Insights and Applications
Analyzing sales by pizza size provides critical insights into customer behavior. Use this knowledge to:
- Align inventory with demand.  
- Focus promotions on high-performing sizes.  
- Address underperforming products through targeted strategies.


#### 8.6.5 🍕 ***<ins>Analyzing Sales by Pizza Category</ins>*** 🍕


**Fifth** we now shift our focus to analyzing **pizza categories**. This step is pivotal in understanding customer preferences across different pizza types, enabling us to refine marketing strategies, streamline inventory management, and optimize our menu offerings. 📊✨


#### 🌟 Why Analyze Sales by Pizza Category?

This analysis helps answer critical questions:
- **Which pizza categories are most popular among customers?**  
- **How can we optimize marketing efforts to target specific categories?**  
- **Which categories should we prioritize in promotions or inventory planning?**  

By identifying trends in pizza categories, businesses can better align their strategies with customer demand.


#### Step 1: Create a PivotTable for Pizza Category Sales Analysis

A **PivotTable** is a powerful tool for summarizing and organizing data, making it easier to identify patterns and insights. Let’s build a PivotTable to analyze sales by pizza category.

#### Insert the PivotTable
1. **Activate Your Dataset**:  
   - Click on any cell within your dataset to activate it.
   
2. **Navigate to the Ribbon**:  
   - Go to the **Insert** tab and select **PivotTable**.

3. **Choose Worksheet Location**:  
   - In the dialog box, select **New Worksheet** and click **OK**.  
   - This creates a new worksheet with an empty PivotTable.


#### Rename the Worksheet for Clarity
To keep your workbook organized:
- **Right-click on the New Worksheet Tab**: Select **Rename**.
- **Enter a Descriptive Name**: Type **"Pizza Category Sales"** for easy navigation.


#### Set Up the PivotTable Fields
1. **Drag `pizza_category` to Rows**:  
   - This lists categories like Classic, Veggie, and Supreme.
   
2. **Drag `total_price` to Values**:  
   - This calculates the total revenue for each pizza category.

3. **Ensure Accurate Calculations**:  
   - Right-click on `total_price`, select **Value Field Settings**, and choose **Sum**.


#### Explanation
This PivotTable provides a clear view of revenue generated by each pizza category, helping identify which categories are most popular. This insight is crucial for tailoring inventory, marketing, and promotional efforts to meet customer preferences.


#### Step 2: Create a Bar Chart for Sales by Pizza Category

Visualizing data with a **Bar Chart** makes trends easier to interpret and communicate.

#### Steps to Create a Bar Chart
1. **Go to the Insert Tab**:  
   - Navigate to the Ribbon and click on **PivotChart** in the Charts group.

2. **Select Bar Chart**:  
   - Choose **Clustered Bar** for a straightforward comparison.


#### Customize the Chart for Clarity
Enhance the chart for readability:
- **Rename the Chart Title**:  
   - Update it to **“Sales by Pizza Category”** for immediate context.
   
- **Adjust Design Elements**:  
   - Use the Chart Design and Format tabs to modify colors, bar widths, and spacing.


#### Add Chart Elements for Improved Understanding
Include essential elements:
- **Data Labels**: Display exact revenue amounts for each category.
- **Axis Titles**:  
   - Label the x-axis as **"Pizza Category"**.  
   - Label the y-axis as **"Revenue"**.


#### Interpretation
The Bar Chart highlights the revenue contribution of each pizza category. This visualization makes it easier to identify which categories are driving sales, enabling data-backed decisions to optimize resources and marketing campaigns. 📈🍕


#### Step 3: Add a Slicer for Enhanced Interactivity

Adding a **Slicer** allows users to filter sales data interactively by specific attributes, enhancing the depth and flexibility of your analysis.


#### When to Use a Slicer
Slicers are valuable for:
- **Interactive Filtering**: Quickly refine data by specific attributes like size or promotions.  
- **Segmented Analysis**: Explore subsets of data to uncover unique trends.


#### Steps to Add a Slicer
1. **Select Your PivotTable**:  
   - Click on the PivotTable you created.

2. **Navigate to PivotTable Analyze Tab**:  
   - Go to the Ribbon and click **Insert Slicer**.

3. **Select Relevant Field**:  
   - In the dialog box, check `pizza_size` (or another relevant attribute) and click **OK**.


#### Customize the Slicer
Make the slicer visually appealing and user-friendly:
- **Resize and Position**: Place it next to the Bar Chart for easy interaction.
- **Adjust Style and Layout**: Use the **Slicer Tools > Options** tab to align its style with your dashboard design.


#### Using the Slicer Effectively
1. **Filter by Size or Promotion**:  
   - Click a size or promotion in the slicer to dynamically update the PivotTable and chart.

2. **Select Multiple Options**:  
   - Hold **Ctrl** to analyze combined data across multiple selections.


#### Understanding Outcomes from Using a Slicer
Slicers enhance your analysis by:
- **Identifying Trends Over Time**:  
   - Observe how sales vary among different pizza categories or sizes.
   
- **Enabling Comparative Analysis**:  
   - Compare the impact of multiple categories or sizes on overall sales.
   
- **Guiding Targeted Strategies**:  
   - Develop promotions for underperforming categories or capitalize on high-performing ones during peak seasons.


#### 🧠 Insights and Applications
Analyzing sales by pizza category provides actionable insights to:
- Focus inventory on high-demand categories.  
- Tailor promotions to drive sales in specific categories.  
- Address low-performing categories with strategic interventions.

#### 8.6.6 🍕 ***<ins>Identifying Top 5 Best-Selling Pizzas</ins>*** 🍕

**Sixth** understanding which pizzas are most popular is key to shaping inventory management, refining marketing strategies, and aligning operations with customer demand. By analyzing the **Top 5 Best-Selling Pizzas**, you gain actionable insights into consumer preferences that drive business success. Let’s break down the process step by step. 🚀📊


#### 🌟 Why Analyze Top 5 Best-Selling Pizzas?

This analysis answers critical questions:
- **🎯 Which pizzas generate the most revenue?**
- **📈 How can we optimize inventory for high-demand products?**
- **💡 What marketing strategies can boost sales for popular pizzas?**

By identifying your best-sellers, you ensure your business focuses on the right products to maximize profit and customer satisfaction.


#### Step 1: Create a PivotTable for Best-Selling Pizzas Analysis

A **PivotTable** is the backbone of this analysis, helping to summarize sales data and identify revenue patterns.

#### Steps to Insert and Configure the PivotTable

1. **Insert the PivotTable**:
   - **Select the Dataset**: Click on any cell within your dataset.
   - **Navigate to the Insert Tab**: Go to **Insert** > **PivotTable**.
   - **Choose New Worksheet**: In the dialog box, select **New Worksheet** and click **OK**.

2. **Rename the Worksheet for Clarity**:
   - **Right-Click the Worksheet Tab**: Select **Rename**.
   - **Enter "Top 5 Best-Selling Pizzas"**: This makes it easy to locate this analysis.

3. **Set Up PivotTable Fields**:
   - **Drag `pizza_name` to Rows**: This lists each pizza type.
   - **Drag `total_price` to Values**: This calculates total revenue for each pizza type.
   - **Ensure Summation**: Right-click `total_price` in the Values area, select **Value Field Settings**, and choose **Sum**.

#### 🎯 Outcome:
Your PivotTable now displays total revenue by pizza type, offering a clear view of your best-selling pizzas.


#### Step 2: Sort and Filter for Top 5 Best-Selling Pizzas

Sorting and filtering allow you to focus specifically on your top performers.

#### Steps to Sort and Filter the PivotTable

1. **Sort by Total Revenue**:
   - Click any cell in the `total_price` column.
   - Go to **Sort & Filter** in the Ribbon and select **Sort Largest to Smallest**.

2. **Filter for Top 5 Items**:
   - Click the drop-down arrow next to **Row Labels**.
   - Select **Value Filters** > **Top 10**.
   - In the dialog box, change "10" to "5" and ensure it filters by **Sum of total_price**. Click **OK**.

#### 🎯 Outcome:
Your filtered PivotTable now highlights the top 5 pizzas, giving a focused view of your highest revenue generators.


#### Step 3: Create a Doughnut Chart for Visualizing Top 5 Best-Selling Pizzas

A **Doughnut Chart** visually represents the proportion of revenue contributed by each of the top 5 pizzas.

#### Steps to Create and Customize the Chart

1. **Insert the Doughnut Chart**:
   - Select the filtered PivotTable range.
   - Go to **Insert** > **PivotChart** > **Doughnut Chart**.

2. **Customize the Chart**:
   - **Rename the Chart Title**: Enter **"Top 5 Best-Selling Pizzas"**.
   - **Adjust Design Elements**:
     - Use the **Chart Design** and **Format** tabs to select contrasting colors for clarity.
   - **Add Data Labels**:
     - Click the **Chart Elements** button (plus icon) and enable **Data Labels** to display exact revenue amounts.

#### 🎯 Outcome:
Your Doughnut Chart offers a clear visual breakdown of revenue shares among the top 5 pizzas, making it easy to interpret customer preferences.


#### Step 4: Add a Slicer for Enhanced Interactivity

Adding a **Slicer** introduces interactivity, allowing users to explore data dynamically by attributes like size or category.

#### Steps to Add and Customize the Slicer

1. **Insert the Slicer**:
   - Select the PivotTable.
   - Go to **PivotTable Analyze** > **Insert Slicer**.
   - Check **`pizza_category`** (or another relevant field) and click **OK**.

2. **Customize the Slicer**:
   - **Position and Resize**: Place it near the Doughnut Chart for intuitive filtering.
   - **Style the Slicer**: Use **Slicer Tools > Options** to adjust its appearance.

3. **Using the Slicer**:
   - **Filter by Category**: Click a category (e.g., "Classic") to update the chart and PivotTable dynamically.
   - **Select Multiple Categories**: Hold **Ctrl** (Windows) or **Command** (Mac) to compare multiple categories.


#### 🧠 Insights and Applications

#### Identifying Customer Preferences:
- **Example**: If "Pepperoni" dominates the top 5, it indicates strong customer demand for classic flavors. Use this insight to prioritize inventory and promotions.

#### Shaping Marketing Campaigns:
- Highlight best-sellers in advertising campaigns to attract more customers and boost revenue.

#### Optimizing Operations:
- Align staffing and supply chain strategies to ensure popular items are always available, especially during peak periods.

#### 8.6.7 🍕 ***<ins>Identifying Bottom 5 Worst-Selling Pizzas</ins>*** 🍕

**Lastly** understanding the **Bottom 5 Worst-Selling Pizzas** is essential for refining inventory management, developing targeted marketing strategies, and adjusting menu offerings to meet customer demands. This analysis provides critical insights into underperforming products and helps businesses take corrective actions to improve overall sales. Let’s explore this step-by-step process. 📉🔍

####

#### 🌟 Why Analyze Worst-Selling Pizzas?

Analyzing underperforming items answers important business questions:
- **❓ Why are certain pizzas not selling well?**
- **📦 How can we optimize inventory to reduce waste?**
- **💡 Can we revamp or promote these pizzas to improve sales?**

This process highlights areas for improvement, offering opportunities to refine menu strategies and better meet customer preferences.

####

#### Step 1: Create a PivotTable for Worst-Selling Pizzas Analysis

A **PivotTable** is an efficient tool to summarize and analyze sales data, helping us pinpoint the least popular items quickly.

#### Steps to Insert and Configure the PivotTable

1. **Insert the PivotTable**:
   - **Select the Dataset**: Click on any cell within your dataset.
   - **Navigate to the Insert Tab**: Go to **Insert** > **PivotTable**.
   - **Choose New Worksheet**: In the dialog box, select **New Worksheet** and click **OK**.

2. **Rename the Worksheet for Clarity**:
   - **Right-Click the Worksheet Tab**: Select **Rename**.
   - **Enter "Bottom 5 Worst-Selling Pizzas"**: This ensures your analysis is clearly labeled.

3. **Set Up PivotTable Fields**:
   - **Drag `pizza_name` to Rows**: This lists all pizza types in the Rows area.
   - **Drag `total_price` to Values**: This calculates total revenue for each pizza.
   - **Ensure Summation**: Right-click `total_price` in the Values area, select **Value Field Settings**, and choose **Sum**.

#### 🎯 Outcome:
Your PivotTable now provides a summary of total revenue for each pizza type, making it easy to identify low-performing items.

####

#### Step 2: Sort and Filter for Bottom 5 Worst-Selling Pizzas

Sorting and filtering refine the data, allowing you to focus on the pizzas with the lowest sales.

#### Steps to Sort and Filter the PivotTable

1. **Sort by Total Revenue**:
   - Click any cell in the `total_price` column.
   - Go to **Sort & Filter** in the Ribbon and select **Sort Smallest to Largest**.

2. **Filter for Bottom 5 Items**:
   - Click the drop-down arrow next to **Row Labels**.
   - Select **Value Filters** > **Bottom 10**.
   - In the dialog box, change "10" to "5" and ensure it filters by **Sum of total_price**. Click **OK**.

#### 🎯 Outcome:
Your filtered PivotTable now highlights the bottom 5 worst-selling pizzas, providing a clear focus on underperforming items.


#### Step 3: Create a Doughnut Chart for Visualizing Bottom 5 Worst-Selling Pizzas

A **Doughnut Chart** visually represents the revenue contributions of these underperforming pizzas, making the data easier to interpret.

#### Steps to Create and Customize the Chart

1. **Insert the Doughnut Chart**:
   - Select the filtered PivotTable range.
   - Go to **Insert** > **PivotChart** > **Doughnut Chart**.

2. **Customize the Chart**:
   - **Rename the Chart Title**: Enter **"Bottom 5 Worst-Selling Pizzas"**.
   - **Adjust Design Elements**:
     - Use the **Chart Design** and **Format** tabs to apply contrasting colors for clarity.
   - **Add Data Labels**:
     - Click the **Chart Elements** button (plus icon) and enable **Data Labels** to show exact revenue amounts.

#### 🎯 Outcome:
Your Doughnut Chart provides a clear visualization of the revenue distribution among the bottom 5 pizzas, helping you identify actionable insights.


#### Step 4: Add a Slicer for Enhanced Interactivity

A **Slicer** allows users to filter data dynamically, offering deeper insights into low-performing pizzas across different categories or attributes.

#### Steps to Add and Customize the Slicer

1. **Insert the Slicer**:
   - Select the PivotTable.
   - Go to **PivotTable Analyze** > **Insert Slicer**.
   - Check **`pizza_category`** (or another relevant field) and click **OK**.

2. **Customize the Slicer**:
   - **Position and Resize**: Place the slicer near your Doughnut Chart for easy filtering.
   - **Style the Slicer**: Use **Slicer Tools > Options** to adjust its appearance.

3. **Using the Slicer**:
   - **Filter by Category**: Click a category (e.g., "Classic") to dynamically update the chart and PivotTable.
   - **Select Multiple Categories**: Hold **Ctrl** (Windows) or **Command** (Mac) to compare data across categories.


#### 🧠 Insights and Applications

#### 1. Identifying Problem Areas:
- **Example**: If "Hawaiian" consistently ranks among the bottom 5, it may indicate low customer interest or pricing issues.

#### 2. Developing Targeted Promotions:
- Offer discounts or bundle deals to boost sales for underperforming pizzas.

#### 3. Optimizing Inventory:
- Reduce stock for low-demand pizzas to minimize waste and improve resource allocation.

#### 4. Refining Menu Strategy:
- Consider revising recipes, rebranding items, or even removing persistently underperforming pizzas.


---


#### 8.7 🖥️ Dashboard Development <a id="dashboard-development"></a>
- **User-Friendly Layout**:
  - Positioned KPI prominently at the top for easy reference.
  - Grouped related visuals logically for intuitive navigation.
- **Interactive Features**:
  - Added slicers for filtering by time period, pizza size, and category.
  - Included timelines to explore trends over specific months.


---


## 📈 Dashboard Overview <a id="dashboard-overview"></a>
The final dashboard includes:
- 📊 **Bar Chart:** Shows revenue contribution by pizza type.
- 📈 **Line Chart:** Displays monthly sales trends.
- 🎛 **Interactive Slicers:** Filter data by pizza type or date.

Here’s a preview of the dashboard:

![📊 Dashboard Screenshot](images/dashboard_screenshot.png)


---


## 🔑 Key Findings <a id="key-findings"></a>
1. 🍕 **Pepperoni Pizza** contributes 35% of total revenue, making it the top-selling item.
2. 📅 Sales peak on **weekends**, especially on Saturdays.
3. 🎄 **December** is the highest-performing month, indicating strong seasonal demand.


---


## ⚠️ Limitations <a id="limitations"></a>
- 📆 Dataset only covers one year, limiting long-term trend analysis.
- 🙍‍♀️ Customer demographic data is unavailable, preventing deeper segmentation.


---


## 🚀 Conclusion and Recommendations <a id="conclusion-and-recommendations"></a>
Focus on promoting best-selling pizzas, such as Pepperoni, during peak periods.
Optimize inventory and staffing for weekends and December sales surges.
Develop targeted marketing campaigns based on seasonal trends.


---


## 🤝 Contributing and Feedback
- Have suggestions or improvements? Feel free to open an issue or submit a pull request.
- If you found this project useful, please ⭐ star the repository!
