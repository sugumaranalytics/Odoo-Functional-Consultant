# Day 16 - Odoo Inventory Operations

**Course:** Odoo Functional Consultant  
**Module:** Inventory  
**Day:** 16

---

# Learning Objectives

By the end of Day 16, you will understand:

- Delivery Orders
- Customer Returns
- Internal Transfers
- Inventory Adjustments
- Warehouse Stock Movement
- Warehouse Document Types

---

# 1. Delivery Order

## What is a Delivery Order?

A Delivery Order is created automatically when a Sales Order is confirmed.

It is used to deliver products from the warehouse to the customer.

---

## Navigation

Sales

→ Orders

→ Orders

→ Open Confirmed Sales Order

→ Delivery

---

## Workflow

```
Quotation

↓

Sales Order

↓

Delivery Order (WH/OUT)

↓

Validate

↓

Customer Receives Goods
```

---

## Example

Customer:

Anitha Cottons

Product:

Wireless Mouse

Quantity:

2

After Validation

Warehouse Stock

↓

Customer

---

# WH/OUT Meaning

WH

Warehouse

OUT

Outgoing Products

Example

WH/OUT/00002

---

# 2. Customer Return

Sometimes customers return products because of

- Wrong Item
- Damaged Item
- Defective Product
- Exchange
- Refund

---

## Navigation

Sales

↓

Orders

↓

Open Delivery

↓

Return

↓

Enter Quantity

↓

Return

↓

Validate

---

## Workflow

```
Customer

↓

Warehouse (WH/IN)
```

---

## Example

Product

Wireless Mouse

Returned Quantity

1

Warehouse Stock automatically increases after validation.

---

# WH/IN Meaning

WH

Warehouse

IN

Incoming Products

Example

WH/IN/00005

---

# 3. Internal Transfer

Internal Transfer moves stock from one internal location to another.

No Customer

No Vendor

Only warehouse locations change.

---

## Navigation

Inventory

↓

Operations

↓

Internal Transfers

↓

New

---

## Example

Source

WH/Stock

Destination

WH/Stock/Shelf A

Product

Wireless Mouse

Quantity

1

---

## Workflow

```
WH/Stock

↓

WH/Stock/Shelf A
```

---

## Internal Transfer Number

WH/INT

Meaning

Warehouse Internal Transfer

Example

WH/INT/00002

---

# Result

Before

WH/Stock = 98

Shelf A = 0

↓

Internal Transfer

↓

After

WH/Stock = 97

Shelf A = 1

Total Company Stock remains the same.

---

# 4. Inventory Adjustment

Inventory Adjustment is used when physical stock and system stock are different.

---

## Reasons

- Damaged Goods
- Lost Products
- Manual Counting
- Annual Stock Audit
- Stock Verification

---

## Navigation

Inventory

↓

Operations

↓

Inventory Adjustments

---

## Example

System Quantity

97

Physical Count

96

Difference

-1

Click

Apply

System Quantity becomes

96

---

# Example (Practice)

Current Quantity

97

Counted Quantity

97

Difference

0

No stock change is required.

---

# Inventory Adjustment Process

```
Physical Count

↓

Enter Counted Quantity

↓

Difference Calculated

↓

Apply

↓

Inventory Updated
```

---

# Warehouse Document Types

| Document | Purpose |
|-----------|----------|
| WH/IN | Incoming Products |
| WH/OUT | Outgoing Products |
| WH/INT | Internal Stock Transfer |

---

# Complete Inventory Flow

```
Vendor

↓

Purchase Order

↓

Receipt (WH/IN)

↓

Warehouse

↓

Internal Transfer (WH/INT)

↓

Shelf A

↓

Delivery (WH/OUT)

↓

Customer

↓

Customer Return (WH/IN)

↓

Warehouse
```

---

# Business Example

ABC Technologies purchased 100 Wireless Mouse.

Vendor delivers products.

↓

Receipt completed.

↓

Warehouse stores products.

↓

Customer purchases 2 Wireless Mouse.

↓

Delivery Order created.

↓

Warehouse delivers products.

↓

Customer returns 1 Wireless Mouse.

↓

Warehouse receives returned product.

↓

Warehouse moves stock from WH/Stock to Shelf A.

↓

Warehouse performs stock counting.

↓

Inventory Adjustment confirms actual stock.

---

# Interview Questions

## 1. What is a Delivery Order?

A Delivery Order is a warehouse document used to deliver products from the warehouse to customers after confirming a Sales Order.

---

## 2. What is WH/OUT?

WH/OUT represents outgoing products from the warehouse to the customer.

---

## 3. What is WH/IN?

WH/IN represents incoming products into the warehouse from vendors or customer returns.

---

## 4. What is an Internal Transfer?

An Internal Transfer moves products between internal warehouse locations without involving customers or vendors.

---

## 5. Does an Internal Transfer change company stock?

No.

It changes only the storage location.

The total company stock remains the same.

---

## 6. What is Inventory Adjustment?

Inventory Adjustment updates the system quantity to match the actual physical stock counted in the warehouse.

---

## 7. When is Inventory Adjustment used?

- Physical Stock Count
- Annual Audit
- Damaged Products
- Lost Products
- Stock Verification

---

# Key Terms

| Term | Meaning |
|------|---------|
| Receipt | Products received from Vendor |
| Delivery | Products delivered to Customer |
| Return | Customer sends products back |
| Internal Transfer | Move stock inside warehouse |
| Inventory Adjustment | Correct stock after physical counting |
| WH/IN | Warehouse Incoming |
| WH/OUT | Warehouse Outgoing |
| WH/INT | Warehouse Internal Transfer |

---

# Day 16 Summary

✅ Delivery Orders

✅ Customer Returns

✅ Internal Transfers

✅ Inventory Adjustments

✅ WH/IN

✅ WH/OUT

✅ WH/INT

✅ Warehouse Stock Movement

✅ Inventory Verification

---

# Next Day (Day 17)

**Inventory Reporting & Product Traceability**

Topics:

- Inventory Reports
- Product Traceability
- Stock Moves
- Inventory Valuation
- Forecasted Inventory
- Reordering Rules
- Inventory Dashboard
- Reporting for Functional Consultants
