# EXPLORATION OF THE AVAILABLE DATA (SALES DATA) 

First to do is to clean ensure the data clean for effective analysis 
and to do that is to remove the duplicate features
- Select the data range (including headers).
- Go to "Data" tab.
-  Click "Remove Duplicates" (in "Data Tools" group).
-  Choose "Select All" or specific columns.
- Click "OK" .  After cleaning,i created another column, ![average sales](https://github.com/user-attachments/assets/d4d1a23d-b814-4c63-a5a9-5c781fa86ef2)

name total sales,insert a formula that multiply the quantity by unit price. 
and its replicated all through data is formatted as table.[sales data.csv](https://github.com/user-attachments/files/17629480/sales.data.csv)
------------------------------------------------
## TO GET THE TOP SELLING 
 	
Sales revenue : total sales = price * quantity.

![TOP SELLING](https://github.com/user-attachments/assets/23f24b68-c133-4f77-a9fc-cc9f1af27d42)

-------------------------------------------------------------

## TO GET REGIONAL PERFORMANCE 

regional sales revenue : total sales within a region

![REGIONAL PERFORMANCE](https://github.com/user-attachments/assets/8aa38b18-01e5-4d91-a963-a5457663dede)

------------------------------------------------------------
## TO GET MONTHLY TREND 

TMS = sum (Daily sales ) within a month ( sum of sales for month)

![TOP SALES TREND](https://github.com/user-attachments/assets/864a1d23-3156-4506-b956-8484289edc8f)


------------------------------------------------------------------
## TO GET TOTAL SALES BY PRODUCT

- Total sales by products = quantity sold * price per unit

![TOP SELLING](https://github.com/user-attachments/assets/f50c755c-22ad-4afa-b51b-789525c27ef6)
---------------------------------------------------------

## TO GET TOTAL SALES BY REGION

 Total sales by region = ( sales revenue for each region )

![TOTAL SALES BY REGION](https://github.com/user-attachments/assets/78d6e7f8-09b9-4916-b99a-de104c2257b2)

------------------------------------------------------
## TO GET TOTAL SALES BY MONTH 

Total sales by month ( Daily sales for each month) 

![TOP SALES BY MONTH](https://github.com/user-attachments/assets/32aecfdb-785b-4ccb-aec3-9c0d06907535)

-------------------------------------------------------------------
# TO CALCULATE METRICS SUCH AS AVERAGE SALES PER PRODUCT 

Average sales per product = total sales revenue / number of total sold 
=averageif ( products, 'Hat', total sales) and with the remainimg products. 

![average sales](https://github.com/user-attachments/assets/984a6997-6cbd-40cf-9d9f-679c211b4947)

----------------------------------------------------------------------------
# TO CALCULATE TOTAL REVENUE BY REGION 

total revenue by region = number of sales transactions * average sale price for each region 

![total revenue](https://github.com/user-attachments/assets/3cdaa702-b69b-4386-8a29-18c4b605a8d3)

