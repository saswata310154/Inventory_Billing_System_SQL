# DevifyX Inventory & Billing System

## 📌 Project Overview

This project is a comprehensive Inventory and Billing System developed using **MySQL 8.0+**. It manages products, stock, suppliers, customers, purchases, sales, invoices, and analytics. The system automates stock updates via triggers and provides analytical reporting through views.

## 🧱 Core Features Implemented

- ✅ Product, Supplier, Customer Management
- ✅ Purchase & Sales Order Management
- ✅ Stock Movement & Inventory Valuation
- ✅ Invoicing and Payment Tracking
- ✅ Role-Based Access (DB Level)
- ✅ Views for Low Stock, Product Performance, Sales Summary, etc.
- ✅ Triggers for automatic stock updates
- ✅ Audit Logging

## ⚙️ Technologies Used

- MySQL 8.0+
- SQL (DDL, DML, Views, Triggers, Constraints)
- JSON columns for permissions

## 🗂️ File Structure

```
DevifyX_Inventory_System_Final/
├── DDL_Schema.sql
├── DML_Sample_Data.sql
├── QUERIES.txt
├── Sample_Queries.sql
├── README.md
```

## 🧪 How to Run

1. Create the database and use it:
   ```sql
   CREATE DATABASE inventory_billing_system;
   USE inventory_billing_system;
   ```

2. Execute files in order:
   ```sql
   SOURCE DDL_Schema.sql;
   SOURCE DML_Sample_Data.sql;
   SOURCE Sample_Queries.sql;
   ```

3. Verify outputs with: `QUERIES.txt`

## 📊 Key Queries Included

- Low stock alerts
- Current stock levels
- Product expiry tracking
- Sales and purchase summary
- Product performance
- Payment tracking
- Audit logs

## 👨‍💻 Developed By

Saswata Sarkar  
M.Sc. Data Science, Kalyani University,West Bengal,India
