# Day 4 – Users, Roles & Access Rights

## Learning Objectives

By the end of Day 4, you will be able to:

- Understand Odoo Users
- Create a New User
- Configure User Information
- Understand User Roles
- Assign Security Groups
- Configure Access Rights
- Understand Record Rules
- Assign Multi-Company Access
- Test User Permissions
- Manage User Security

---

# What is a User?

A **User** is a person who can log in to Odoo and perform business operations based on the permissions assigned.

Examples:

- Administrator
- Sales Manager
- Sales Executive
- Accountant
- Inventory Manager
- HR Officer

Each user has a unique login account.

---

# Why User Management?

Every employee in an organization has different responsibilities.

Examples:

- Sales Executive → Sales Module
- Accountant → Accounting Module
- Inventory Manager → Inventory Module
- HR Manager → Employees Module

Odoo ensures users access only the modules required for their work.

---

# Creating a New User

Navigation:

Settings

↓

Users & Companies

↓

Users

↓

New

Enter:

- Name
- Email Address
- Login
- Password
- Language
- Time Zone

Click **Save**.

The new user can now log in to Odoo.

---

# User Information

Each user profile contains:

- Name
- Email Address
- Login
- Password
- Language
- Time Zone
- Company
- Job Position
- User Photo

These settings personalize the user's Odoo experience.

---

# User Types

Odoo provides three user types.

### Internal User

Employees who work inside the organization.

Examples:

- Sales Executive
- Accountant
- HR Officer

---

### Portal User

External users with limited access.

Examples:

- Customers
- Vendors

---

### Public User

Anonymous website visitors.

Example:

Website visitors browsing products.

---

# User Roles

A role defines what a user can do.

Examples:

- Sales User
- Sales Administrator
- Inventory User
- Inventory Administrator
- HR User
- HR Administrator
- Accountant
- Administrator

---

# Security Groups

Security Groups determine which modules and features a user can access.

Examples:

- Sales
- Inventory
- Purchase
- Accounting
- Project
- Employees

A user can belong to one or more groups.

---

# Access Rights

Access Rights determine what actions a user can perform.

Permissions include:

- Read
- Write
- Create
- Delete

Example:

Sales Executive

- Read Quotations
- Create Quotations
- Edit Quotations

Sales Manager

- View All Quotations
- Approve Quotations
- Manage Sales Team

---

# Record Rules

Record Rules determine which records a user can access.

Example:

John Sale

↓

Can view only his own quotations.

Sales Manager

↓

Can view quotations created by all sales executives.

This protects sensitive business information.

---

# Multi-Company Access

Users can work in one or more companies.

Example:

Allowed Companies

- Ravinder Technologies Pvt Ltd
- Ravinder Retail Pvt Ltd

Default Company

- Ravinder Technologies Pvt Ltd

Users can switch companies without logging out.

---

# Company Switching

Navigation:

Top Right Corner

↓

Company Name

↓

Select Company

Example:

Ravinder Technologies Pvt Ltd

↓

Ravinder Retail Pvt Ltd

This allows users to work across multiple companies efficiently.

---

# Testing User Permissions

After creating a user:

- Login using the new account.
- Open the Sales module.
- Create a quotation.
- Verify accessible modules.
- Switch companies.
- Confirm assigned permissions.

Testing ensures the configuration is correct.

---

# Security Best Practices

- Create separate accounts for every employee.
- Assign only the required permissions.
- Use strong passwords.
- Review user access regularly.
- Remove inactive users.
- Restrict Administrator access.

---

# Real-World Example

ABC Group has two companies:

- Ravinder Technologies Pvt Ltd
- Ravinder Retail Pvt Ltd

A new employee, **John Sale**, joins as a Sales Executive.

As an Odoo Functional Consultant, you:

- Create the user.
- Assign Sales access.
- Configure Multi-Company access.
- Test login.
- Create a quotation.
- Verify security groups.
- Verify access rights.
- Verify record rules.

This ensures the employee can work securely within Odoo.

---

# Functional Consultant Responsibility

An Odoo Functional Consultant should know how to:

- Create users
- Configure user profiles
- Assign security groups
- Configure access rights
- Apply record rules
- Assign company access
- Test user permissions
- Train end users
- Ensure business data security

---

# Key Concepts Learned

- Users can log in using individual accounts.
- Security Groups control module access.
- Access Rights control Read, Write, Create, and Delete permissions.
- Record Rules control access to specific records.
- Multi-Company allows users to work in multiple companies.
- User testing verifies that permissions are correctly configured.

---

# Day 4 Summary

Today I learned about **Users, Roles & Access Rights** in Odoo.

I learned how to:

- Create new users
- Configure user information
- Assign user roles
- Configure Security Groups
- Configure Access Rights
- Understand Record Rules
- Assign Multi-Company access
- Test user login
- Create a quotation using a new user
- Switch between companies
- Verify user permissions

Understanding user management and security is one of the most important responsibilities of an **Odoo Functional Consultant**, ensuring employees have the correct access while protecting business data.

---

# Next Topic (Day 5)

**Sales Management**

Topics include:

- CRM Overview
- Leads
- Opportunities
- Customer Management
- Quotations
- Sales Orders
- Sales Workflow
- Customer Invoicing
- Sales Reporting
- Complete Sales Process
