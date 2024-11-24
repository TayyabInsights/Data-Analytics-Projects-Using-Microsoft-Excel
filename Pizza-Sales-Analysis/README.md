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

---

#### 🚀 Final Thoughts

By thoughtfully calculating KPI such as **Total Sales**, **AOV**, and **Total Pizzas Sold**, you unlock actionable insights that drive strategic decisions. Each KPI serves as a lens, offering unique perspectives into performance, customer behavior, and operational efficiency.

**Pro Tip**: Always keep your KPI aligned with business goals. Regularly review and refine them to ensure they remain relevant and impactful. 📈✨


---


### 8.6 🎨 Data Visualization and Analysis <a id="data-visualization-and-analysis"></a>
- **Selected Visuals**:
  - Bar charts for hourly, daily, and size-based sales.
  - Line graphs for monthly trends.
  - Doughnut charts for the top 5 best-selling and bottom 5 worst-selling pizzas.
- **Enhanced Readability**: Applied consistent color schemes and clear labels.


---


### 8.7 🖥️ Dashboard Development <a id="dashboard-development"></a>
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
