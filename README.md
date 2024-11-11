### Project Overview
This project implements a MySQL database for a music store. The database stores information about customers, employees, products (including albums, tracks, and instruments), purchases, and more.

### Database Structure
The database consists of the following tables:
* **customers**: Stores customer information (ID, name, address, email, phone).
* **employees**: Stores employee information (ID, name, job title, hire date, salary).
* **products**: Stores product information (ID, name, price, description, category).
* **albums**: Stores album information (ID, title, artist, release year, genre, label, price).
* **tracks**: Stores track information (ID, album_id, name, length, price).
* **instruments**: Stores instrument information (ID, name, brand, price, type).
* **orders**: Stores order information (ID, customer_id, order_date, total_amount).
* **order_details**: Stores order details (order_id, product_id, quantity, price).
* **inventories**: Stores inventory information (product_id, quantity_in_stock).
* **payments**: Stores payment information (order_id, payment_method, payment_date, amount).

### Database Schema
ER Diagram

### SQL Scripts
The 'sql' directory contains SQL scripts for:
* Creating database and tables
* Inserting sample data
* Performing various queries and updates

### Usage
1. **Create the database:** Execute the 'create_database.sql' script.
2. **Create tables:** Execute the 'create_tables.sql' script.
3. **Insert sample data:** Execute the 'insert_data.sql' script (optional).
4. **Query and update data:** Use MySQL Workbench or any other SQL client to interact with the database.

### Additional Notes
* **Data Types:** Appropriate data types have been used for each column.
* **Relationships:** Foreign keys and indexes have been created to optimize performance.
* **Normalization:** The database is normalized to reduce redundancy and improve data integrity.
* **Error Handling:** Consider implementing error handling mechanisms for data integrity.


