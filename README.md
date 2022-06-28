# Heureka_Scraping

What does it do:
Importing the html code from Heureka for one type of products (for example paddleboards) for further work. Picking out information about the product title, stores which it is selled, price of a product and delivery price. At the end export to csv file.

Description:

1. Requesting the html code based on the url, could be changed for any other url.
2. Identifiing the product title based on h3 tag.
3. Accessing the detail of each product based on the href tag in the html code and requesting the content again.
4. From the detail of the product identifiing the stores of selling, links of the store, the related prices and the delivery price.
5. With all the obtained data creating an offer (date, title, shop, link of the shop, price, delivery price).
6. Cleaning the data from None value of delivery and transferring the amounts into the int data type.
7. Creating a data frame from these data. 
8. Export to csv file


