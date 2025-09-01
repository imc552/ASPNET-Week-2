# ASPNET-Week-2

Using the week 1 example, I added a button on the product page called "Duplicate" that takes the selected product and duplicates all information except the Primary Key "ID" to avoid conflicts. 

Added interface "IDuplicate" that has a method "DuplicateProduct" that uses the Products datatype and passes the id as a parameter to the Duplicate Service.

Added a service "DuplicateService" that inherits the IDuplicate interface. It takes in an instance of MvcProductContext allowing the service to interact with the database. The DuplicateProduct method takes the original product and creates a new instance of the object with the same values. It then adds the duplicate product back to the database and saves. 

Added scoped Iduplicate and DuplicateService to the builder


Copilot: Used for explaining how to find a databse entry with an ID and how to edit and add it back to the database.
