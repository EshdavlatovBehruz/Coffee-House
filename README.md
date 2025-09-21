# ☕ Coffee House Sales Analysis — Power BI Dashboard

## Project Overview
This project analyzes **coffee house sales data** using Power BI.  
The interactive dashboard provides insights into **sales performance, customer transactions, and product demand patterns** across different time periods.

## Key Insights
- **Total Sales**: 112.25K  
- **Total Transactions**: 4K  
- **Average Transaction Value**: 31.65  
- **Top-selling products**: Latte, Americano, Cappuccino  
- **Peak sales times**: Morning & Afternoon 
- **Weekday trend**: Strongest sales on Tuesday, steady performance mid-week  
- **Monthly trend**: Sales fluctuate with clear seasonal peaks  
- **Hourly trend**: Customer activity peaks around morning and afternoon hours  

- ## DAX Measures**:
  - Total Sales = SUM(Coffee_sales[money])
  - Total Transactions = COUNTROWS(Coffee_sales)
  - Average Transaction = DIVIDE([Total Sales], [Total Transactions], 0)
    
- **Visualization**:
  - KPI Cards (Sales, Transactions, Avg. Value)  
  - Bar & Line charts (Products, Time of Day, Weekday, Month, Hour)  
  - Interactive slicers (Month selection)  

## 🚀 Tools Used
- Power BI Desktop  
- Power Query (ETL)  
- DAX (Data Analysis Expressions)  
