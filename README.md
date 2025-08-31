# ASPNET-Week-2

Using the week 1 example, I added a button on the product page called "Duplicate" that takes the selected product and duplicates all information except the Primary Key "ID" to avoid conflicts. 

Added interface "IDuplicate" that has a method "DuplicateProduct" that uses the Products datatype and passes the id as a parameter to the Duplicate Service.

Added a service "DuplicateService" that inherits the IDuplicate interface. It takes in an instance of MVcProductContext allowing the service to interact with the database.

Added class/service "DuplicateService"





Added scoped Iduplicate and DuplicateService to the builder
