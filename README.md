# Car-Sales-Analysis

## Objective

The objective of this project is to design and develop a dynamic and interactive Car Sales Dashboard using Power BI. The dashboard will visualize critical KPIs related to car sales, helping us understand sales performance over time and make data-driven decisions.

## Problem statement
### KPI REQUIREMENTS
  
#### Sales Overview:
   - Year-to-Date (YTD) Total Sales
   - Month-to-Date (MTD) Total Sales
   - Year-over-Year (YOY) Growth in Total Sales
   - Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales
#### Average Price Analysis:
   - YTD Average Price
   - MTD Average Price
   - YOY Growth in Average Price
   - Difference between YTD Average Price and PTYD Average Price
#### Cars Sold Metrics:
   - YTD Cars Sold
   - MTD Cars Sold
   - YOY Growth in Cars Sold
   - Difference between YTD Cars Sold and PTYD Cars Sold

  
## CHARTS REQUIREMENT

- YTD Sales Weekly Trend.
- YTD Total Sales by Body Style.
- YTD Total Sales by Color.
- YTD Cars Sold by Dealer Region.
- Company-Wise Sales Trend in Grid Form.
- Details Grid Showing All Car Sales Information.




## Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns have empty values.
- Step 5 : The error present in "Engine" column resolves using replace values.
- Step 6 : In the report view, a Calender table created.
- Step 7 : A new one to many relationship made between car data table and calender table in model view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Body_Style", "Dealer_Region", "Transmission" & "Engine".
- Step 9 : Card visuals were added to the canvas according to the KPI requirements.
   Snap of the Card Visuals,
      
![KPI](https://github.com/user-attachments/assets/deb6f146-c8fe-4996-8efb-f0d52a7a88a1)

- Step 10 : An area chart added to understnd the weekly trend of YTD sales.
  
- Step 11 : A Donut chart used to display YTD total sales across different car body styles.

- Step 12 : A Donut chart used to display the contribution of various car colors to the YTD total sales.
  
- Step 13 : A map chart added to visualize the sales distribution geographically by showcasing the YTD sales data based on different dealer regions.
  
- Step 14 :  Provided a tabular grid that displays the sales trend for each company. The grid showcases the company name along with their YTD sales figures.
        
- Step 15 : Created a new details page to create a detailed grid that presents all relevant information for each car sale, including car model, body style, colour, sales amount, dealer region and date.

# Snapshot of Report Overview (Power BI desktop)
![Overview](https://github.com/user-attachments/assets/6a5e3ae0-8f71-456b-bd9b-5971b8d8c564)

           


# Snapshot of Report Details (Power BI desktop)
![Details](https://github.com/user-attachments/assets/2f04af50-ee22-46e8-8f57-7e281bdac9a7)

 
 # Dashboard Snapshot (Power BI Service)
 
![Dashboard 1](https://github.com/user-attachments/assets/cab0f094-fa4d-4fda-8792-9c81cea887c8)
![Dashboard 2](https://github.com/user-attachments/assets/24c4be56-f21b-41b8-a830-b83893d0e982)

 




A dual page report was created on Power BI Desktop & it was then published to Power BI Service.


