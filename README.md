Case study
Adventure Works has recently acquired another bicycle business. Adventure Works’ CEO, Jamie Lee, has assigned a task to the sales department to ensure that the sales data from the newly acquired business is reported in the Adventure Works sales reports. Your manager, Adio Quinn, has tasked you with creating a Power BI query that merges the data. 

The company provided the two Excel files containing the Adventure Works sales data, AdventureWorksSales.xlsx and the new company’s data, OtherSales.xlsx. The datasets have some common data such as SalesOrderID, SalesOrderDetailID, UnitPrice and SalesData as well as columns with different names. As you learned in previous videos, in tables that will be combined, the column names that you want to stack vertically should be the same. For columns with matching names, their row values are stacked vertically to merge them, while for columns that exist separately in each set, they will be added horizontally, with null values for tables where those columns were not present before. To complete your task successfully you have to rename the common columns and give them the same names. You also have to remove any unnecessary columns.

This exercise aims to assist you in understanding how to combine data by appending data. By the end of this exercise, you’ll understand how to append data in Power Query, add rows together and consolidate data.

Instructions
Create a new Power BI project called Exercise – Appending a dataset. Follow the prompts below to complete the exercise.

Step 1: Download the Excel files
Download the AdventureWorksSales.xlsx and OtherSales.xlsx files, which you will use in this exercise.

Content of AdventureWorksSales.xlsx

Content of OtherSales.xlsx
Step 2: Open the Power Query Editor
Open the Power Query editor and import your datasets, AdventureWorksSales and OtherSales.

Step 3: Format Excel files
You have to append OtherSales data to AdventureWorksSales data. So, you will use AdventureWorksSales data as the first table and OtherSales data as second table. 

For this reason, format the OtherSales data and rename the column names, using the AdventureWorksSales data, for example, Quantity to OrderQty, Name to ProductName, and Total to LineTotal.

Step 4: Append queries
Append queries in a new master table. In the newly created query, check the column names, row number and the values appended. Make sure that the operation has been completed successfully.

Append dialog. Two tables selected. AdventureWorksSales as first and OtherSales as second.
Step 5: Rename new query
In the left menu, select the new query and change its name to Consolidated Sales and select Enter on the right pane, named Properties.

Conclusion
You have now successfully combined your datasets using Power Query. The data sets are now consolidated in one file, ready for further analysis in Power BI Desktop.
