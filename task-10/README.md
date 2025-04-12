# 10. Comprehensive Database Design, Optimization, and Advanced Features

## Objective:

- Design a normalized database schema for a complex business scenario (e.g., an eCommerce platform).
- Implement advanced SQL features to ensure performance, data integrity, and automation.

## Requirements:

### ✅ Schema Design:
- Create multiple related tables including:
  - `Products`
  - `Customers`
  - `Orders`
  - `OrderDetails`
- Apply:
  - Proper **primary and foreign keys**
  - **Unique constraints**
  - Normalization principles

### ⚡ Indexing and Performance:
- Analyze common queries.
- Apply indexing strategies to optimize performance.

### 🔄 Triggers:
- Implement triggers to:
  - Automatically update inventory when an order is placed.
  - Log stock changes to a separate table (`StockLog`).

### 🔐 Transactions:
- Use `START TRANSACTION`, `COMMIT`, and `ROLLBACK` in stored procedures.
- Ensure data consistency during multi-step operations (e.g., order placement).

### 📊 Views (and Optional Materialized Views):
- Create a view (`OrderSummary`) to display total sales per order with customer info.
- Materialized views can be implemented in engines that support them (not MySQL by default).

### 🧪 Documentation and Testing:
- Document:
  - Schema
  - Triggers
  - Views
  - Stored Procedures
- Write and execute test queries to confirm that all components work as expected.

## Reference

See the [commands.txt](./commands.txt) file for:
- Full SQL definitions
- Triggers
- Stored procedure
- View logic
- Sample test queries and outputs
