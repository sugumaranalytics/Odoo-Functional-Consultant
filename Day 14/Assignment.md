# Day 14 – Purchase Workflow (Vendor Bill & Payment)

## Course
**Odoo Functional Consultant – 30 Days Roadmap**

**Day:** 14 (Remaining)

**Module:** Purchase & Accounting Integration

---

# Objective

Learn how Odoo completes the Purchase Cycle after receiving products by creating a Vendor Bill and registering payment.

---

# Topics Covered

- Vendor Bill
- Bill Posting
- Register Payment
- Purchase Accounting Flow
- Procure-to-Pay (P2P) Process

---

# Purchase Workflow

```text
Need Product
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
Vendor Bill
      │
      ▼
Post Vendor Bill
      │
      ▼
Register Payment
      │
      ▼
Purchase Completed
```

---

# What is a Vendor Bill?

A **Vendor Bill** is the invoice received from the supplier after products are delivered.

It records the amount that the company needs to pay to the vendor.

**Simple Definition**

> Vendor Bill = Supplier Invoice

---

# Why Vendor Bill is Important?

Without a Vendor Bill:

- Inventory is updated.
- Products are received.
- Accounts department cannot record the payable amount.

Vendor Bill connects the **Purchase** module with the **Accounting** module.

---

# Real-Time Example

Company:

**ABC Technologies**

Vendor:

**Kumar Industries**

Product:

**Monitor**

Quantity:

10

Purchase Price:

₹12,000 each

Total:

₹120,000

---

# Live Practice Completed

### Step 1

Opened Purchase Order

```
Purchase → Orders → Purchase Orders
```

Opened:

```
P00006
```

---

### Step 2

Clicked

```
Create Bill
```

Vendor Bill created successfully.

Status:

```
Draft
```

---

### Step 3

Verified

- Vendor
- Product
- Quantity
- Price
- GST
- Total Amount

---

### Step 4

Entered

```
Bill Date
```

Confirmed Vendor Bill.

Status changed to

```
Posted
```

---

### Step 5

Clicked

```
Pay
```

Registered payment.

Status became

```
PAID
```

Green ribbon displayed on the Vendor Bill.

---

# Vendor Bill Screen

Contains:

- Vendor
- Bill Date
- Accounting Date
- Due Date
- Currency
- Invoice Lines
- Taxes
- Total Amount

---

# Purchase Accounting Flow

```text
Purchase Order
      │
      ▼
Receive Products
      │
      ▼
Vendor Bill
      │
      ▼
Post Bill
      │
      ▼
Vendor Payment
      │
      ▼
Paid
```

---

# Documents Used

| Document | Purpose |
|----------|---------|
| RFQ | Request supplier quotation |
| Purchase Order | Confirm purchase |
| Receipt | Receive products |
| Vendor Bill | Record supplier invoice |
| Payment | Pay supplier |

---

# Departments Involved

| Department | Responsibility |
|------------|----------------|
| Purchase | Create RFQ & Purchase Order |
| Warehouse | Receive Products |
| Accounts | Create Vendor Bill |
| Finance | Register Payment |

---

# Functional Consultant Knowledge

A Functional Consultant should know:

- RFQ process
- Purchase Order approval
- Product Receipt
- Vendor Bill creation
- Bill Posting
- Vendor Payment
- Purchase workflow
- Purchase and Accounting integration

---

# Navigation

### Open Purchase Orders

```
Purchase
→ Orders
→ Purchase Orders
```

---

### Create Vendor Bill

```
Purchase Order
→ Create Bill
```

---

### Post Vendor Bill

```
Vendor Bill
→ Confirm (Post)
```

---

### Register Payment

```
Vendor Bill
→ Pay
```

---

# Advantages of Vendor Bills

- Tracks supplier invoices
- Records company liabilities
- Integrates Purchase with Accounting
- Maintains payment history
- Supports GST accounting
- Improves financial reporting

---

# Business Scenario

ABC Technologies purchases 10 monitors from Kumar Industries.

Workflow:

1. Purchase team creates an RFQ.
2. Vendor provides a quotation.
3. Purchase Order is confirmed.
4. Warehouse receives the monitors.
5. Inventory increases.
6. Supplier sends the invoice.
7. Accounts creates the Vendor Bill.
8. Vendor Bill is posted.
9. Finance registers payment.
10. Vendor Bill status becomes **PAID**.

---

# Interview Questions

## 1. What is a Vendor Bill?

A Vendor Bill is the invoice received from a supplier after products are delivered. It records the amount payable to the supplier.

---

## 2. When is a Vendor Bill created?

After receiving products from the supplier.

---

## 3. Which module creates Vendor Bills?

Purchase module (integrated with Accounting).

---

## 4. What happens after posting a Vendor Bill?

The invoice becomes an official accounting entry and is ready for payment.

---

## 5. What is the final step of the Purchase Workflow?

Register Payment and mark the Vendor Bill as **Paid**.

---

# Key Points

- RFQ requests supplier quotations.
- Purchase Order confirms the purchase.
- Receipt updates inventory.
- Vendor Bill records the supplier invoice.
- Payment settles the vendor amount.
- Purchase workflow ends when the Vendor Bill is **Paid**.

---

# Day 14 Summary

✅ RFQ

✅ Purchase Order

✅ Product Receipt

✅ Inventory Updated

✅ Vendor Bill Created

✅ Vendor Bill Posted

✅ Vendor Payment Registered

✅ Purchase Workflow Completed

---

# Conclusion

Day 14 completed the **Procure-to-Pay (P2P)** cycle in Odoo.

You learned how the Purchase, Inventory, and Accounting modules work together to complete a real business purchasing process from supplier quotation to final payment.
