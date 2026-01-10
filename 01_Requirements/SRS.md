# Software Requirements Specification (SRS)
## E-commerce Web Application – Amazon

---

## 1. Introduction

### 1.1 Purpose
This document describes the functional and non-functional requirements of an
Amazon-like e-commerce web application. It serves as a reference for
manual testing, test scenario creation, and defect reporting.

---

### 1.2 Scope
The application allows users to:
- Browse and search products
- View product details
- Add products to cart
- Place orders and make payments
- Track and cancel orders

---

## 2. Overall Description

### 2.1 Product Overview
The system is a web-based e-commerce platform that enables users to purchase
products online through a secure and user-friendly interface.

---

### 2.2 User Classes

| User Type | Description |
|----------|-------------|
| Guest User | Can browse and search products |
| Registered User | Can place orders and make payments |
| Admin | Manages products and orders (out of testing scope) |

---

### 2.3 Operating Environment
- Web Browsers: Chrome, Firefox, Edge
- Operating Systems: Windows, macOS
- Internet connection required

---

## 3. Functional Requirements

### 3.1 User Registration & Login
- User should be able to register using valid email and password
- User should be able to login with valid credentials
- System should display error message for invalid login attempts
- User should be able to logout successfully

---

### 3.2 Product Search & Browse
- User should be able to search products using keywords
- User should be able to browse products by category
- Product details page should display correct information
- System should handle no-result search scenarios

---

### 3.3 Add to Cart
- User should be able to add products to cart
- User should be able to update product quantity
- User should be able to remove products from cart
- Cart should display correct total price

---

### 3.4 Checkout & Address Management
- User should be able to proceed to checkout after login
- Mandatory address fields should be validated
- User should be able to select or add a delivery address

---

### 3.5 Payment
- User should be able to select payment method:
  - Credit/Debit Card
  - UPI
  - Cash on Delivery (if applicable)
- System should display payment success or failure message

---

### 3.6 Order Confirmation
- System should generate a unique order ID
- Order confirmation message should be displayed
- Order details should be visible in “My Orders”

---

### 3.7 Order Tracking & Cancellation
- User should be able to track order status
- User should be able to cancel order before shipment
- System should display cancellation confirmation

---

## 4. Non-Functional Requirements

### 4.1 Performance
- Pages should load within 3 seconds
- Search results should be displayed quickly

---

### 4.2 Usability
- Application should be user-friendly
- Error messages should be clear and meaningful

---

### 4.3 Security
- Password fields should be masked
- Payment data should be encrypted
- Unauthorized access should be restricted

---

### 4.4 Compatibility
- Application should work on major browsers
- Application should be responsive on different screen sizes

---

## 5. Assumptions & Constraints
- User has an active internet connection
- Payment gateway availability is assumed
- Admin functionalities are not tested

---

## 6. Conclusion
This SRS document serves as the baseline for manual testing activities,
including test scenario creation, test case execution, and defect reporting
for the Amazon e-commerce web application.



