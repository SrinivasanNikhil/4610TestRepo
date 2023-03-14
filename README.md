
# MIST 4610 Group Project 1 - A New Restaurant

A new restaurant, Four-For-Four Dining, has emerged in the city of Athens, Georgia. They have contacted our consulting company, CSCSN Data Co., to develop a data model to track information for the restaurant.

Four-For-Four Dining is a company which has many franchise locations. Each location consists of an address (broken down), a store phone number, and an email for business inquiries. They also have several employees at each location. Employee information includes their name, their position at Four-For-Four, a salary (these are full-time workers!), a phone number, and a personal email. Some employees have positions in which they manage other employees, which should be reflected in the data model.

Keeping track of inventory is of high priority to Four-For-Four. There are many different suppliers who sell inventory to the company. Supplier information includes the name of the supplier, a description of what inventory they sell, and contact information such as phone number and email address. Each Four-For-Four Dining location has a unique inventory that they order, including information like the inventory’s name, the product type, and the last updated date of the inventory’s purchase.

Upon its grand opening, Four-For-Four Dining has attracted many customers to its locations. The restaurant has requested access to a customer’s full name, contact information (phone number and email will do), primary and secondary addresses, city, state, zip code, and country. The company is looking to provide an incentive for customers to return. In order to achieve this, Four-For-Four should look to implement a rewards program. Customers can advance to different tiers in the program, which is determined by meeting a certain rewards points threshold. Each tier provides deals such as a free entree or drink, and the quality of the deals increase as a customer moves up the tiers in the rewards program.

Lastly, the company wants to keep track of information of the orders placed by customers. They would like to know the date and time of when an order was placed and when a payment is made. Crucial payment information includes the type of payment being made and the amount paid. When an order is made, they would like to know the composition of it as well. This can include several menu items as well as the quantity of those menu items ordered. Important menu item information is as simple as its name, description, price, and calorie count. Menu items also may be part of a combo item (a burger, fries, and drink are separate menu items, but may be combined into a combo).

Four-For-Four Dining is counting on CSCSN Data Co. to develop a comprehensive data model that meets their business needs. Draw a data model to accurately represent the information that they would like to collect.

## Data Model

![App Screenshot](https://raw.githubusercontent.com/SrinivasanNikhil/4610TestRepo/main/demo%20dm.png?text=App+Screenshot+Here)

### Data model description

Four-For-Four Dining has many franchises across the United States. The restaurant has suppliers that supply items for many different franchises, and each franchise has different suppliers for different items they need in store. Each restaurant franchise has many orders that take place during business hours, but each order is only processed at the franchise where the order took place. In addition, each restaurant franchise has many employees for different positions (chef, cashier, etc.), but each employee can only work at one franchise.

One employee can manage many other employees, but each employee can only report to one manager. An employee can fill many orders at their franchise, but each order can only be filled by one employee. Four-For-Four Dining customers can have several orders at the restaurant if they have visited more than once. Each order belongs to one customer. Every order at Four-For-Four Dining consists of one form of payment (cash, card, etc.). Customers who join the rewards program will receive many benefits that vary based on their rewards tier. Each customer can only belong to one rewards program, but the rewards program can include many Four-For-Four Dining customers.

Orders at Four-For-Four Dining can take shape in many different ways. The orders at the restaurant can include many menu items, for example, the customer can order multiple cheese
 burgers or a burger and a drink. Similarly, a menu item can take place on many different orders. Lastly, the restaurant includes combo meals as an option for customers, which consist of a variety of menu items. The items on the menu can be used for many different combos shown on the menu.

 
