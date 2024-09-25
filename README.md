# CRM Sales Dashboard

## Overview
This project involves building a CRM Sales Dashboard to track quarterly performance of sales agents and analyze sales pipeline data. The data is prepared, analyzed using pivot tables, and visualized with charts to create an interactive dashboard for easy tracking of opportunities won, lost, and agent performance.

## Project Objectives

### Objective 1: Data Preparation
- Explore and clean the sales pipeline data.
- Join the sales team data to add the manager and regional office information for each sales agent.
- **Key Tasks:**
  - Loaded data from `sales_pipeline.csv` and reviewed for missing values and data integrity.
  - Merged with `sales_teams.csv` to associate each sales agent with their manager and regional office.

### Objective 2: Data Exploration with Pivot Tables
- Analyze sales trends and sales agent performance by creating pivot tables.
- **Key Tasks:**
  - Created a pivot table to show opportunities won by quarter.
  - Built another pivot table to show the percentage of won and lost opportunities by quarter.
  - Created a final pivot table displaying the opportunities won by quarter for each sales agent, sorted by opportunities won in descending order.
  - Structured pivot tables to display quarters as columns, with the most recent quarter first.

### Objective 3: Build Dynamic Dashboard
- Visualize the sales data and create an interactive dashboard.
- **Key Tasks:**
  - Inserted a scorecard to show opportunities won for Q4 2017, compared to Q3 2017.
  - Used a pie chart to visualize the percentage of deals won and lost in Q4 2017.
  - Created a bar chart to show opportunities won by sales agents for Q4 2017.
  - Added slicers for `regional_office` and `manager` fields to filter the dashboard.
  - Arranged the charts and visuals into a clean, interactive dashboard layout.

## Key Insights
1. **Sales Trends**: Opportunities won and lost were analyzed by quarter to identify trends and patterns in sales performance.
2. **Agent Performance**: The dashboard ranks sales agents by their performance, highlighting top performers.
3. **Quarterly Comparison**: A scorecard shows a clear comparison of opportunities won between Q3 and Q4 of 2017.
4. **Regional and Managerial Filtering**: Filters for regional office and managers allow for dynamic tracking of sales performance across different segments.

## Technologies Used
- **Google Sheets**: For data preparation, analysis, and building the pivot tables.
- **Google Sheets Charts**: To visualize the data and create an interactive dashboard.

## How to Use
1. Open the [Google Sheets file](https://docs.google.com/spreadsheets/d/1_1L0qyeObHyCa2hGQHHXYQirksXnHeQFkxWgAhNbuv8/edit?usp=sharing).
2. Explore the pivot tables and visuals created to track sales performance.
3. Use the slicers on the dashboard to filter data by `regional_office` or `manager` to dynamically update the charts.

## Author
- Rolando John R. Aca-ac
