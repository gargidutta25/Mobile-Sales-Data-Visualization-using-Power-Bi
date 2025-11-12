📊 Mobile Sales Data Visualization – Power BI Project

This project showcases an interactive Power BI dashboard built to analyze and visualize mobile sales data across different cities, models, and payment methods. The goal of this project is to transform raw sales data into meaningful business insights through data cleaning, modeling, and visualization.

🚀 Project Overview

The Mobile Sales Dashboard provides a comprehensive view of:

Total Sales, Quantity, and Transactions

Average Unit Price

Sales by City, Mobile Model, and Payment Method

Monthly and Daily Sales Trends

Customer Ratings Distribution

This visualization helps identify high-performing regions, popular phone models, and customer purchase preferences.

🧹 Data Cleaning & Transformation (Power Query Steps)

Performed in Power Query Editor within Microsoft Power BI Desktop:

 Added Custom Column
Formula:

=[Day] & "/" & [Month] & "/" & [Year]


→ Renamed the new column to 'Date'

Changed Data Type with Locale
Ensured the 'Date' column was correctly formatted according to locale.

Reordered Columns
Positioned the 'Date' column appropriately within the dataset.

Removed Unnecessary Columns
Dropped redundant columns: 'Day', 'Month', and 'Year'.

Added Custom Column: 'Day Name'
Derived from the Date column by follwing steps below mentioned:

Add Column → Date → Day → Name of Day


Removed Old 'Day Name' Column
Replaced outdated or redundant versions with the newly derived one.

Adjusted Data Types
Verified and corrected data types for all columns based on their content.

Applied Changes
Selected Close & Apply to load the cleaned data into Power BI.

📈 Tools & Technologies Used

Microsoft Power BI Desktop

Power Query Editor

DAX (Data Analysis Expressions)

Excel (Raw Data Source)

📂 Repository Contents

Mobile Sales Data.xlsx → Raw dataset used for this project

Power BI file (.pbix) → Dashboard file

README.md → Project documentation

📊 Dashboard Highlights

Interactive filters for Month, Brand, and Payment Method

Map visualization of Sales by City

KPI cards for quick business metrics

Trend charts for Monthly and Daily Sales

Model-wise and Brand-wise performance insights

🧠 Key Learnings

Data transformation using Power Query

Creating calculated columns and measures

Building interactive visualizations in Power BI

Data storytelling through dashboards

📬 Feedback

I’d love to hear your thoughts or suggestions for improvement!
Feel free to open an issue or connect with me on LinkedIn
.
