# Day 13 – Assignment

**Course:** Odoo Functional Consultant (60 Days)  
**Day:** 13  
**Topic:** Purchase → Inventory → Sales Workflow  
**Author:** Sugumar Ranganathan  
**Email:** contact.sugumarai@gmail.com

---

# Objective

Practice the complete inventory workflow by creating products, purchasing stock, receiving products, selling products, delivering them, and verifying inventory changes.

---

# Assignment 1 – Create a New Product

Create a new product with the following details.

| Field | Value |
|--------|-------|
| Product Name | Keyboard |
| Product Type | Goods |
| Track Inventory | Enabled |
| Sales | Enabled |
| Purchase | Enabled |
| Sales Price | ₹1,500 |
| Cost | ₹1,000 |

Expected Result

- Product created successfully.

---

# Assignment 2 – Configure Vendor

Vendor Details

| Field | Value |
|--------|-------|
| Vendor | Kumar Industries |
| Purchase Price | ₹1,000 |
| Minimum Quantity | 1 |

Expected Result

Vendor information saved successfully.

---

# Assignment 3 – Create Purchase Order

Navigation

Purchase → Orders → Requests for Quotation

Purchase Details

| Field | Value |
|--------|-------|
| Vendor | Kumar Industries |
| Product | Keyboard |
| Quantity | 20 |
| Unit Price | ₹1,000 |

Tasks

- Save
- Confirm Order

Expected Result

Purchase Order created successfully.

---

# Assignment 4 – Receive Products

Open the Purchase Order.

Click

Receive Products

Verify

- Product = Keyboard
- Demand = 20
- Quantity = 20

Click

Validate

Expected Result

Receipt status becomes **Done**.

---

# Assignment 5 – Verify Inventory

Navigation

Inventory → Products → Keyboard

Verify

| Smart Button | Expected Value |
|--------------|----------------|
| On Hand | 20 |
| Forecasted | 20 |
| Purchased | 20 |

Expected Result

Inventory updated successfully.

---

# Assignment 6 – Create Sales Order

Navigation

Sales → Orders → Quotations

Customer

ABC Technologies

Product

Keyboard

Quantity

5

Tasks

- Save
- Confirm

Expected Result

Sales Order confirmed.

---

# Assignment 7 – Deliver Product

Click

Delivery

Verify

| Field | Value |
|--------|-------|
| Product | Keyboard |
| Quantity | 5 |

Click

Validate

Expected Result

Delivery status becomes **Done**.

---

# Assignment 8 – Verify Inventory After Delivery

Navigation

Inventory → Products → Keyboard

Verify

| Before Delivery | After Delivery |
|-----------------|----------------|
| On Hand = 20 | On Hand = 15 |
| Forecasted = 20 | Forecasted = 15 |
| Purchased = 20 | Purchased = 20 |
| Sold = 5 | Sold = 5 |

Expected Result

Inventory reduced correctly.

---

# Assignment 9 – Observe Smart Buttons

Open the Keyboard product and record the following values.

| Smart Button | Value |
|--------------|-------|
| On Hand | ______ |
| Forecasted | ______ |
| Purchased | ______ |
| Sold | ______ |
| Incoming | ______ |
| Outgoing | ______ |

---

# Assignment 10 – Practical Questions

### 1. What happens when a Purchase Receipt is validated?

Answer:

_____________________________________________________

---

### 2. When is inventory reduced?

Answer:

_____________________________________________________

---

### 3. What is the difference between On Hand and Forecasted Quantity?

Answer:

_____________________________________________________

---

### 4. Why should Track Inventory be enabled before using a product?

Answer:

_____________________________________________________

---

### 5. Which document creates stock movement?

- Purchase Order
- Sales Order
- Delivery Order
- Invoice

Answer:

_____________________________________________________

---

# Mini Challenge

Create another product.

Example

- Mouse
- Printer
- Laptop
- CPU

Perform the complete workflow.

- Purchase 15 units
- Receive stock
- Sell 3 units
- Deliver products
- Verify inventory

Record the final stock.

| Purchased | Sold | Final Stock |
|-----------:|-----:|------------:|
| 15 | 3 | 12 |

---

# Expected Learning Outcomes

After completing this assignment, you should be able to:

- Create inventory-tracked products.
- Configure vendors.
- Create Purchase Orders.
- Receive products into inventory.
- Create Sales Orders.
- Validate Delivery Orders.
- Verify inventory movement.
- Understand stock increases and decreases.
- Interpret inventory smart buttons.
- Execute an end-to-end Purchase → Inventory → Sales workflow.

---

# Assignment Status

- [ ] Product Created
- [ ] Vendor Configured
- [ ] Purchase Order Created
- [ ] Products Received
- [ ] Inventory Verified
- [ ] Sales Order Created
- [ ] Delivery Validated
- [ ] Stock Reduced
- [ ] Smart Buttons Verified
- [ ] Assignment Completed

---

# Final Expected Result

```text
Product Created
       │
       ▼
Purchase Order
       │
       ▼
Receive Products
       │
       ▼
Stock = 20
       │
       ▼
Sales Order
       │
       ▼
Delivery
       │
       ▼
Stock = 15
```

---

**Prepared by:** Sugumar Ranganathan  
**Email:** contact.sugumarai@gmail.com
