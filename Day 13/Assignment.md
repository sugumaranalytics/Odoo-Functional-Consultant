# Day 13 – Assignment (With Answers)

**Course:** Odoo Functional Consultant (60 Days)  
**Day:** 13  
**Topic:** Purchase → Inventory → Sales Workflow  
**Author:** Sugumar Ranganathan  
**Email:** contact.sugumarai@gmail.com

---

# Objective

Perform the complete Purchase → Inventory → Sales workflow and understand how stock moves in Odoo.

---

# Assignment 1 – Create a New Product

### Task

Create a product with the following details.

| Field | Value |
|--------|-------|
| Product Name | Keyboard |
| Product Type | Goods |
| Track Inventory | Enabled |
| Sales | Enabled |
| Purchase | Enabled |
| Sales Price | ₹1,500 |
| Cost | ₹1,000 |

### Answer

Product **Keyboard** created successfully with **Track Inventory** enabled.

---

# Assignment 2 – Configure Vendor

### Task

Configure vendor information.

| Field | Value |
|--------|-------|
| Vendor | Kumar Industries |
| Purchase Price | ₹1,000 |
| Minimum Quantity | 1 |

### Answer

Vendor information saved successfully under the Purchase tab.

---

# Assignment 3 – Create Purchase Order

### Task

Navigation

Purchase → Orders → Requests for Quotation

| Vendor | Product | Qty | Unit Price |
|---------|---------|----:|-----------:|
| Kumar Industries | Keyboard | 20 | ₹1,000 |

Click

- Save
- Confirm Order

### Answer

Purchase Order created and confirmed successfully.

---

# Assignment 4 – Receive Products

### Task

Open the Purchase Order.

Click

Receive Products

Verify

- Product = Keyboard
- Quantity = 20

Click

Validate

### Answer

Receipt status changed to **Done**.

Inventory increased from **0 → 20**.

---

# Assignment 5 – Verify Inventory

Navigation

Inventory → Products → Keyboard

### Expected Result

| Smart Button | Value |
|--------------|------:|
| On Hand | 20 |
| Forecasted | 20 |
| Purchased | 20 |

### Answer

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

Click

- Save
- Confirm

### Answer

Sales Order created successfully.

Delivery Order generated automatically.

---

# Assignment 7 – Deliver Product

Click

Delivery

Verify

- Product = Keyboard
- Quantity = 5

Click

Validate

### Answer

Delivery status changed to **Done**.

Inventory reduced by 5 units.

---

# Assignment 8 – Verify Inventory After Delivery

Navigation

Inventory → Products → Keyboard

### Result

| Before | After |
|---------|------:|
| On Hand | 20 → 15 |
| Forecasted | 20 → 15 |
| Purchased | 20 |
| Sold | 5 |

### Answer

Inventory reduced correctly.

---

# Assignment 9 – Observe Smart Buttons

### Question

Record the smart button values.

### Answer

| Smart Button | Value |
|--------------|------:|
| On Hand | 15 |
| Forecasted | 15 |
| Purchased | 20 |
| Sold | 5 |
| Incoming | 0 |
| Outgoing | 0 |

---

# Assignment 10 – Interview Questions

### 1. What happens when a Purchase Receipt is validated?

### Answer

The purchased products are added to warehouse inventory, and the **On Hand** quantity increases.

---

### 2. When is inventory reduced?

### Answer

Inventory is reduced only after the **Delivery Order** is validated.

---

### 3. What is the difference between On Hand and Forecasted Quantity?

### Answer

**On Hand**

The actual physical stock available in the warehouse.

**Forecasted**

The expected stock after considering incoming and outgoing stock movements.

---

### 4. Why should Track Inventory be enabled before using a product?

### Answer

Because Odoo creates stock movements only for products with **Track Inventory** enabled. Without it, inventory quantities will not increase or decrease.

---

### 5. Which document creates stock movement?

Options

- Purchase Order
- Sales Order
- Delivery Order
- Invoice

### Answer

**Purchase Receipt** increases stock.

**Delivery Order** decreases stock.

Purchase Orders, Sales Orders, and Invoices alone do **not** change inventory.

---

# Mini Challenge

Create another product.

Example

Mouse

Purchase

15 Units

Sell

3 Units

### Answer

| Purchased | Sold | Final Stock |
|-----------:|-----:|------------:|
| 15 | 3 | 12 |

---

# Practical Scenario

A computer shop purchases

20 Keyboards.

Inventory becomes

20 Units.

A customer purchases

5 Keyboards.

After validating the Delivery Order,

Inventory becomes

15 Units.

This is how businesses track inventory in Odoo.

---

# Summary Questions

### Q1. Which operation increases stock?

**Answer**

Purchase Receipt.

---

### Q2. Which operation decreases stock?

**Answer**

Delivery Order.

---

### Q3. Can a Sales Order reduce inventory?

**Answer**

No.

Inventory is reduced only after the Delivery Order is validated.

---

### Q4. Why is the Delivery Order important?

**Answer**

It confirms that products have physically left the warehouse and updates inventory.

---

### Q5. Which smart button shows the current stock?

**Answer**

**On Hand**.

---

### Q6. What did you learn in Day 13?

**Answer**

- Product Creation
- Inventory Tracking
- Vendor Configuration
- Purchase Orders
- Purchase Receipts
- Warehouse Stock Management
- Sales Orders
- Delivery Orders
- Inventory Validation
- Stock Movement
- Smart Buttons
- Complete Purchase → Inventory → Sales Workflow

---

# Final Workflow

```text
Create Product
       │
       ▼
Configure Vendor
       │
       ▼
Purchase Order
       │
       ▼
Receive Products
       │
       ▼
Warehouse Stock = 20
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
Warehouse Stock = 15
```

---

# Assignment Checklist

- ✅ Product Created
- ✅ Vendor Configured
- ✅ Purchase Order Created
- ✅ Products Received
- ✅ Inventory Updated
- ✅ Sales Order Created
- ✅ Delivery Order Validated
- ✅ Inventory Reduced
- ✅ Smart Buttons Verified
- ✅ End-to-End Workflow Completed

---

# Day 13 Completed Successfully 🎉

**Prepared by:** Sugumar Ranganathan  
**Email:** contact.sugumarai@gmail.com
