# MyMart

Creating a Django+Python project for storing user entered customer data through created HTML files into csv files.

Concept:
To create an ordering system through HTML, Python, and Django that allows users to order anything they want (linked with another HTML file that stores list of items available for order) and then stores the order details accordingly into a CSV file.

In summary, the program does the following:

HTML:
- Creating HTML file for list of items
- Creating HTML file for orders

Django project:
- starting the project within the Command Prompt and creating two apps: list & order
- creating a "templates" folder to store HTML files
- creating view function for list of items and order under views.py for the two apps respectively
- modifying urls.py accordingly
- CSV file is created accordingly as data gets stored from the orders' HTML file
