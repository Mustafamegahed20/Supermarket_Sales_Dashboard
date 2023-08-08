# Supermarket_Sales_Dashboard
Analyzing , cleaning , modeling and visualizing SuperMarket sales data Using Power Bi 

## Data 
Data Link : https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

**Invoice id**: Computer generated sales slip invoice identification number

**Branch**: Branch of supercenter (3 branches are available identified by A, B and C).

**City**: Location of supercenters

**Customer type**: Type of customers, recorded by Members for customers using member card and Normal for without member card.

**Gender**: Gender type of customer

**Product line**: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel

**Unit price**: Price of each product in $

**Quantity**: Number of products purchased by customer

**Tax**: 5% tax fee for customer buying

**Total**: Total price including tax

**Date**: Date of purchase (Record available from January 2019 to March 2019)

**Time**: Purchase time (10am to 9pm)

**Payment**: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet)

**COGS**: Cost of goods sold

**Gross margin percentage**: Gross margin percentage

**Gross income**: Gross income

**Rating**: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)

## Project Steps
1.Connect Data From CSV file

2.Cleaning and make some transformation to the Data

3.Create some measures by DAX

7.built interactive dashboard

## Measures Using Dax 
1.Total Sales
```sql
Total Sales= SUM('supermarket_sales'[Total])
```
2.Total Orders
```sql
Total Orders = COUNT(supermarket_sales[Invoice ID])
```
3. Total COGS
```sql
Total COGS = SUM(supermarket_sales[cogs]) 
```
4.Total Quantity
```sql
Total Quantity = SUM(supermarket_sales[Quantity])
```

## Dashboard
![image](https://github.com/Mustafamegahed20/Supermarket_Sales_Dashboard/assets/61358936/3df4590c-7472-47df-bd9e-5ef0c070b49f)


## You Can Check Dashboard at novypro : 
You can give a look to dashboard and can have other insights from it.

https://www.novypro.com/project/super-market-sales-
