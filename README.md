# Interactive-Sales-Dashboard
<h1>Data Preparation</h1>

Before creating pivot tables and properly visualizing the dataset, I needed to add a few columns. Because the CustomerID exists on each order in the Orders worksheet as well as every customer profile in the Customers sheet, I was able to merge the necessary data from each customer (such as CustomerName, CustomerEmail, Country, and LoyaltyCard) to their corresponding order history. This makes it much easier when making the pivot tables and the sliders because they only need to reference one worksheet. To do this, I used lookup functions to reference other ranges throughout the dataset.

Then, I merged the data from the Products sheet onto the Orders sheet. I merged the UnitPrice and CoffeeType columns using 'XLOOKUP'.

---------------------------------------------------------------------------------------------------------------------------


