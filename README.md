# Power-BI-Sales-Analysis-Dashboard
This is the Sales Analytics dashboard for a company that sells bicycles, helmets, bags, and lights. This dashboard will show a full breakdown of their sales by product and year, as well as their budget and variances. For this dashboard, I used three Excel files as sources. This repository also contains the.pbyx file. Please download those excel files together with the.pbyx file and modify the source file location from the data sources setting by clicking on the transform data button which is in queries section.

![Sales Images](https://github.com/user-attachments/assets/2a33f877-afd4-495d-9122-0a3d2f29d45a)


## Sales Forecast
- The Current Year Sales by Date graph forecasts sales for approximately one year based on prior year's sales patterns. This will help the organization arrange their inventor accordingly.

## DAX Functions
- I have sued Calendar() Auto function to create Date table so that it will be easy to visualize the data and to create relationships between the datasets.
  - Then I derived Month, Month_No, Quarter, and Year columns using the date column from the calendar table.
- I have created a few measures, which are listed below for this dataset, using variables and calculate functions.
  - Budget Sales
  - Budget Variation%
  - CY Sales
  - PY sales
  - YOY Growth%

## Visualizations 
- I used many forms of visualizations in this dashboard to present the story of a company's sales in an impactful way, assisting the management in making efficient business decisions.
  - Card
  - Donut Chart
  - Scatter Chart
  - Scattered Area Chart
  - Line Chart
  - Matrix
 
## Tooltips
- I've also added two tooltip pages that provide an in-depth view of the data, allowing for greater understanding of variations in budgets and sales by product category and year.

 

 


