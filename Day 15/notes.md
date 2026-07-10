# Day 15 – Inventory Basics (Odoo Functional Consultant)

**Course:** Odoo Functional Consultant (30 Days)  
**Day:** 15  
**Module:** Inventory  
**Topic:** Inventory Basics – Warehouse, Locations & Purchase Receipt  
**Status:** ✅ Completed

---

# Learning Objectives

By the end of Day 15, I learned:

- Inventory Management basics
- Warehouse configuration
- Warehouse Locations
- Operation Types
- Product Types
- Track Inventory
- Purchase Order
- Goods Receipt
- On Hand Quantity
- Forecasted Quantity
- Bill Matching (Introduction)

---

# What is Inventory?

Inventory is the process of managing products inside a company.

Inventory includes:

- Receiving products
- Storing products
- Moving products
- Delivering products
- Counting products

Example

Warehouse

- Laptop
- Mouse
- Keyboard
- Monitor

---

# Why Inventory Management?

Without Inventory

- Wrong stock count
- Missing products
- Delivery delays
- Manual tracking

With Odoo Inventory

- Real-time stock
- Automatic stock updates
- Warehouse management
- Product traceability
- Inventory reports

---

# Inventory Module

Navigation

Inventory

Modules available

- Overview
- Operations
- Products
- Reporting
- Configuration

---

# Warehouse

A Warehouse is a physical place where products are stored.

Example

ABC Technologies Warehouse

Short Name

WH

Warehouse Flow

Vendor

↓

Warehouse

↓

Customer

---

# Warehouse Configuration

Warehouse Name

ABC Technologies

Short Name

WH

Incoming Shipments

Receive and Store (1 Step)

Outgoing Shipments

Deliver (1 Step)

Buy to Resupply

Enabled

---

# Warehouse Locations

Locations divide a warehouse into storage areas.

Default Locations

- WH/Input
- WH/Stock
- WH/Output
- WH/Quality Control
- WH/Packing Zone

Partner Locations

- Vendors
- Customers

Virtual Locations

- Inventory Loss
- Scrap

---

# Location Types

## WH/Input

Incoming products from vendors.

Example

Vendor

↓

WH/Input

---

## WH/Stock

Main storage location.

Products are available here after receipt.

---

## WH/Output

Products waiting for delivery.

---

## Vendors

Supplier location.

---

## Customers

Customer location.

---

## Scrap

Damaged products.

---

## Inventory Loss

Used during stock adjustment.

---

# Replenish Location

Replenish Location means a location that Odoo can automatically refill when stock becomes low.

Example

Warehouse

↓

Shelf

↓

Customer

When the shelf becomes empty, Odoo replenishes stock from the warehouse.

---

# Operation Types

Navigation

Inventory

↓

Configuration

↓

Operation Types

Available Operations

- Receipts
- Delivery Orders
- Internal Transfers
- Pick
- Pack
- Storage
- Cross Dock

---

# Receipts

Receipt means receiving products from a vendor.

Flow

Vendor

↓

WH/Stock

Important Fields

Source Location

Partners/Vendors

Destination Location

WH/Stock

Sequence Prefix

IN

---

# Product Types

Goods

Physical products.

Examples

- Mouse
- Laptop
- Keyboard

Service

Examples

- Installation
- Consulting

Combo

Bundle of multiple products.

---

# Track Inventory

Track Inventory tells Odoo to maintain stock quantities.

If enabled

- On Hand Quantity
- Forecasted Quantity
- Stock Moves

If disabled

No stock tracking.

Important

Inventory tracking cannot be changed after a product has been used in transactions.

---

# Product Created

Product Name

Wireless Mouse

Configuration

- Product Type = Goods
- Track Inventory = Enabled
- Sales = Enabled
- Purchase = Enabled
- Sales Price = ₹450
- Cost = ₹350

---

# Purchase Workflow

Step 1

Create Product

↓

Step 2

Create Vendor

↓

Step 3

Create Request for Quotation (RFQ)

↓

Step 4

Confirm Purchase Order

↓

Step 5

Receive Products

↓

Step 6

Validate Receipt

↓

Warehouse Stock Updated

---

# Purchase Order

Purchase Order Number

P00008

Vendor

Kumar Industries

Product

Wireless Mouse

Quantity

100

Unit Price

₹350

Total

₹35,000

---

# Receipt

Receipt records incoming products.

Flow

Vendor

↓

Receipt

↓

WH/Stock

After Validation

Warehouse stock increases.

---

# Inventory Quantities

## On Hand Quantity

Actual physical stock available.

Example

Wireless Mouse

100 Units

---

## Forecasted Quantity

Expected stock after considering incoming and outgoing operations.

Example

100 Ordered

-20 Delivery

Forecasted

80

---

# Bill Matching

Bill Matching compares:

1. Purchase Order
2. Goods Receipt
3. Vendor Bill

Purpose

Ensure that:

- Ordered quantity is correct
- Received quantity is correct
- Vendor invoice is correct

This is called **3-Way Matching**.

---

# Practical Completed

✔ Inventory Dashboard

✔ Warehouse Configuration

✔ Warehouse Locations

✔ Operation Types

✔ Product Creation

✔ Track Inventory

✔ Purchase Order

✔ Receipt Validation

✔ Stock Updated

---

# Real Business Flow

Vendor

↓

Purchase Order

↓

Receipt

↓

Warehouse

↓

Inventory Updated

↓

Sales Order

↓

Delivery

↓

Customer

---

# Interview Questions

## 1. What is Inventory?

Inventory is the process of managing products, stock movements, and warehouse operations.

---

## 2. What is a Warehouse?

A warehouse is a physical location where products are stored.

---

## 3. What is On Hand Quantity?

The actual quantity physically available in the warehouse.

---

## 4. What is Forecasted Quantity?

Expected stock after considering incoming and outgoing operations.

---

## 5. What is a Receipt?

A receipt records incoming products from vendors into the warehouse.

---

## 6. What is Bill Matching?

Bill Matching verifies that the Purchase Order, Receipt, and Vendor Bill match before payment.

---

## 7. What is Track Inventory?

Track Inventory enables Odoo to maintain stock quantities and inventory movements for a product.

---

# Key Terms

- Inventory
- Warehouse
- Location
- WH/Stock
- WH/Input
- WH/Output
- Receipt
- Purchase Order
- RFQ
- Goods
- Track Inventory
- On Hand
- Forecasted
- Bill Matching
- Vendor
- Replenish Location

---

# Day 15 Summary

Today I learned the fundamentals of Inventory Management in Odoo. I explored warehouse configuration, locations, operation types, and inventory concepts. I created a new product (**Wireless Mouse**), enabled inventory tracking, created a Purchase Order, received 100 units into the warehouse, validated the receipt, and verified that the **On Hand Quantity** was updated successfully. I also understood the purpose of Bill Matching and how the Purchase → Receipt → Inventory workflow operates in a real business environment.

---

# Day 15 Status

**Day 15 – Inventory Basics:** ✅ Completed (100%)
