This is a website created by the .NET Core framework. 
The original intention of this website is to provide online food ordering services, record customer orders and facilitate merchants’ delivery services.

v1.0 - Create the basic food order website

Establish the basic Field for our MVC framework(Model).

For the data stored part, I chose MySQL as the database. Two types of data will be recorded in our database: 
1. Customers' information including customer's name(First name and last name are stored in different fields) and address.
2.Order information. It will be the information about what kind of food and beverage our customers have ordered, what's the quantity, price, Customer's ID and food order ID.

The customer ID will be the foreign key for the order table.

v2.0 - Create the Views and Controllers

Use scaffolding tools to generate views and Controllers.

In order to further enhance the user experience, some Views have been optimized.

v3.0 - Add validation process

Add roles in Modle and set the permissions of each role. 
If the user is not logged in, he can only browse the food and drink menu. 
If the customer logged in, he can see user information and order information.

v4.0 - Improve the role assignment mechanism（Future directions for improvement）

Separate the level of registered users. 

Ordinary customers, store owners, and administrators should have different permissions and operation interfaces. 
For example, ordinary customers can only browse their customer information and historical orders. 
The store owners can see the historical orders of all their customers. 
The administrator has all permissions.
