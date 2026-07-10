# Day 15 Assignment – Inventory Basics

**Course:** Odoo Functional Consultant (30 Days)  
**Day:** 15  
**Module:** Inventory  
**Topic:** Inventory Basics  
**Status:** ✅ Completed

---



---

# Part A – Multiple Choice Questions (MCQ)

## Q1. Which module is used to manage stock in Odoo?

A. CRM

B. Sales

C. Inventory

D. Accounting

### Answer

**C. Inventory**

---

## Q2. What is the default storage location inside a warehouse?

A. Vendors

B. WH/Stock

C. Customers

D. Scrap

### Answer

**B. WH/Stock**

---

## Q3. Which operation is used to receive products from a vendor?

A. Delivery Order

B. Internal Transfer

C. Receipt

D. Manufacturing

### Answer

**C. Receipt**

---

## Q4. Which product type is used for physical products?

A. Service

B. Goods

C. Combo

D. Subscription

### Answer

**B. Goods**

---

## Q5. What happens after validating a Receipt?

A. Customer receives invoice

B. Stock decreases

C. Warehouse stock increases

D. Purchase Order is deleted

### Answer

**C. Warehouse stock increases**

---

# Part B – Fill in the Blanks

## Q1.

Inventory stores products inside a __________.

### Answer

**Warehouse**

---

## Q2.

Products received from suppliers are stored in __________.

### Answer

**WH/Stock**

---

## Q3.

Incoming products arrive from __________.

### Answer

**Vendors**

---

## Q4.

The actual available stock is called __________ Quantity.

### Answer

**On Hand**

---

## Q5.

Inventory tracking is enabled using the __________ option.

### Answer

**Track Inventory**

---

# Part C – True or False

## Q1.

Goods products can be tracked in Inventory.

### Answer

**True**

---

## Q2.

Services maintain warehouse stock.

### Answer

**False**

---

## Q3.

A Purchase Order is created before receiving products.

### Answer

**True**

---

## Q4.

WH/Input is the customer location.

### Answer

**False**

---

## Q5.

Bill Matching compares Purchase Order, Receipt and Vendor Bill.

### Answer

**True**

---

# Part D – Short Answer Questions

## Q1. What is Inventory?

### Answer

Inventory is the process of managing products, stock quantities, warehouse operations, receipts, deliveries, and stock movements within a company.

---

## Q2. What is a Warehouse?

### Answer

A warehouse is a physical location where products are stored, received, and delivered.

---

## Q3. What is WH/Stock?

### Answer

WH/Stock is the main storage location where products are available after they are received into the warehouse.

---

## Q4. What is Track Inventory?

### Answer

Track Inventory enables Odoo to maintain stock quantities, stock movements, and inventory history for a product.

---

## Q5. What is a Receipt?

### Answer

A Receipt is an inventory operation used to receive products from vendors into the warehouse.

---

# Part E – Difference Between

## Q1. Goods vs Service

| Goods | Service |
|--------|---------|
| Physical product | Non-physical service |
| Inventory tracked | Inventory not tracked |
| Stored in warehouse | Not stored in warehouse |
| Example: Mouse | Example: Installation |

---

## Q2. On Hand vs Forecasted Quantity

| On Hand | Forecasted |
|----------|------------|
| Actual stock available | Expected future stock |
| Physical quantity | Includes incoming and outgoing movements |
| Updated after receipt | Changes based on orders |

---

## Q3. Vendor vs Customer

| Vendor | Customer |
|----------|----------|
| Supplies products | Purchases products |
| Sends goods | Receives goods |
| Creates Purchase Orders | Creates Sales Orders |

---

# Part F – Practical Questions

## Q1.

Create a new Goods product.

### Answer

Created Product:

- Product Name: Wireless Mouse
- Product Type: Goods
- Track Inventory: Enabled
- Sales Price: ₹450
- Cost: ₹350

---

## Q2.

Create a Purchase Order.

### Answer

Purchase Order Details:

- PO Number: P00008
- Vendor: Kumar Industries
- Product: Wireless Mouse
- Quantity: 100
- Unit Price: ₹350

---

## Q3.

Receive the purchased products.

### Answer

Receipt validated successfully.

Products moved from:

Partners/Vendors

↓

WH/Stock

---

## Q4.

What is the On Hand Quantity after receiving products?

### Answer

**100 Units**

---

## Q5.

What is the Forecasted Quantity after receiving products?

### Answer

**100 Units**

---

# Part G – Real Business Scenario

## Scenario

ABC Technologies purchased 100 Wireless Mouse units from Kumar Industries at ₹350 each.

Answer the following:

### 1. Which document is created first?

### Answer

Request for Quotation (RFQ)

---

### 2. Which document is created after confirmation?

### Answer

Purchase Order

---

### 3. Which operation updates warehouse stock?

### Answer

Receipt Validation

---

### 4. Where are products stored?

### Answer

WH/Stock

---

### 5. What is the total Purchase Order value?

### Calculation

100 × ₹350

= ₹35,000

### Answer

**₹35,000**

---

# Part H – Workflow Question

Draw the Purchase Workflow.

### Answer

```text
Vendor
   │
   ▼
Request for Quotation (RFQ)
   │
   ▼
Purchase Order
   │
   ▼
Receipt
   │
   ▼
WH/Stock
   │
   ▼
Inventory Updated
```

---

# Part I – Interview Questions

## Q1. What is Inventory?

### Answer

Inventory is the process of managing stock, warehouses, receipts, deliveries, and inventory movements.

---

## Q2. What is a Receipt?

### Answer

A Receipt records incoming goods from vendors into the warehouse.

---

## Q3. What is On Hand Quantity?

### Answer

The actual physical stock available in the warehouse.

---

## Q4. What is Forecasted Quantity?

### Answer

The expected stock after considering incoming and outgoing inventory operations.

---

## Q5. What is Bill Matching?

### Answer

Bill Matching verifies that the Purchase Order, Goods Receipt, and Vendor Bill match before payment is made to the vendor.

---

# Practical Work Completed

| Task | Status |
|------|--------|
| Inventory Dashboard | ✅ |
| Warehouse Configuration | ✅ |
| Warehouse Locations | ✅ |
| Operation Types | ✅ |
| Product Creation | ✅ |
| Track Inventory Enabled | ✅ |
| Purchase Order Created | ✅ |
| Receipt Validated | ✅ |
| On Hand Quantity Verified | ✅ |

---

# Assignment Summary

During this assignment, I learned the complete Inventory Basics workflow in Odoo. I configured and explored warehouse settings, understood warehouse locations and operation types, created a Goods product with inventory tracking, created a Purchase Order, received products from the vendor, validated the receipt, and verified that the warehouse stock was updated correctly. I also learned the concepts of On Hand Quantity, Forecasted Quantity, and Bill Matching.

---

# Assignment Status

**Day 15 Assignment:** ✅ Completed

**Score:** ______ /100
