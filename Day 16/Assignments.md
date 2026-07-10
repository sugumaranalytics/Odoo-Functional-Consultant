# Day 16 - Assignment with Answers

**Course:** Odoo Functional Consultant  
**Module:** Inventory  
**Day:** 16

---

# Assignment 1

## Question

What is a Delivery Order?

### Answer

A Delivery Order is a warehouse document created automatically after a Sales Order is confirmed. It is used to deliver products from the warehouse to the customer.

---

# Assignment 2

## Question

Explain the complete Delivery Order workflow.

### Answer

```
Quotation

↓

Sales Order

↓

Delivery Order (WH/OUT)

↓

Validate

↓

Customer Receives Product
```

---

# Assignment 3

## Question

What does WH/OUT mean?

### Answer

WH = Warehouse

OUT = Outgoing Products

Example:

```
WH/OUT/00002
```

It represents products moving from the warehouse to the customer.

---

# Assignment 4

## Question

Create a Sales Order.

### Answer

Customer

```
Anitha Cottons
```

Product

```
Wireless Mouse
```

Quantity

```
2
```

Confirm the quotation to create a Sales Order.

---

# Assignment 5

## Question

Validate the Delivery Order.

### Answer

Navigation

```
Sales

↓

Orders

↓

Open Sales Order

↓

Delivery

↓

Validate
```

Result

Warehouse stock decreases automatically.

---

# Assignment 6

## Question

What is Customer Return?

### Answer

Customer Return is the process of receiving products back from the customer into the warehouse.

Example reasons:

- Wrong Product
- Damaged Product
- Exchange
- Refund

---

# Assignment 7

## Question

Explain the Customer Return workflow.

### Answer

```
Customer

↓

Return

↓

WH/IN

↓

Warehouse Stock
```

---

# Assignment 8

## Question

What does WH/IN mean?

### Answer

WH

Warehouse

IN

Incoming Products

Example

```
WH/IN/00005
```

It represents products entering the warehouse.

---

# Assignment 9

## Question

What is an Internal Transfer?

### Answer

An Internal Transfer moves products from one warehouse location to another without involving a customer or vendor.

Example

```
WH/Stock

↓

WH/Stock/Shelf A
```

---

# Assignment 10

## Question

Create an Internal Transfer.

### Answer

Operation Type

```
Internal Transfer
```

Source Location

```
WH/Stock
```

Destination Location

```
WH/Stock/Shelf A
```

Product

```
Wireless Mouse
```

Quantity

```
1
```

Validate the transfer.

---

# Assignment 11

## Question

What does WH/INT mean?

### Answer

WH

Warehouse

INT

Internal Transfer

Example

```
WH/INT/00002
```

It represents stock movement between internal warehouse locations.

---

# Assignment 12

## Question

Does an Internal Transfer change company stock?

### Answer

No.

It only changes the storage location.

Example

Before

```
WH/Stock = 98

Shelf A = 0
```

After

```
WH/Stock = 97

Shelf A = 1
```

Total Company Stock

```
98
```

---

# Assignment 13

## Question

What is Inventory Adjustment?

### Answer

Inventory Adjustment is used to update the system quantity so that it matches the actual physical quantity counted in the warehouse.

---

# Assignment 14

## Question

When is Inventory Adjustment used?

### Answer

Inventory Adjustment is used during:

- Physical Stock Count
- Annual Stock Audit
- Damaged Products
- Lost Products
- Manual Verification
- Stock Reconciliation

---

# Assignment 15

## Question

Perform an Inventory Adjustment.

### Answer

Current Quantity

```
97
```

Counted Quantity

```
96
```

Difference

```
-1
```

Click

```
Apply
```

System quantity becomes

```
96
```

---

# Assignment 16

## Question

What happens if the Counted Quantity equals the On Hand Quantity?

### Answer

Example

On Hand Quantity

```
97
```

Counted Quantity

```
97
```

Difference

```
0
```

No stock change occurs after applying the adjustment.

---

# Assignment 17

## Question

Differentiate between Receipt, Delivery, Internal Transfer and Inventory Adjustment.

### Answer

| Process | Purpose |
|----------|----------|
| Receipt | Receive products from Vendor |
| Delivery | Deliver products to Customer |
| Internal Transfer | Move stock between warehouse locations |
| Inventory Adjustment | Correct stock after physical counting |

---

# Assignment 18

## Question

Explain the complete warehouse workflow.

### Answer

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

↓

Inventory Adjustment
```

---

# Assignment 19

## Question

What are the warehouse document prefixes used in Odoo?

### Answer

| Prefix | Meaning |
|---------|---------|
| WH/IN | Warehouse Incoming |
| WH/OUT | Warehouse Outgoing |
| WH/INT | Warehouse Internal Transfer |

---

# Assignment 20

## Question

ABC Technologies purchased 100 Wireless Mouse. Later, 2 were delivered to a customer, 1 was returned, and 1 was moved to Shelf A. Explain the stock movement.

### Answer

```
Vendor

↓

Receive 100 Mouse

↓

Warehouse

100

↓

Deliver 2

↓

Warehouse

98

↓

Customer Returns 1

↓

Warehouse

99

↓

Internal Transfer

WH/Stock

↓

WH/Stock/Shelf A

Stock in WH/Stock decreases by 1

Stock in Shelf A increases by 1

Total Company Stock

99
```

---

# Viva Questions

### 1. What is a Delivery Order?

A Delivery Order is used to deliver products from the warehouse to the customer after confirming a Sales Order.

---

### 2. What is WH/OUT?

WH/OUT represents outgoing warehouse deliveries.

---

### 3. What is WH/IN?

WH/IN represents incoming warehouse receipts or customer returns.

---

### 4. What is WH/INT?

WH/INT represents internal warehouse stock transfers.

---

### 5. What is Inventory Adjustment?

Inventory Adjustment updates the system stock to match the actual physical stock.

---

### 6. Why do businesses perform Inventory Adjustments?

To ensure that system stock accurately reflects the actual quantity available in the warehouse after audits, damages, losses, or counting differences.

---

# Day 16 Assignment Completed

✅ Delivery Orders

✅ Customer Returns

✅ WH/IN

✅ WH/OUT

✅ WH/INT

✅ Internal Transfers

✅ Inventory Adjustments

✅ Warehouse Workflow

**Score:** ⭐⭐⭐⭐⭐ (20/20)
