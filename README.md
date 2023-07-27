# **Project Description**

An internet application for managing a network of pizzerias. The interface and functionality of the application will vary depending on the user's role in the system. The database will store information about system users and data about dishes.

In the current version, to connect to the database, you need to create a new database in the **Microsoft SQL Server Management Studio** environment. Then, create a Query in it using the script provided in the repository: **pizza_restaurant_ver_9_DDL.sql** (located in the resources folder). You can also find an SQL script there to populate the database.

---

## **Roles in the System:**
1. Manager/Owner has:
   - [X] the ability to take phone orders by filling out a form, similar to how a logged-in user does it,
   - [X] the ability to reserve tables (adding, editing, and viewing reservations),
   - [X] the ability to assign loyalty points,
   - [X] the ability to modify pizza prices,
   - [X] the ability to generate a report showing income within a specific time range (income is the difference between the base price, which is set in the program, and the price set by the manager).
2. Unregistered Customer has:
   - [X] the ability to register in the system,
   - [X] the ability to log in to the system,
   - [X] access to the menu,
   - [X] access to information about locations (address/contact),
   - [X] the ability to place an order using a given phone number.
3. Logged-in Customer has:
   - [X] the ability to change the password,
   - [X] the option to log out,
   - [X] access to the menu and the ability to place an order with delivery address selection,
   - [X] access to information related to their profile,
   - [X] the ability to display a report that lists pizza types (sorted in ascending/descending order) according to the amount spent by the Customer in a given time period, as well as the total amount of orders (as a summary).

---

## **Database Schema**
![Database Schema](resources/Relational_ver_9.PNG)