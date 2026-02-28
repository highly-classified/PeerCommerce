# PeerCommerce  
### Campus Talent & Micro-Business Exchange Portal  

PeerCommerce is a university-based digital commerce ecosystem built using **Zoho Creator (Low-Code Platform)**.  

The platform enables students to:
- Offer paid services (skills)
- Sell physical or digital products
- Book peer services
- Purchase products
- Manage wallet-based transactions
- Track financial activity via ledger
- Automate workflows and notifications
- Use AI-based classification and prediction
- Operate through a secure student portal

This application was developed as part of a Low-Code Application Development coursework project.

---

# 1. Problem Statement

Universities have multiple student talents and micro-businesses, but there is no structured internal platform to:

- Monetize peer skills  
- Track service lifecycle  
- Maintain financial transparency  
- Manage inventory-based student businesses  
- Automate booking and approval processes  

PeerCommerce solves this by creating a structured, governed internal campus commerce ecosystem.

---

# 2. Core Features

## 2.1 User Management

- Role-based student profiles (Buyer / Service Provider / Product Seller)
- Wallet balance tracking
- Account approval workflow (Blueprint)
- Portal-based authentication

---

## 2.2 Service Marketplace

Students can:
- List services with pricing
- Book peer services
- Track booking lifecycle

### Includes:
- Auto cost calculation
- Wallet validation before booking
- Automated ledger entry
- Email notifications
- Scheduled reminders

### Blueprint Lifecycle:

Requested → Accepted → In Progress → Completed → Closed

---

## 2.3 Product Marketplace

Students can:
- List products
- Manage stock
- Process multi-item orders

### Includes:
- Subform-based order items
- Auto stock deduction
- Auto wallet debit/credit
- Conditional formatting for low stock
- Seller notification for pending orders

### Blueprint Lifecycle:

Placed → Confirmed → Packed → Delivered → Closed



---

## 2.4 Wallet & Ledger System

A centralized Transaction Ledger ensures:

- Full financial traceability
- Automatic wallet update via workflows
- Credit/Debit classification
- Source tracking (Service / Product / Refund)

This guarantees financial governance within the ecosystem.

---

# 3. Automation & Workflows

## Form Workflows
- Auto fetch provider details
- Cost calculation
- Wallet validation
- Stock verification
- Ledger auto-entry

## Scheduled Workflows
- Booking reminder 1 day before service
- Seller notification if order pending > 24 hours

## Email Notifications
- Booking confirmation
- Order delivery confirmation
- Account approval
- Reminder alerts

---

# 4. Blueprint (Business Process Automation)

Blueprint ensures structured lifecycle control:

- Service Booking Blueprint  
- Product Order Blueprint  
- User Approval Blueprint  

This guarantees controlled stage transitions and role-based action restrictions.

---

# 5. AI Model Integration

AI features implemented:

- Service category prediction based on description
- Product demand prediction based on past sales

AI fields are trained and deployed using Zoho Creator AI models.

---

# 6. Reports & Analytics

Implemented reports:

- Active Services Report
- Earnings by Provider
- Product Sales Report
- Wallet Summary
- Booking Kanban View
- Conditional Formatting (Low stock / Cancelled records)

## Dashboard Includes:
- Total Users
- Total Revenue
- Active Services
- Top Providers
- Revenue trends

Designed to integrate with Zoho Analytics for advanced BI.

---

# 7. Portal Configuration

- Secure student login
- Role-based access
- Restricted financial data visibility
- Self-registration with domain restriction (if enabled)
- Permission sets configured per user type

---

# 8. Technical Architecture

**Platform:** Zoho Creator  
**Type:** Low-Code Application  
**Architecture Style:** Relational Form-Based with Workflow Automation  

## Key Components:

- Forms with Lookup Relationships (One-to-Many)
- Subforms (Parent-Child structure)
- Deluge scripting for business logic
- Workflow engine (Form + Scheduled)
- Blueprint engine
- Portal framework
- AI model framework
- Reporting & Dashboard engine

---

# 9. Database Schema Overview

### Major Forms:

- User Profile  
- Transaction Ledger  
- Service Listing  
- Service Booking  
- Product Listing  
- Product Order (with Order Items Subform)  

### Relationships:

- User → Services (1:M)  
- User → Bookings (1:M)  
- User → Orders (1:M)  
- Service → Bookings (1:M)  
- Product → Order Items (1:M)  
- User → Ledger (1:M)  

---

# 10. Deployment

- Application deployed in Zoho Creator Live Mode.
- Portal enabled for student access.

**Portal URL:**  
https://peercommerce.zohocreatorportal.in/


---

# 11. How to Use

1. Open Portal URL.
2. Register using university email.
3. Await admin approval (if enabled).
4. Login and explore:
   - List Service
   - Book Service
   - Add Product
   - Place Order
   - View Wallet

---

# 12. Learning Outcomes Demonstrated

This project demonstrates practical understanding of:

- Low-code application development
- Data relationships using lookup fields
- Subform modeling
- Workflow automation
- Conditional validation logic
- Scheduled processes
- Blueprint-based business process modeling
- Financial ledger implementation
- AI model training and usage
- Portal configuration and governance
- Dashboard and reporting systems

---

