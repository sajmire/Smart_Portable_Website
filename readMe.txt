Steps to install the application

1. All the ByteCodes are placed in csj/WEB-INF/classes folder. The folder has been provided in the deliverables.
2. Place the csj folder in webapps directory of apache-tomacat-7.0.34
3. Run the env-setup-for-tomcat file to set the environment variables.
4. Start the MySQL database and also start the MySQL WorkBench6.3.
5. Go to C:\Program Files\MongoDB\Server\3.2\bin and run mongod.exe and mongo.exe file to start the MongoDB server.
6. Go to C:\apache-tomcat-7.0.34\bin and run the startup.bat file to run the apache-tomacat-7.0.34.
7. To run the application go to the Mozilla Firefox and start the web browser.
8. In the url tab type localhost/csj/index.html which is the url to the index page of the application.



Main Modules
1. CUSTOMER
2. SALESMAN
3. STORE MANAGER

In customer module One can Sign Up, Login, Browse the products, View the Products, Add them to CART.
He can also remove the items from the cart and then finally he can check out and the order will be stored in the database and he can also view the product.
He can also Cancle the order.
The customer can also read and write reviews about a product and these reviews will be stored in MONGODB.
The customer can also find the TRENDING product in the market in grouped on different cities.


In Salesman module an employee can login and view all the products and he can view , update and delete the orders placed by the user.
in addition to it a salesman can also create accounts for customers.


In StoreManager module one can Add a new Product And Delete a product. 
Also the Bonus feature has been implemented in the StoreManager module Store manager can see the data analytics on the basis of multiple filter conditions entered by the user.



