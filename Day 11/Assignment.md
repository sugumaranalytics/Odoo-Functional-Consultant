# Day 11 – Assignment with Answers
## Odoo Functional Consultant – Sales Orders & Delivery

---

# Objective

Learn how Sales Orders are created, how they are confirmed, how Delivery works, and how Sales integrates with Inventory and Invoicing.

---

# Question 1

## What is a Sales Order?

### Answer

A Sales Order is a confirmed customer order created after a customer accepts a quotation.

---

# Question 2

## When is a Sales Order created?

### Answer

A Sales Order is created after the customer approves and confirms the quotation.

---

# Question 3

## Explain the Sales Order Workflow.

### Answer

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

# Question 4

## What information does a Sales Order contain?

### Answer

A Sales Order contains:

- Customer
- Sales Order Number
- Order Date
- Products
- Quantity
- Unit Price
- Taxes
- Total Amount
- Invoice Status
- Delivery Status

---

# Question 5

## What is a Delivery Order?

### Answer

A Delivery Order is a warehouse document used to deliver products to the customer after a Sales Order is confirmed.

---

# Question 6

## What is the purpose of a Warehouse?

### Answer

A Warehouse stores products and manages stock before they are delivered to customers.

---

# Question 7

## What happens when a Delivery Order is validated?

### Answer

The delivery is completed and the inventory stock is automatically updated.

---

# Question 8

## What is Delivery Validation?

### Answer

Delivery Validation confirms that the products have been shipped or delivered to the customer.

---

# Question 9

## What is Invoice Status?

### Answer

Invoice Status shows the progress of invoicing.

Examples:

- Draft
- Posted
- Paid

---

# Question 10

## Why is Inventory important in the Delivery process?

### Answer

Inventory manages stock movement and creates Delivery Orders after a Sales Order is confirmed.

---

# Practical Exercise 1

## Open the Sales Module.

### Answer

Navigation

```text
Sales

↓

Orders

↓

Quotations
```

Opened successfully.

✅ Completed

---

# Practical Exercise 2

## Open Sales Order S00004.

### Answer

Sales Order opened successfully.

Customer

ABC Technologies

Status

Sales Order

✅ Completed

---

# Practical Exercise 3

## Verify the Sales Order details.

### Answer

Customer

ABC Technologies

Product

Computer

Quantity

1

Price

₹35,000

GST

5%

Total

₹36,750

✅ Verified

---

# Practical Exercise 4

## Open the Invoice.

### Answer

Invoice Number

```text
INV/26-27/0001
```

Invoice opened successfully.

Status

Paid

✅ Completed

---

# Practical Exercise 5

## Verify Payment Status.

### Answer

Payment Status

```text
Paid
```

Customer payment was successfully registered.

✅ Completed

---

# Practical Exercise 6

## Check whether a Delivery Order was created.

### Answer

No Delivery Order was created.

Reason

Inventory module was installed but not configured.

Therefore,

No Delivery Smart Button was available.

✅ Verified

---

# Practical Exercise 7

## Explain the normal Delivery Flow.

### Answer

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

# Practical Exercise 8

## Explain why Delivery could not be completed during this practice.

### Answer

The Inventory module was not configured.

Operation Types and Warehouse settings were not created.

Therefore,

Odoo did not generate a Delivery Order.

Delivery practical will be completed during the Inventory module.

✅ Completed

---

# Practical Exercise 9

## Explain the integration between Sales and Inventory.

### Answer

Sales confirms customer orders.

Inventory manages stock.

After a Sales Order is confirmed,

Inventory creates the Delivery Order.

After delivery,

Stock quantity is reduced automatically.

---

# Practical Exercise 10

## Explain the complete Sales Process.

### Answer

```text
Customer Inquiry

↓

Quotation

↓

Customer Approval

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

# Real Business Scenario

ABC Technologies purchases one Computer worth ₹35,000.

Perform the following activities.

- Create Quotation
- Confirm Sales Order
- Create Invoice
- Post Invoice
- Register Payment
- Check Delivery

### Answer

### Step 1

Quotation created.

✅

---

### Step 2

Quotation confirmed.

Sales Order

```
S00004
```

✅

---

### Step 3

Invoice created.

```
INV/26-27/0001
```

✅

---

### Step 4

Invoice posted.

Status

Posted

✅

---

### Step 5

Payment registered.

Invoice Status

Paid

✅

---

### Step 6

Delivery checked.

Result

Delivery Order was not generated because Inventory configuration is pending.

Delivery will be completed in Day 15–16.

✅

---

# Interview Questions

## What is a Sales Order?

### Answer

A Sales Order is a confirmed customer order created after a quotation is accepted.

---

## What is a Delivery Order?

### Answer

A Delivery Order is a warehouse document used to dispatch products to customers.

---

## Why was the Delivery Order not created in this practice?

### Answer

Because the Inventory module was installed but not configured.

---

## What is Delivery Validation?

### Answer

It confirms that the products have been delivered successfully.

---

## What is the purpose of Inventory integration?

### Answer

Inventory tracks stock movement and automatically updates stock after delivery.

---

## What happens after confirming a Sales Order?

### Answer

Normally, Odoo creates a Delivery Order and allows invoicing.

---

## What was the Invoice Status after payment?

### Answer

Paid.

---

## What is the purpose of a Warehouse?

### Answer

To store products before they are delivered to customers.

---

## Why are Sales Orders important?

### Answer

Sales Orders confirm customer purchases and start the delivery and invoicing process.

---

## When will the Delivery practical be completed?

### Answer

After configuring Inventory, Warehouses, and Operation Types in Day 15 and Day 16.

---

# Self Assessment

| Task | Status |
|------|--------|
| Understood Sales Orders | ✅ |
| Opened Sales Order | ✅ |
| Verified Customer Details | ✅ |
| Verified Products | ✅ |
| Verified Invoice | ✅ |
| Verified Payment | ✅ |
| Understood Delivery Flow | ✅ |
| Understood Inventory Integration | ✅ |
| Learned Delivery Concept | ✅ |
| Understood why Delivery was Pending | ✅ |

---

# Learning Outcome

After completing this assignment, you can:

- Explain Sales Orders.
- Describe the complete Order-to-Cash process.
- Verify Sales Orders and Invoices.
- Understand the Delivery workflow.
- Explain Inventory integration.
- Identify why Delivery Orders may not be created.
- Understand when Delivery Validation is performed.

---

## GitHub Commit Message

```text
Day 11: Completed Sales Orders & Delivery Assignment with Answers
```

---

# Day 11 Status

**Module:** Sales Orders & Delivery

**Assignment:** ✅ Completed

**Note:** Delivery practical will be completed after Inventory configuration in Day 15–16.

**Next Topic:** Day 12 – Product Management
