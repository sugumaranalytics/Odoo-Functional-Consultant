# Day 3 – Multi-Company Management

## Learning Objectives

By the end of Day 3, you will be able to:

- Understand Multi-Company Management
- Create a New Company
- Configure Company Information
- Assign Users to Companies
- Set Default Company
- Configure Allowed Companies
- Switch Between Companies
- Understand Company-Specific Data
- Understand Shared Records
- Manage Multiple Companies Efficiently

---

# What is Multi-Company?

Multi-Company is an Odoo feature that allows multiple companies to operate within a single Odoo database.

Each company maintains its own business data while sharing the same Odoo installation.

Example:

- ABC Supermarket
- ABC Textile Store
- ABC Electronics

---

# Why Multi-Company?

Many organizations own multiple businesses.

Instead of installing separate ERP systems, Odoo allows all companies to be managed from one database.

Benefits:

- One Login
- One Database
- Lower Maintenance Cost
- Centralized Management
- Easy Company Switching

---

# Company Information

Each company has its own information.

Examples:

- Company Name
- Address
- Phone Number
- Email
- Website
- Currency
- Tax ID (GST/VAT)
- Company Logo

This information appears in quotations, invoices, purchase orders, and reports.

---

# Creating a New Company

Navigation:

Settings

↓

Users & Companies

↓

Companies

↓

New

Enter:

- Company Name
- Address
- Contact Details
- Currency
- Tax Information

Click **Save**.

---

# User Access

Each user can be assigned to one or more companies.

User Configuration:

- Default Company
- Allowed Companies
- User Role
- Access Rights

This ensures users only access the companies assigned to them.

---

# Default Company

The Default Company is automatically selected when the user logs in.

Example:

Employee Default Company:

**ABC Supermarket**

The user starts working in this company after login.

---

# Allowed Companies

Users may have permission to work in multiple companies.

Example:

Sales Manager

Allowed Companies:

- ABC Supermarket
- ABC Textile Store

Managers can switch between these companies whenever required.

---

# Company Switcher

The Company Switcher allows users to change the active company.

Navigation:

Top Right Corner

↓

Company Name

↓

Select Company

No logout is required.

---

# Company-Specific Data

Each company maintains separate business records.

Examples:

- Customers
- Vendors
- Sales Orders
- Purchase Orders
- Warehouses
- Inventory
- Accounting
- Taxes
- Financial Reports

Data from one company does not affect another company.

---

# Shared Records

Some records can be shared between companies.

Examples:

- Products
- Customer Contacts

Sharing common records avoids duplicate data entry.

---

# Access Rights

Odoo controls user access through permissions.

Examples:

Employee

- ABC Supermarket

Sales Manager

- ABC Supermarket
- ABC Textile Store

Administrator

- All Companies

This improves security and data privacy.

---

# Real-World Example

ABC Group owns:

- ABC Supermarket
- ABC Textile Store
- ABC Electronics

Using Multi-Company:

- One Odoo Database
- One Login
- Separate Accounting
- Separate Inventory
- Separate Reports
- Easy Company Switching

Each company works independently while using the same ERP system.

---

# Benefits of Multi-Company

- Centralized Business Management
- Better Security
- Separate Financial Records
- Separate Inventory
- Reduced Software Cost
- Easy Business Expansion
- Improved Productivity

---

# Best Practices

- Create companies before users.
- Assign the correct Default Company.
- Give users only the required company access.
- Verify the active company before creating transactions.
- Configure accounting separately for each company.

---

# Functional Consultant Responsibility

A Functional Consultant should know:

- How to create companies
- How to configure company information
- How to assign users
- How to manage company access
- How to explain company switching
- How to maintain data separation
- How to implement Multi-Company for business requirements

---

# Day 3 Summary

Today I learned about **Multi-Company Management** in Odoo.

I learned how to:

- Create multiple companies
- Configure company information
- Assign users to companies
- Set Default and Allowed Companies
- Switch between companies
- Manage company-specific data
- Share common records
- Configure user access
- Support organizations with multiple businesses using a single Odoo database

Multi-Company Management helps businesses manage multiple organizations efficiently while keeping each company's data secure and independent.

---

# Next Topic

**Day 4 – User Preferences**

Topics include:

- User Profile
- Language
- Time Zone
- Notifications
- Password Management
- Email Signature
- Account Security
- Personal Preferences
