# power_bi_project

## Milestone One Importing via Azure SQL database.
Importing via Azure SQL database
I connected to the Azure SQL database order_db within PowerBI and I was in turn able to obtain the orders_powerbi table.

Once I was connected to the table, I deleted the Card Number column in order to avoid personal information being seen by the wrong parties and then separated Order Date and Shipping Date into Order Date and Order Time and Shipping Date and Shipping Time to separate out the date and time data types. This will allow me to analyse these columns independantly in the future, making the overall table more usefull to generate insights. All of these changes by transforming the data with Power Query.

As I found that there were Null values contained within the Order Date table and knowing this could potentially cause me problems later, I removed all rows containing Nulls as their Order Date.
There were some coloumns that did not conform to Power BI naming conversions (multiple special characters, vauge naming, varying upper case and lower case names) and so were renamed. 

Importing csv file -

Importing blob file - 

Importing from zip file - 
