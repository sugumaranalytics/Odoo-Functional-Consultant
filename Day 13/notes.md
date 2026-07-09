# Day 13 – Odoo Purchase, Inventory & Sales Workflow (Complete Stock Flow)

**Course:** Odoo Functional Consultant (60 Days)  
**Day:** 13  
**Topic:** Purchase → Inventory → Sales → Delivery Workflow  
**Author:** Sugumar Ranganathan  
**Email:** contact.sugumarai@gmail.com

---

# Objective

Learn the complete inventory cycle in Odoo by purchasing products, receiving stock, creating a sales order, delivering products, and verifying inventory movement.

---

# Topics Covered

- Product Creation
- Track Inventory
- Vendor Configuration
- Purchase Order
- Receive Products
- Inventory Stock Update
- Sales Order
- Delivery Order
- Stock Validation
- Inventory Reduction
- Smart Buttons

---

# Business Flow

```text
Vendor
   │
   ▼
Request for Quotation (RFQ)
   │
   ▼
Purchase Order
   │
   ▼
Receive Products
   │
   ▼
Warehouse Stock
   │
   ▼
Sales Quotation
   │
   ▼
Sales Order
   │
   ▼
Delivery Order
   │
   ▼
Validate Delivery
   │
   ▼
Customer
```

---

# Step 1 – Create Product

Navigation

Inventory → Products → New

Product Details

- Product Name : Monitor
- Product Type : Goods
- Track Inventory : Enabled
- Sales : Enabled
- Purchase : Enabled
- Sales Price : ₹15,000
- Cost : ₹12,000 (Example)

---

# Step 2 – Configure Vendor

Purchase Tab

Vendor

- Kumar Industries

Vendor Price

- ₹12,000

Minimum Quantity

- 1

---

# Step 3 – Create Purchase Order

Navigation

Purchase → Orders → Requests for Quotation

Vendor

- Kumar Industries

Product

- Monitor

Quantity

- 10

Unit Price

- ₹12,000

Actions

- Save
- Confirm Order

Result

Purchase Order Created

---

# Step 4 – Receive Products

Click

Receive Products

Verify

Product : Monitor

Demand : 10

Quantity : 10

Click

Validate

Status

Done

---

# Step 5 – Verify Inventory

Navigation

Inventory → Products → Monitor

Stock

On Hand = 10

Forecasted = 10

Purchased = 10

Inventory successfully updated.

---

# Step 6 – Create Sales Order

Navigation

Sales → Orders → Quotations

Customer

Anitha Cottons

Product

Monitor

Quantity

1

Click

Confirm

Result

Sales Order Created

---

# Step 7 – Delivery Order

Click

Delivery (Smart Button)

Delivery Order

WH/OUT/00001

Verify

Product

Monitor

Demand

1

Quantity

1

Click

Validate

Status

Done

---

# Step 8 – Verify Inventory After Delivery

Navigation

Inventory → Products → Monitor

Before Delivery

On Hand = 10

After Delivery

On Hand = 9

Forecasted = 9

Purchased = 10

Sold = 1

Inventory reduced successfully.

---

# Inventory Flow

```text
Purchase 10
      │
      ▼
Warehouse Stock = 10
      │
      ▼
Sales Order = 1
      │
      ▼
Delivery
      │
      ▼
Warehouse Stock = 9
```

---

# Smart Buttons Explained

## On Hand

Current physical stock available.

Example

9 Units

---

## Forecasted

Expected stock after incoming and outgoing operations.

Example

9 Units

---

## Purchased

Total quantity purchased.

Example

10 Units

---

## Sold

Total quantity delivered to customers.

Example

1 Unit

---

## Incoming

Products expected to enter inventory.

---

## Outgoing

Products reserved or scheduled for delivery.

---

# Problems Faced Today

## Problem 1

Inventory was not reduced after sales.

Reason

Track Inventory was disabled for the first product.

Solution

Created a new product with Track Inventory enabled before transactions.

---

## Problem 2

Error

"No rule has been found to replenish Monitor."

Reason

Route configuration issue.

Solution

Verified

- Warehouse Configuration
- Routes
- Operation Types
- Delivery Rules

Created a new Sales Order after correcting the configuration.

---

## Problem 3

Delivery Button Missing

Reason

Old product was not inventory-tracked.

Solution

Created a new inventory-tracked product.

---

# Key Learnings

Always enable Track Inventory before using a product.

Purchase Orders only increase stock after Receipt is validated.

Sales Orders do not reduce inventory.

Inventory decreases only after Delivery Order is validated.

Warehouse routes determine stock movement.

Delivery Orders are generated automatically for inventory-tracked products.

---

# Important Navigation

Create Product

Inventory → Products

Purchase

Purchase → Requests for Quotation

Receipt

Purchase → Receive Products

Sales

Sales → Quotations

Delivery

Sales Order → Delivery

Inventory

Inventory → Products

---

# Interview Questions

### 1. When does inventory increase?

After validating the Purchase Receipt.

---

### 2. When does inventory decrease?

After validating the Delivery Order.

---

### 3. Difference between On Hand and Forecasted?

On Hand

Current physical stock.

Forecasted

Expected future stock considering incoming and outgoing moves.

---

### 4. Why was Delivery not created for the first product?

Because Track Inventory was disabled.

---

### 5. Why is Validate important?

Without validation, stock movement is not completed.

---

# Real-Time Example

A computer shop purchases

10 Monitors

Inventory becomes

10

Customer purchases

1 Monitor

Delivery is validated.

Inventory becomes

9

This is exactly how businesses manage warehouse stock in Odoo.

---

# Summary

Today I completed the complete Purchase → Inventory → Sales workflow in Odoo.

I learned how to:

- Create inventory products
- Configure vendors
- Create Purchase Orders
- Receive products
- Update inventory
- Create Sales Orders
- Validate Delivery Orders
- Reduce warehouse stock
- Understand inventory movement

This is one of the most important workflows for an Odoo Functional Consultant.

---

# Day 13 Completed Successfully

✅ Product Creation

✅ Purchase Order

✅ Vendor Configuration

✅ Receive Products

✅ Inventory Tracking

✅ Sales Order

✅ Delivery Order

✅ Stock Reduction

✅ Smart Buttons

✅ End-to-End Inventory Workflow

---

**Prepared by:** Sugumar Ranganathan  
**Email:** contact.sugumarai@gmail.com
