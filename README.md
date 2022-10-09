# Pizza-Power-BI-data-visualisation

Here I have visualised a pizza sales dataset(s) using Power BI.
My goal was to find insights on the overall campany performance and most importantly the pizzas they were selling. 

Originally the data folder came with 4 data sets:

-Order_details; changed to "Order_details_sales

-orders changed to "order_dates"

-Pizza_types

-Pizzas

I had to make an extra dataset: "Calendar_lookup", which contained a date range from 01/01/2015-31/12/2015. This was done so that I could left join the orders table
to Order_details Table so I could make one big fact table.
This allowed me to add the Calendar_lookup table to my data model so that the data could be filterd by date fields properly. 

With the use of dax and powerbi visualisations, I have created a report that shows you the generl sales perfromance of the company on the executive summary page.
By right clicking any product name on the matrix visualisation on the executive summary, you will be given an option to "drill-through". After clicking on that you 
will be taken the product page where you will see information based on the product you clicked. 


