# Day 11 – Sales Orders & Delivery
## Odoo Functional Consultant – Detailed Notes

---

# Learning Objectives

By the end of this lesson, you will understand:

- What is a Sales Order?
- Sales Order Workflow
- Order Confirmation
- Delivery Process
- Delivery Order
- Warehouse Concept
- Inventory Integration
- Invoice Status
- Delivery Status
- Best Practices

---

# What is a Sales Order?

A Sales Order (SO) is a confirmed order placed by a customer after accepting a quotation.

It is an official document that confirms the company will deliver the requested products or services.

---

# Sales Workflow

```text
Lead
    ↓
Opportunity
    ↓
Quotation
    ↓
Sales Order
    ↓
Delivery
    ↓
Invoice
    ↓
Payment
```

---

# Sales Order Creation

Navigation

```
Sales
    ↓
Orders
    ↓
Quotations
```

Open a quotation and click **Confirm**.

The quotation becomes a Sales Order.

Example

Sales Order Number

```
S00004
```

---

# Sales Order Information

A Sales Order contains

- Customer
- Order Number
- Order Date
- Salesperson
- Products
- Quantity
- Unit Price
- Taxes
- Total Amount
- Invoice Status
- Delivery Status

---

# Customer Information

Example

Customer

ABC Technologies

Location

Chennai

Tamil Nadu

India

---

# Product Information

Example

| Product | Quantity | Unit Price |
|---------|---------:|-----------:|
| Computer | 1 | ₹35,000 |

GST

5%

Total

₹36,750

---

# Sales Order Status

```
Quotation

↓

Quotation Sent

↓

Sales Order
```

---

# Invoice Process

After confirming the Sales Order

```
Sales Order

↓

Create Invoice

↓

Draft Invoice

↓

Post Invoice

↓

Register Payment

↓

Paid
```

---

# Invoice Status

Possible statuses

- Draft
- Posted
- Paid

Example

Invoice Number

```
INV/26-27/0001
```

Status

```
Paid
```

---

# Payment

Example

Customer paid

₹36,750

Payment Status

```
Paid
```

---

# Delivery Process

Normally, after confirming a Sales Order,

Odoo automatically creates a Delivery Order.

```
Sales Order

↓

Delivery Order

↓

Validate Delivery

↓

Done
```

---

# Delivery Order

A Delivery Order tells the warehouse team

- Which customer
- Which products
- Quantity
- Delivery address

Example

Customer

ABC Technologies

Product

Computer

Quantity

1

---

# Warehouse

Warehouse stores products before delivery.

Examples

- Main Warehouse
- Chennai Warehouse
- Bangalore Warehouse

---

# Inventory Integration

Sales and Inventory work together.

When a Delivery Order is validated,

Inventory stock is reduced automatically.

---

# Important Note (Your Practical)

During this practice,

- Inventory application was installed.
- Inventory was **not configured**.
- Operation Types were not created.
- Therefore, Odoo did **not** create a Delivery Order.

Because of this,

The Delivery practical will be completed during the Inventory module.

---

# Screenshot Observation

Sales Order

```
S00004
```

Invoice

```
Paid
```

Delivered Quantity

```
0.00
```

Delivery Button

```
Not Available
```

Reason

Inventory configuration is pending.

---

# Smart Buttons

Normally a Sales Order contains

- Delivery
- Invoice
- Customer
- Payments

In this practice,

Only the Invoice button was available because Inventory was not configured.

---

# Practical Exercise Completed

Created

✅ Sales Order

Confirmed Quotation

✅

Created Invoice

✅

Posted Invoice

✅

Registered Payment

✅

Invoice Status

✅ Paid

Delivery

⏳ Pending (Inventory configuration required)

---

# Delivery Flow (Concept)

```text
Sales Order
      ↓
Delivery Order
      ↓
Pick Product
      ↓
Pack Product
      ↓
Ship Product
      ↓
Validate Delivery
      ↓
Done
```

---

# Best Practices

✔ Verify customer details before confirming the Sales Order.

✔ Check product availability.

✔ Create Invoice only after confirmation.

✔ Register customer payment correctly.

✔ Configure Inventory before using Delivery Orders.

✔ Validate Delivery after products are shipped.

✔ Keep Sales and Inventory synchronized.

---

# Advantages of Sales Orders

- Confirms customer purchase.
- Generates invoices.
- Integrates with Inventory.
- Tracks order status.
- Improves customer service.
- Maintains complete sales records.

---

# Interview Questions

## What is a Sales Order?

A Sales Order is a confirmed customer order created after accepting a quotation.

---

## What happens after confirming a Sales Order?

Normally, Odoo creates a Delivery Order.

---

## What is a Delivery Order?

A warehouse document used to deliver products to customers.

---

## Why was the Delivery Order not created in this practice?

Because the Inventory module was not configured.

---

## What is the Invoice Status after payment?

Paid.

---

## What is the relationship between Sales and Inventory?

Sales creates Delivery Orders and Inventory manages stock movement.

---

## What is Delivery Validation?

It confirms that the products have been delivered successfully.

---

## What is the purpose of a Warehouse?

To store products before delivery.

---

## When will the Delivery practical be completed?

During the Inventory module after configuring Warehouses and Operation Types.

---

## Why do businesses use Sales Orders?

To confirm customer purchases, generate invoices, manage deliveries, and track sales.

---

# Day 11 Summary

You learned

- Sales Orders
- Order Confirmation
- Invoice Workflow
- Payment Registration
- Delivery Concept
- Delivery Orders
- Warehouse
- Inventory Integration
- Invoice Status
- Delivery Flow
- Best Practices
- Interview Questions

---

## GitHub Commit Message

```text
Day 11: Completed Sales Orders & Delivery Concepts, Invoice Workflow, Payment Process, and Delivery Flow Notes
```

---

# Day 11 Status

**Status:** ✅ Completed

**Note:** Delivery practical will be completed after Inventory configuration in Day 15 and Day 16.

**Next Topic:** Day 12 – Product Management
