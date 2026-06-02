# Electric Vehicle Sales Analysis - India

## 📌 Project Overview
The primary goal of this project is to analyze provided Electric Vehicle (EV) sales data for India. This involved cleaning, transforming, and modeling the data to create an interactive Power BI dashboard. The resulting dashboard answers key business questions regarding sales trends, market penetration, top manufacturers, and regional performance between fiscal years 2022 and 2024.

## 🛠️ Tools & Technologies Used
* **Microsoft Power BI Desktop & Power BI Query:** For loading, transforming, and visualizing the data.
* **Data Modeling:** Built a star schema data model by establishing relationships between the tables using the 'date' column.
* **DAX (Data Analysis Expressions):** Used to create custom measures for complex calculations.

## 📂 Dataset Details
The analysis relies on three core CSV datasets:
1. `electric_vehicle_sales_by_state.csv`: Contains state-level monthly sales data, detailing the number of electric vehicles sold alongside the total vehicles sold for both 2-wheeler and 4-wheeler categories.
2. `electric_vehicle_sales_by_makers.csv`: Provides a breakdown of electric vehicle sales by the manufacturer (maker), vehicle category, and date.
3. `dim_date.csv`: A dimension table that maps each date to its corresponding fiscal year and quarter, enabling time-series analysis.

## 📊 Key Metrics & DAX Calculations
* **Penetration Rate:** Represents the percentage of total vehicles that are electric within a specific region or category.
* **Compound Annual Growth Rate (CAGR):** Measures the mean annual growth rate over a specified period longer than one year.

## 💡 Key Questions Answered in the Dashboard
The dashboard visually explores several critical business questions, including:
* Identifying the top 3 and bottom 3 makers for the fiscal years 2023 and 2024 in terms of 2-wheelers sold.
* Highlighting the top 5 states with the highest penetration rate in 2-wheeler and 4-wheeler EV sales in FY 2024.
* Tracking the quarterly trends based on sales volume for the top 5 EV 4-wheeler makers from 2022 to 2024.
* Discovering the peak and low season months for EV sales.

## 🚀 How to View the Project
1. Download the `.pbix` file from this repository.
2. Open it using Microsoft Power BI Desktop to interact with the slicers and explore the visualizations.
