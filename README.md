Grocery Store Management 🛒

This project is a MySQL database system for managing a grocery store.
It includes the schema, sample queries, and analytical SQL to track sales, products, suppliers, and customers.

📌 Features

Database schema for:

Suppliers

Categories

Employees

Customers

Products

Orders & Order Details

Queries for analysis:

Product counts by category

Average price per category

Top-selling products

Supplier revenue contribution

Monthly & daily sales trends

Top 5 products by revenue in each category

🗂️ Project Structure
/Grocery_Store_Managment
│── Grocery_Store_Managment.sql   # Main SQL file (schema + queries)
│── README.md                     # Project documentation

⚙️ Setup Instructions

Clone the repository:

git clone https://github.com/prash930/Grocery_Store_Managment.git
cd Grocery_Store_Managment


Import the database in MySQL:

mysql -u <username> -p < Grocery_Store_Managment.sql


Or copy/paste the SQL into MySQL Workbench / phpMyAdmin and run it.

🛠️ Tech Stack

Database: MySQL

Language: SQL

🚀 Future Improvements

Switch IDs from TINYINT/SMALLINT → INT for larger datasets

Use DATE / DATETIME instead of VARCHAR for dates

Add indexes on frequently queried columns

Add sample data inserts for quick demo

🤝 Contribution

Contributions are welcome!

Fork this repo

Create a new branch:

git checkout -b feature-name


Commit your changes:

git commit -m "Add new feature"


Push to branch:

git push origin feature-name


Open a Pull Request
