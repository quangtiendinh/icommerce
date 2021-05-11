# The iCommerce application

A small start-up named "iCommerce" wants to build a very simple online shopping
application to sell their products. In order to get to the market quickly, they just want to
build an MVP version with a very limited set of functionalities:

1. The application is simply a simple web page that shows all products on which
   customers can filter, sort, and search for products based on different criteria such as
   name, price, brand, color, ...
2. All product prices are subject to change at any time and the company wants to keep
   track of it.
3. A product always shows the latest price when showing on the website
4. If the customer finds a product that they like, they can add it to their shopping cart
   and proceed to place an order.
5. For audit support, all customers' activities such as searching, filtering, and viewing
   product details need to be stored in the database.
   However, failure to store customer activity is completely transparent to customers
   and should have no impact on the activity itself.
6. Customers can log in simply by clicking the button “Login with Facebook”. No further
   account registration is required.
7. No online payment is supported yet. The customer is required to pay by cash when
   the product got delivered.
