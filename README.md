

# Grocery Store Management 🛒

This project is a **MySQL database system** for managing a grocery store.
It includes the schema, sample queries, and analytical SQL to track sales, products, suppliers, and customers.

---

## 📌 Features

* **Database schema** for:

  * Suppliers
  * Categories
  * Employees
  * Customers
  * Products
  * Orders & Order Details
* **Queries for analysis**:

  * Product counts by category
  * Average price per category
  * Top-selling products
  * Supplier revenue contribution
  * Monthly & daily sales trends
  * Top 5 products by revenue in each category

---

## 🗂️ Project Structure

```
/Grocery_Store_Managment
│── Grocery_Store_Managment.sql   # Main SQL file (schema + queries)
│── README.md                     # Project documentation
```

---

## ⚙️ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/prash930/Grocery_Store_Managment.git
   cd Grocery_Store_Managment
   ```

2. Import the database in MySQL:

   ```bash
   mysql -u <username> -p < Grocery_Store_Managment.sql
   ```

3. Or copy/paste the SQL into **MySQL Workbench / phpMyAdmin** and run it.

---

## 🛠️ Tech Stack

* **Database**: MySQL
* **Language**: SQL

---

## 🚀 Future Improvements

* Switch IDs from `TINYINT/SMALLINT` → `INT` for larger datasets
* Use `DATE` / `DATETIME` instead of `VARCHAR` for dates
* Add indexes on frequently queried columns
* Add sample data inserts for quick demo

---

## 🤝 Contribution

Contributions are welcome!

1. Fork this repo
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add new feature"
   ```
4. Push to branch:

   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request 🎉

---


Do you also want me to **clean your SQL file** a bit (fix datatypes, naming, add indexes) and give you the updated version so you can push both together?
