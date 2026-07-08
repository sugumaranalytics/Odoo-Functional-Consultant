# Day 10 – Quotation Management
## Odoo Functional Consultant – Detailed Notes

---

# Learning Objectives

By the end of Day 10, you will understand:

- What is a Quotation?
- Importance of Quotations
- Quotation Workflow
- Creating Quotations
- Customer Selection
- Product Selection
- Quantity & Unit Price
- Taxes
- Terms & Conditions
- Optional Products
- Internal Notes
- Sending Quotations
- Confirming Quotations
- Converting Quotations into Sales Orders
- Best Practices

---

# What is a Quotation?

A **Quotation** is a formal price offer sent to a customer before confirming a sale.

It contains all the details about the products or services being offered, including pricing, taxes, payment terms, and conditions.

A quotation is **not** a confirmed sale.

---

# Why is a Quotation Important?

A quotation helps:

- Inform the customer about pricing.
- Explain products and services.
- Define payment terms.
- Specify delivery conditions.
- Avoid misunderstandings.
- Obtain customer approval before the sale.

---

# Real World Example

ABC Technologies wants to purchase:

- Computer
- Quantity: 1
- Price: ₹35,000
- GST: 5%

Salesperson prepares a quotation.

Customer reviews it.

If accepted:

```
Quotation

↓

Sales Order
```

---

# Quotation Workflow

```
Opportunity
      │
      ▼
Quotation
      │
      ▼
Customer Review
      │
      ▼
Approved
      │
      ▼
Sales Order
```

---

# Navigation

Sales

↓

Quotations

↓

New

---

# Creating a Quotation

Fill the following details:

Customer

ABC Technologies

Quotation Date

Today

Expiration Date

30 Days

Payment Terms

Immediate

Salesperson

Administrator

---

# Customer Information

Customer details include

- Name
- Address
- Phone
- Email
- GST Number

Example

ABC Technologies

Chennai

Tamil Nadu

India

---

# Order Lines

Order Lines contain products being sold.

Example

| Product | Quantity | Unit Price |
|---------|----------|------------|
| Computer | 1 | ₹35,000 |

---

# Product Selection

Products can be

- Storable Products
- Consumables
- Services

Examples

Computer

Printer

Laptop

Odoo ERP Implementation

Training Service

---

# Quantity

Specifies the number of products.

Example

Computer

Quantity

1

---

# Unit Price

Selling price of one product.

Example

₹35,000

---

# Taxes

Taxes are calculated automatically.

Examples

GST 5%

GST 12%

GST 18%

GST 28%

---

# Amount Calculation

Example

Computer

₹35,000

GST

5%

GST Amount

₹1,750

Total

₹36,750

---

# Optional Products

Optional Products help increase sales.

Example

Customer buys

Laptop

Suggest

Laptop Bag

Wireless Mouse

Printer

Monitor

---

# Terms and Conditions

Terms define the business agreement.

Example

- Delivery within 7 working days.
- Payment before delivery.
- One-year warranty.
- Installation included.

These appear on the printed quotation.

---

# Payment Terms

Examples

Immediate

15 Days

30 Days

Advance Payment

---

# Internal Notes

Internal Notes are visible only to company employees.

Example

Customer prefers delivery on Friday.

Needs management approval for discount.

---

# Activities

Activities help salespeople remember follow-ups.

Examples

Call Customer

Email Customer

Arrange Meeting

Product Demo

---

# Send by Email

Quotation can be emailed directly from Odoo.

Benefits

- Faster communication
- Professional PDF quotation
- Easy customer approval

---

# Preview

Preview shows how the quotation will look before printing or emailing.

---

# Print

Print generates a quotation PDF.

Useful for

- Customer copy
- Company records
- Offline sharing

---

# Cancel

Used when

- Customer cancelled purchase.
- Wrong quotation created.
- Duplicate quotation.

---

# Confirm Quotation

After customer approval

Quotation

↓

Sales Order

The quotation becomes a confirmed customer order.

---

# Quotation Status

```
Quotation

↓

Quotation Sent

↓

Sales Order
```

---

# Smart Buttons

Smart buttons display related records.

Examples

- Quotations
- Sales Orders
- Invoices
- Deliveries
- Payments

---

# Chatter

Chatter records communication.

Used for

- Send Message
- Log Note
- Activities
- Attachments

---

# Send Message

Used for communication.

Example

Please review this quotation before sending it to the customer.

---

# Log Note

Internal communication only.

Example

Customer requested delivery on Friday.

---

# Practical Exercise

Create the following quotation.

Customer

ABC Technologies

Product

Computer

Quantity

1

Unit Price

₹35,000

GST

5%

Payment Terms

Immediate

---

Add Terms and Conditions

```
Delivery within 7 working days.
One-year warranty.
Payment before delivery.
```

---

Add Internal Note

```
Customer requested delivery on Friday.
```

---

Schedule Activity

Activity

Call

Summary

Confirm customer approval.

---

Send Quotation by Email.

---

Preview the quotation.

---

Print the quotation.

---

Confirm the quotation.

```
Quotation

↓

Sales Order
```

---

# Quotation Dashboard

Displays

- Total Quotations
- Draft Quotations
- Sent Quotations
- Sales Orders
- Revenue
- Activities

---

# Best Practices

✔ Verify customer details.

✔ Select correct products.

✔ Check pricing carefully.

✔ Apply correct taxes.

✔ Use payment terms.

✔ Add terms and conditions.

✔ Record internal notes.

✔ Schedule follow-ups.

✔ Confirm only after customer approval.

---

# Advantages of Quotation Management

- Professional quotations
- Faster approvals
- Better customer communication
- Accurate pricing
- Automatic tax calculation
- Improved sales efficiency
- Better record keeping
- Higher customer satisfaction

---

# Interview Questions

## What is a Quotation?

A quotation is a formal price offer sent to a customer before confirming a sale.

---

## What is the purpose of a Quotation?

It provides product details, pricing, taxes, and terms before the customer makes a purchase decision.

---

## What is the difference between a Quotation and a Sales Order?

Quotation

Price offer.

Sales Order

Confirmed customer purchase.

---

## Why are Terms and Conditions important?

They define payment, delivery, warranty, and other business rules.

---

## What are Optional Products?

Additional products suggested to increase sales.

---

## Why are Internal Notes used?

To record private information visible only to company employees.

---

## What is the purpose of Activities?

Activities remind salespeople about follow-ups.

---

## What is Preview?

Preview shows how the quotation will appear before printing or sending.

---

## What happens after customer approval?

Quotation is converted into a Sales Order.

---

## Why do businesses use Quotation Management?

To prepare professional quotations, improve customer communication, and increase sales efficiency.

---

# Day 10 Summary

You learned

- Quotation Introduction
- Quotation Workflow
- Customer Information
- Products
- Quantity
- Unit Price
- Taxes
- Payment Terms
- Terms & Conditions
- Optional Products
- Internal Notes
- Activities
- Send by Email
- Preview
- Print
- Confirm Quotation
- Sales Order Conversion
- Best Practices
- Interview Questions

---

## GitHub Commit Message

```text
Day 10: Completed Quotation Management Module with Practical Notes
```

---

# Day 10 Status

**Status:** ✅ Completed

**Next Topic:** Day 11 – Sales Orders & Delivery
