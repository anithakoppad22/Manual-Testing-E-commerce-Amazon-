Software Requirements Specification (SRS)
E-commerce Web Application (Amazon – Manual Testing Project)
1. Introduction

 1.1 Purpose
 The purpose of this document is to describe the functional and non-functional requirements of an E-commerce Web Application (Amazon).
 This SRS is used as a reference for manual testing, test case creation, and defect identification.

1.2 Scope
The application allows users to:
Browse products
Search and filter items
Add products to cart
Place orders
Make payments
Track orders

This document focuses on end-user functionalities from a tester’s perspective.

1.3 Intended Audience
Manual Test Engineers
QA Team
Developers
Project Managers

2. Overall Description
2.1 Product Overview
The system is a web-based e-commerce platform similar to Amazon that enables customers to purchase products online.

2.2 User Classes
User Type	Description
Guest User	Can browse and search products
Registered User	Can place orders and make payments
Admin	Manages products and orders (out of scope for testing)

2.3 Operating Environment
Web Browser: Chrome, Firefox, Edge
OS: Windows, macOS
Internet connection required

3. Functional Requirements

3.1 User Registration & Login
User should be able to register using email and password
User should be able to login with valid credentials
System should display error message for invalid login

3.2 Product Search & Browse
User should be able to search products by keyword
User should be able to view product details
User should be able to filter products by category, price, rating

3.3 Add to Cart
User should be able to add product to cart
User should be able to update quantity
User should be able to remove product from cart

3.4 Checkout & Address
User should be able to add delivery address
User should be able to select saved address
System should validate mandatory address fields

3.5 Payment
User should be able to select payment method:
Credit/Debit Card
UPI
Cash on Delivery (if applicable)
System should display payment success or failure message

3.6 Order Confirmation
System should generate order ID
User should receive order confirmation message
Order should be visible in “My Orders”

3.7 Order Tracking & Cancellation
User should be able to track order status
User should be able to cancel order before shipment

4. Non-Functional Requirements
4.1 Performance
Pages should load within 3 seconds
Search results should appear quickly

4.2 Usability
Application should be user-friendly
Clear error messages should be displayed

4.3 Security
Password should be masked
Payment details should be encrypted
Unauthorized access should be restricted

4.4 Compatibility
Application should work on major browsers
Responsive design for different screen sizes

5. Assumptions & Constraints
User has active internet connection
Payment gateway is available
Admin functionalities are not tested

6. Testable Requirements Summary
All functional requirements will be validated through manual test cases
Defects will be logged based on deviations from this SRS

7. Conclusion
This SRS document serves as the baseline for manual testing activities including test scenario creation, test case execution, and defect reporting for the Amazon E-commerce web application.
