# Interactive-Sales-Dashboard
<h1>Data Preparation</h1>

Before creating pivot tables and properly visualizing the dataset, I needed to add a few columns. Because the CustomerID exists on each order in the Orders worksheet as well as every customer profile in the Customers sheet, I was able to merge the necessary data from each customer (such as CustomerName, CustomerEmail, Country, and LoyaltyCard) to their corresponding order history. This makes it much easier when making the pivot tables and the sliders because they only need to reference one worksheet. To do this, I used lookup functions to reference other ranges throughout the dataset.

Then, I merged the data from the Products sheet onto the Orders sheet. I merged the UnitPrice and CoffeeType columns using 'XLOOKUP'.

The first image below is the dataset before I made these changes, and the second image shows the changes made to merge all necessary columns onto the Orders sheet.

---------------------------------------------------------------------------------------------------------------------------

<img width="1112" alt="coffeesales1" src="https://github.com/idcruz99/Interactive-Sales-Dashboard/assets/160052201/ffc0f160-618e-45de-b6b1-73d07762835b">

---------------------------------------------------------------------------------------------------------------------------

<img width="1112" alt="coffeesales2" src="https://github.com/idcruz99/Interactive-Sales-Dashboard/assets/160052201/93d6d2eb-023d-4ed0-bcb2-8296a8a3a4ad">

---------------------------------------------------------------------------------------------------------------------------

<img width="1112" alt="coffeesales3" src="https://github.com/idcruz99/Interactive-Sales-Dashboard/assets/160052201/36b83a9c-c40c-49ad-963e-49a3f81727e7">

---------------------------------------------------------------------------------------------------------------------------

<h1>Creating Visuals</h1>

After all of the data that I needed to create the visuals was on one page, I was ready to create the pivot tables, timeline, and slicers. 
