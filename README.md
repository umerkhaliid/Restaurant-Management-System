# Restaurant-Management-System

**Overview**
This is a Restaurant Management System developed using PostgreSQL for the database and Python for the backend. 
The system includes features for table management, customer management, and order management.
The project is designed to help manage reservations, orders, and customer data efficiently.

**Features**
Admin Role:
**Manage the database.**
Handle tables for reservations according to the number of people.
Manage orders divided into dining and delivery categories.
**Table Management**
Add, remove, and update table details.
Categorize tables by seating capacity.
**Customer Management**
Register new customers.
Update customer information.
Track customers by their reservations and orders.
**Order Management**
Add and remove orders.
Update order statuses.
Divide orders by dining and delivery categories.

**Prerequisites**
PostgreSQL
Python 3.x
psycopg2 (Python library for PostgreSQL)

**Configuration**
Update the 'config.py' file with your database configuration:
DB_NAME = 'your_db_name'
DB_USER = 'your_db_user'
DB_PASSWORD = 'your_db_password'
DB_HOST = 'your_db_host'
DB_PORT = 'your_db_port'

**Database Schema**
**Tables**
Tables: Stores details about restaurant tables.
Customers: Stores customer information.
Orders: Stores order details divided by dining and delivery.

**Contact**
For any questions or suggestions, please contact umerkh00@gmail.com
