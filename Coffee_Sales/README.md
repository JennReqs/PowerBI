## Coffee Sales Dashboard**
Objective:
To create a coffee dashboard from a coffee sales data


### Loading the Data
1. Load the csv file to Microsift Power BI
2. Create the measures needed
     Number of Items Sold = COUNT(Coffe_sales[coffee_name])
3. For the Total Sales, I will used graphs in order to compute it. 
     
| Queries to Answer | Column Name |
|--------------|-------------|
|1. Sales by Coffee Type| Highest Sales by Coffee type|
|2. Sales by the Day of the Week| Determine what day of the week with the highest and lowest sales|
| 3. Sales by Time of the Day| Determine what time of the day with the highest sales(morning, afternoon, night)|
|4. Peak Hours| Hour of the day with the highest and lowest sales |
|5. Sales by Month| Month with the highest and lowest sales |



### Next is to add data to the table.
I used the export wizard window for me to upload data on my table. I’ll just make sure the values is correct like the data types and format especially the date format (yyyy-mm-dd).

### Step 2: Write Analytical SQL Queries


### 1. Customer Insights

_Find the top 10 customers by total spending._

![top10 with highest spend](https://github.com/JennReqs/sql_project/blob/main/sales_analysis/top10customers.PNG)

### 2. Sales Performance

_Calculate total sales revenue per month._

![revenue per month](https://github.com/JennReqs/sql_project/blob/main/sales_analysis/monthlysales.PNG)

### 3. Product Analysis

_Find the most profitable products._

![revenue per month](https://github.com/JennReqs/sql_project/blob/main/sales_analysis/topitemsales.PNG)
