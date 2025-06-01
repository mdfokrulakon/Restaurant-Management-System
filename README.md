# 🍽️ Restaurant Management System Database (Oracle SQL)

This repository contains a complete Oracle SQL schema for a restaurant and food delivery management system. It is designed to support various operations, including order processing, employee management, notifications, returns, discounts, and payment tracking.

## 📦 Features

- **User Management**: Admin and regular user accounts.
- **Restaurant & Branches**: Separate handling of multiple branch types and their locations.
- **Menu & Products**: Organized menu with product-offer linkage.
- **Customer Handling**: Support for customer data and notifications.
- **Order & Delivery System**: Tracks orders, order items, delivery personnel, and payment status.
- **Discounts & Offers**: Flexible discount and promotional offer structures.
- **Notifications System**: Includes customer notifications with read tracking.

## 🛠️ Technologies Used

- Oracle SQL
- PL/SQL Compatibility
- Relational Database Design with Constraints and Keys

## 📁 File Structure

- `DROP_TABLES.sql`: Drops all tables in dependency order with `CASCADE CONSTRAINTS`.
- `CREATE_TABLES.sql`: Creates all necessary tables with proper keys and constraints.
- `INSERT_USERS.sql`: Inserts default users into the `USERS` table.

## ✅ Setup Instructions

1. Ensure you are connected to an Oracle SQL database environment.
2. Run the `DROP_TABLES.sql` script to clear previous instances.
3. Run the `CREATE_TABLES.sql` script to recreate the schema.
4. (Optional) Populate with test data using `INSERT_USERS.sql`.

## 📌 Note

- Referential integrity is strictly enforced using `FOREIGN KEY` constraints.
- Use `CASCADE CONSTRAINTS` when dropping tables to avoid dependency errors.
- All data types and field sizes are chosen for flexibility and normalization.


