# DBMS-PROJECT

# Online Bookstore Management System

## Developed by: Yuvraj Srivastava
## UID: 21bca1210

### Objective:
A mini-project that simulates a real-world Online Bookstore, managing products, customer orders, and tracking sales.

### Schema Overview:
- Customers (CustomerID, Name, Email, Phone)
- Products (ProductID, Name, Description, Price, Stock)
- Orders (OrderID, CustomerID, OrderDate)
- OrderItems (OrderItemID, OrderID, ProductID, Quantity)

### SQL Features Implemented:
- Table creation with constraints
- Insert, update, delete operations
- Joins and aggregation queries
- Relationship mapping (1-to-many, many-to-1)

### Files Included:
- `schema.sql` – Contains SQL commands to create and populate the database
- `queries.sql` – Contains sample queries and expected results
- `ER_Diagram.png` – Visual representation of the entity relationships
- `README.md` – Project documentation

### How to Run:
1. Open MySQL or any SQL-compatible database engine.
2. Run the SQL script in `schema.sql`.
3. Run the queries from `queries.sql` to test functionalities.

