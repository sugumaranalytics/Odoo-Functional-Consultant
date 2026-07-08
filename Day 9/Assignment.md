# Day 9 – Assignment with Answers
## Odoo Functional Consultant – Sales Module Overview

---

# Objective

Understand the complete Sales process in Odoo, including Quotations, Sales Orders, Delivery, Invoicing, and Payments.

---

# Question 1

## What is the Sales Module?

### Answer

The Sales Module in Odoo helps businesses manage the complete sales process from creating quotations to receiving customer payments.

---

# Question 2

## Why do companies use the Sales Module?

### Answer

Companies use the Sales Module to:

- Create quotations
- Manage sales orders
- Sell products and services
- Generate invoices
- Record customer payments
- Track sales performance

---

# Question 3

## List the major components of the Sales Module.

### Answer

- Customers
- Products
- Quotations
- Sales Orders
- Delivery
- Invoices
- Payments
- Pricelists
- Taxes
- Reports

---

# Question 4

## Explain the complete Sales Workflow.

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

# Question 5

## What is a Quotation?

### Answer

A Quotation is a price offer sent to the customer before confirming the sale.

It contains:

- Customer
- Products
- Quantity
- Price
- Taxes
- Total Amount

---

# Question 6

## What is a Sales Order?

### Answer

A Sales Order is created when the customer accepts the quotation. It confirms that the customer has agreed to purchase the products or services.

---

# Question 7

## What is an Invoice?

### Answer

An Invoice is an official bill sent to the customer requesting payment.

---

# Question 8

## What are Payment Terms?

### Answer

Payment Terms specify when the customer must pay.

Examples:

- Immediate
- 15 Days
- 30 Days
- 50% Advance

---

# Question 9

## What is the purpose of Taxes in the Sales Module?

### Answer

Taxes are automatically calculated based on the product and tax configuration.

Examples:

- GST 5%
- GST 12%
- GST 18%
- GST 28%

---

# Question 10

## What is Chatter?

### Answer

Chatter is a communication section available in quotations, sales orders, and invoices. It is used to record messages, notes, activities, and attachments.

---

# Practical Exercise 1

## Create the following Customer.

| Field | Value |
|--------|-------|
| Customer | ABC Technologies |
| Address | Chennai |
| Phone | 9876543210 |
| Email | info@abc.com |

### Answer

Customer created successfully.

✅ Completed

---

# Practical Exercise 2

## Create the following Product.

| Field | Value |
|--------|-------|
| Product Name | Computer |
| Product Type | Storable Product |
| Sales Price | ₹35,000 |
| Tax | GST 5% |

### Answer

Product created successfully.

✅ Completed

---

# Practical Exercise 3

## Create the following Quotation.

| Field | Value |
|--------|-------|
| Customer | ABC Technologies |
| Product | Computer |
| Quantity | 1 |
| Price | ₹35,000 |

### Answer

Quotation created successfully.

✅ Completed

---

# Practical Exercise 4

## Add Terms and Conditions.

```text
Delivery within 7 working days.
One-year warranty.
Payment before delivery.
```

### Answer

Terms and Conditions added successfully.

✅ Completed

---

# Practical Exercise 5

## Add an Internal Note.

```text
Customer requested delivery on Friday.
```

### Answer

Internal Note added successfully.

✅ Completed

---

# Practical Exercise 6

## Schedule an Activity.

| Field | Value |
|--------|-------|
| Activity | Call |
| Summary | Confirm delivery date |

### Answer

Activity scheduled successfully.

✅ Completed

---

# Practical Exercise 7

## Confirm the Quotation.

### Answer

Quotation converted into a Sales Order.

```text
Quotation
      ↓
Sales Order
```

✅ Completed

---

# Practical Exercise 8

## Create an Invoice.

### Answer

Invoice created successfully.

Invoice Status

```text
Draft
```

✅ Completed

---

# Practical Exercise 9

## Post the Invoice.

### Answer

Invoice status changed successfully.

```text
Draft
      ↓
Posted
```

✅ Completed

---

# Practical Exercise 10

## Register Customer Payment.

### Answer

Payment registered successfully.

Invoice Status

```text
Posted
      ↓
Paid
```

✅ Completed

---

# Real Business Scenario

ABC Technologies purchases one Computer worth ₹35,000.

Perform the following tasks.

- Create Customer
- Create Product
- Create Quotation
- Add Product
- Add Terms and Conditions
- Add Internal Note
- Schedule Activity
- Confirm Sales Order
- Create Invoice
- Register Payment

### Answer

### Step 1

Created Customer

**ABC Technologies**

---

### Step 2

Created Product

**Computer**

Sales Price

₹35,000

---

### Step 3

Created Quotation

Customer

ABC Technologies

---

### Step 4

Added Product

Computer

Quantity

1

Price

₹35,000

---

### Step 5

Added Terms and Conditions

```text
Delivery within 7 working days.
One-year warranty.
Payment before delivery.
```

---

### Step 6

Added Internal Note

```text
Customer requested delivery on Friday.
```

---

### Step 7

Scheduled Activity

- Call
- Confirm delivery date

---

### Step 8

Confirmed Quotation

```text
Quotation
      ↓
Sales Order
```

---

### Step 9

Created Invoice

```text
Sales Order
      ↓
Draft Invoice
```

---

### Step 10

Posted Invoice and Registered Payment

```text
Draft
      ↓
Posted
      ↓
Paid
```

---

# Interview Questions

## What is the Sales Module?

**Answer**

The Sales Module manages quotations, sales orders, invoicing, payments, and customer sales.

---

## What is a Quotation?

**Answer**

A quotation is a price offer sent to the customer before the sale is confirmed.

---

## What is a Sales Order?

**Answer**

A Sales Order confirms the customer's purchase after the quotation is accepted.

---

## What is an Invoice?

**Answer**

An Invoice is a bill requesting payment from the customer.

---

## What happens after customer payment?

**Answer**

The invoice status changes to **Paid**.

---

## Why are Payment Terms important?

**Answer**

They define when and how the customer should make payment.

---

## What is Chatter?

**Answer**

Chatter is used for messages, internal notes, activities, and document communication.

---

## What is the difference between a Quotation and a Sales Order?

**Answer**

A Quotation is an offer to the customer.

A Sales Order is a confirmed customer purchase.

---

## Why are Terms and Conditions important?

**Answer**

They define the business rules such as delivery time, payment conditions, and warranty.

---

## Why do companies use the Sales Module?

**Answer**

To automate and manage the complete sales process efficiently from quotation to payment.

---

# Self Assessment

| Task | Status |
|------|--------|
| Understood Sales Module | ✅ |
| Created Customer | ✅ |
| Created Product | ✅ |
| Created Quotation | ✅ |
| Added Terms & Conditions | ✅ |
| Added Internal Notes | ✅ |
| Scheduled Activity | ✅ |
| Confirmed Sales Order | ✅ |
| Created Invoice | ✅ |
| Registered Payment | ✅ |

---

# Learning Outcome

After completing this assignment, you can:

- Explain the Sales Module.
- Create Customers and Products.
- Prepare Quotations.
- Confirm Sales Orders.
- Create and Post Invoices.
- Register Customer Payments.
- Understand the complete Order-to-Cash (O2C) process.

---

## GitHub Commit Message

```text
Day 9: Completed Sales Module Overview Assignment with Answers
```

---

# Day 9 Status

**Module:** Sales Module Overview

**Assignment:** ✅ Completed

**Next Topic:** Day 10 – Quotation Management
