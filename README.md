# 📦 Inventory Management System (IMS) – Business Analysis Case Study

A comprehensive **Business Analysis case study** for designing an Inventory Management System (IMS) for a retail business operating across multiple stores and warehouse units.

## 📌 Project Overview

Retail businesses managing multiple locations and thousands of products can face challenges when inventory movements are tracked manually or when store, warehouse, and sales systems are not interconnected.

This project analyzes these business challenges and defines a structured Inventory Management System designed to improve inventory visibility, stock tracking, replenishment, reporting, and operational efficiency.

The project covers the complete Business Analysis lifecycle, including stakeholder analysis, requirement gathering, Business Requirements Document (BRD), user stories, use cases, wireframes, test cases, acceptance criteria, communication planning, and project timeline.

## 🎯 Business Objectives

The proposed Inventory Management System aims to:

- Provide real-time inventory visibility across stores and warehouse units
- Automate stock updates
- Trigger low-stock alerts
- Support faster stock replenishment
- Improve inventory accuracy
- Improve business decision-making through inventory analytics
- Reduce stock-outs and overstocking
- Improve visibility of product availability across multiple outlets

## 🔍 Business Problem

The existing inventory process presents several challenges:

- Manual stock entry can lead to data entry errors
- Stock levels are not updated in real time
- Recorded inventory may differ from physical stock
- Delayed updates can result in stock-outs
- Replenishment decisions can be delayed
- Store and warehouse inventory visibility is limited

The analysis identifies the need for a centralized Inventory Management System to address these operational challenges.

## 👥 Stakeholder Analysis

The project identifies the following key stakeholders:

| Stakeholder | Role |
|---|---|
| Business Owner / Client | Project sponsor and funding provider |
| IT / Technical Team | Infrastructure and integration support |
| Software Development Team | Develops the IMS features |
| QA & Test Engineers | Testing and quality assurance |
| Store Managers | Manage store-level inventory |
| Warehouse Team | Manage stock storage and movement |
| Sales Team | Process customer purchases |
| Project Manager | Project execution and coordination |
| Customers | Indirect beneficiaries of product availability |

## 📋 Business Requirements

### Business Goals

The proposed IMS should:

- Provide real-time stock visibility
- Automate stock updates
- Trigger low-stock alerts
- Support replenishment
- Provide accurate inventory analytics
- Reduce losses caused by stock-outs and overstocking
- Improve inventory management across multiple stores

### Project Scope

#### In Scope

- Real-time stock tracking and updates
- Low-stock alerts
- Automatic reorder suggestions
- Sales system integration
- Inventory dashboard and KPIs
- Store-to-store stock transfers
- Daily, weekly, and monthly inventory reports

#### Out of Scope

- Mobile application support
- Supplier management automation
- Accounting and finance system integration

## ⚙️ Functional Requirements

The system should be able to:

1. Display real-time stock quantities across stores
2. Trigger alerts when products fall below defined thresholds
3. Automatically deduct stock after sales billing
4. Allow manual stock quantity updates
5. Support barcode scanning
6. Generate and download PDF/CSV reports
7. Maintain stock transaction history
8. Provide inventory dashboards and KPIs
9. Support role-based access and permissions
10. Enable store-to-store stock transfers
11. Suggest reorder quantities using sales trends
12. Support bulk stock uploads through CSV/Excel

## 👤 User Stories

The project includes user stories for key system users.

### Store Manager
> As a store manager, I want to view real-time inventory levels so that I can prevent stock-outs.

### Warehouse Assistant
> As a warehouse assistant, I want to update received stock quickly so that inventory quantities remain accurate.

### Sales Executive
> As a sales executive, I want stock to automatically deduct after billing so that I don't have to update it manually.

### Business Owner
> As a business owner, I want graphical inventory reports so that I can analyze store performance easily.

### System Administrator
> As a system admin, I want to manage user access roles so that sensitive data remains secure.

## 🔄 Use Cases

### 1. Low Stock Alert Generation

**Actors:** Store Manager / System

The system regularly checks product quantities. When inventory falls below the defined threshold, the system generates a low-stock alert and notifies the store manager.

If automatic replenishment is enabled, the system may create a purchase order without requiring a manual alert process.

### 2. Automatic Stock Replenishment

**Actors:** Warehouse Staff / System

When a low-stock condition is identified:

1. The system generates a replenishment request
2. Warehouse staff reviews the request
3. The request is approved
4. Stock is deducted from the warehouse
5. Stock is delivered or assigned to the store
6. Store and warehouse inventory are updated

If the warehouse is out of stock, the request can remain pending or be forwarded to the supplier.

## 🖥️ Functional Prototyping & Wireframes

The project includes two primary wireframes.

### Inventory Dashboard

The dashboard provides a quick overview of:

- Total stock
- Low-stock items
- Out-of-stock items
- Stock value
- Stock trends
- Category distribution
- Inventory KPIs

The dashboard is designed to support quick decision-making and improve inventory visibility.

### Stock Management Interface

The stock management interface supports:

- Product search
- Barcode scanning
- Quantity updates
- Product details
- Reordering
- Stock status monitoring

The interface provides stock status information such as:

- In Stock
- Low Stock
- Out of Stock

## 🧪 Test Cases

The project defines test cases for critical inventory workflows.

### TC-01 — Low Stock Alert

**Scenario:** Verify low-stock alert generation.

**Expected Result:** The system automatically triggers a low-stock alert when quantity falls below the defined threshold.

### TC-02 — Manual Stock Update

**Scenario:** Update inventory through the stock management interface.

**Expected Result:** The new stock quantity is reflected immediately in the system.

### TC-03 — Automatic Stock Deduction

**Scenario:** Process a sale and verify inventory.

**Expected Result:** Inventory quantity is reduced according to the number of units sold.

## ✅ Acceptance Criteria

The system is considered successful when:

- Inventory changes are reflected within the defined time
- Low-stock alerts are triggered at the required threshold
- Inventory calculations are accurate
- Staff can operate the system with minimal training
- Reports and dashboards generate successfully
- Users can access only their assigned features
- Warehouse → Store → Sale → Report workflow operates correctly
- Final UAT approval is received from relevant users

## 📢 Communication Plan

The project defines communication plans for different stakeholder groups.

| Stakeholder | Communication | Frequency |
|---|---|---|
| Business Owner / Client | Progress and risk updates | Weekly |
| Project Manager | Sprint progress and issues | Daily |
| Development Team | Requirements and tasks | Daily / Alternate Days |
| QA Testers | Bug reports and testing feedback | Weekly / Pre-Release |
| Store Managers | Feature demos and feedback | Bi-Weekly |
| Warehouse Team | Training and support | After Deployment |
| Full Team | Final release discussion | Project Completion |

## 📅 Project Timeline

The proposed project follows a **12-week delivery plan**:

| Phase | Timeline |
|---|---|
| Requirement Gathering & Analysis | Week 1–2 |
| Wireframes & UI/UX Design | Week 3–4 |
| Development | Week 5–9 |
| Testing & UAT | Week 10–11 |
| Final Deployment & Handover | Week 12 |

## 📊 Gantt Chart

The project timeline distributes the major phases across the 12-week delivery period:

```text
Requirement Gathering  → Week 1–2
Design / Wireframes    → Week 3–4
Development            → Week 5–9
Testing & UAT          → Week 10–11
Deployment             → Week 12
