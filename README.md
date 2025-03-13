# Customer-segmentation-using-RFM-

## Data Description:
The data consists of **541909** rows x **8** columns, totaling in **33.1+ MB** approximately.
**The Goal** based on our features we have to categorize the customers.
* 	InvoiceNo
* 	StockCode
* 	Description
* 	Quantity
* 	InvoiceDate
* 	UnitPrice
* 	CustomerID
* 	Country

## Data preprocessing:
* Transforn the **InvoiceDate** column from objest to date.
* Excluded Negative Values in Quantity and UnitPrice.
* Dropped all the Duplicated Values.
* Droped all the missing values in **CustomerID** column.
* Creating **Total Price** Column, whihc is the result of multipling the quanitity and the item price.


  ## RFM Ananlsis:
 We are going to perform following opertaions:

* For **Recency**, Calculate the number of days between present date and date of last purchase each customer, **InvoiceDate**.
* For **Frequency**, Calculate the number of orders for each customer, **InvoiceNo**.
* For **Monetary**, Calculate sum of purchase price for each customer, **Total_Price**.

Then ordered the values from **1** to **5**.
Then combing them all, in the RFM score.

Also I created a segments for the customers:
* Promising.
* About to Sleep.
* Hibernating.
* Need Attention.
* Potential Loyalists.
* At Risk.
* Can't Loose.
* Loyal Customers.
* New Customers.
* Champions.










