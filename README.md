
# Pizza-Sales Analysis

### Dashboard Link : https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

## Problem Statement

This dashboard helps Pizza company to analyze their best and worst selling produts and make informed decisions . It helps the company what type of pizzas are ordered more by customers on daily and weekly basis. Through different trend analysis, they get to know their improvement area, & thus they can improve their services, profit and revenue by identifying which category to make more on what day they are having most orders. It also lets them know the average orders in different weekdays, thus since by using this dashboard they have identified this problem, they can further work on factors that are helpful in increasing revenue and growth.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present .
- Step 5 : For calculating daily and monthly trend of orders, 'day' and 'month' column were added
- Step 6 : multiple card visual was selected to represent the most imporrtant figures like :-
  
1. total revenue
   
  ![total revenue](https://github.com/rahulmaurya255/Pizza_sales_analysis_bi/assets/155320538/1895c124-2f85-48de-9781-7250741eadee) 

2. average order value 

  ![avg odr value](https://github.com/rahulmaurya255/Pizza_sales_analysis_bi/assets/155320538/eacae67c-6d7c-4cfc-8679-aa2eca2e8c8b)

3. average pizza per order

  ![avg p odr](https://github.com/rahulmaurya255/Pizza_sales_analysis_bi/assets/155320538/bdd18b0a-e3a9-465a-af7a-051c5919d4e9)

4. total orders

  ![total orders](https://github.com/rahulmaurya255/Pizza_sales_analysis_bi/assets/155320538/e8008fd1-eb15-4afb-bb44-ce167d78c89b)

5. total pizza sold

  ![total p sold](https://github.com/rahulmaurya255/Pizza_sales_analysis_bi/assets/155320538/76b80fd2-6220-4f7a-81c6-e2fc3476d77e)


- Step 7 : stacked column chart was selected to visualize trend of orders on weekdays

- Step 8 : area chart was added for monthly trend of no. of orders

- Step 9 : Funnel and donut visuals were used to analyze percentage sales of total and total number of pizzas by category

  ![by category](https://github.com/rahulmaurya255/Pizza_sales_analysis_bi/assets/155320538/4b175d2a-31a2-40e0-be1b-0e9aa924d9c5)


  ![top 5 by revenue](https://github.com/rahulmaurya255/Pizza_sales_analysis_bi/assets/155320538/0abc4214-80f3-4497-aa0e-899148916376)

        
 
 # Report Snapshot (Power BI DESKTOP (1))

 ![dash 1](https://github.com/rahulmaurya255/Pizza_sales_analysis_bi/assets/155320538/5d52bd4f-1e5e-45f5-bea1-a1a50a0136e6)

# Report Snapshot (Power BI DESKTOP(2))

 ![dash 2](https://github.com/rahulmaurya255/Pizza_sales_analysis_bi/assets/155320538/f236e92a-018a-40aa-ad5d-41aab18cafcb)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Busiest Days and Time

   DAYS

Orders are highest on weekends Friday/Saturday evenings



MONTH

There are Maximum orders frommonth of July and January


           
### [2] Sales Performance
CATEGORY

Classic Category contributes to maximum  sales and total orders

SIZE

Large Pizza  Contributes to Maximum sales. 




 
 ### [3] Best Sellers
 REVENUE

The Thai Chicken pizza contributes to maximum revenue


QUANTITY

The Classic Deluxe pizza contributes maximum quantity


TOTAL ORDERS

The Classic Deluxe pizza contributes maximum orders
 
          Classic Deluxde pizza contributes to both maximum quantity an orders
         
### [4] Worst Sellers

REVENUE

The Brie Carrie pizza contributes to minimum revenue

QUANTITY

The Brie Carrie pizza contributes to minimum quantity


TOTAL ORDERS

The Brie Carrie pizza contributes to minimum orders
       
       The brie Carrie pizza is worst in revenue, quantity and orders
