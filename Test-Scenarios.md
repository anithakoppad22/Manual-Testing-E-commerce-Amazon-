# Test Scenarios – Amazon E-commerce Web Application

---

## Module 1: Application URL / Launch

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_URL_01 | FR-URL-01 | Verify application launches successfully with valid URL |
| TS_URL_02 | FR-URL-02 | Verify application loads over HTTPS |
| TS_URL_03 | FR-URL-03 | Verify application behavior for invalid URL |
| TS_URL_04 | FR-URL-04 | Verify application loads within acceptable time |
| TS_URL_05 | FR-URL-05 | Verify application compatibility with major browsers |

---

## Module 2: User Registration

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_REG_01 | FR-REG-01 | Verify user can register with valid details |
| TS_REG_02 | FR-REG-02 | Verify registration with already registered email |
| TS_REG_03 | FR-REG-03 | Verify mandatory field validation during registration |
| TS_REG_04 | FR-REG-04 | Verify password complexity rules |
| TS_REG_05 | FR-REG-05 | Verify confirm password mismatch validation |
| TS_REG_06 | FR-REG-06 | Verify mobile number validation |
| TS_REG_07 | FR-REG-07 | Verify successful account creation message |

---

## Module 3: Login Functionality

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_LOGIN_01 | FR-LOGIN-01 | Verify login with valid email and valid password |
| TS_LOGIN_02 | FR-LOGIN-02 | Verify login with valid email and invalid password |
| TS_LOGIN_03 | FR-LOGIN-03 | Verify login with invalid email and valid password |
| TS_LOGIN_04 | FR-LOGIN-04 | Verify login with invalid email and invalid password |
| TS_LOGIN_05 | FR-LOGIN-05 | Verify login with empty email and password fields |
| TS_LOGIN_06 | FR-LOGIN-06 | Verify error message for incorrect login credentials |
| TS_LOGIN_07 | FR-LOGIN-07 | Verify password field is masked |
| TS_LOGIN_08 | FR-LOGIN-08 | Verify login button functionality |
| TS_LOGIN_09 | FR-LOGIN-09 | Verify “Forgot Password” link functionality |
| TS_LOGIN_10 | FR-LOGIN-10 | Verify user is redirected to login page when accessing protected pages |
| TS_LOGIN_11 | FR-LOGIN-11 | Verify user can logout successfully |
| TS_LOGIN_12 | FR-LOGIN-12 | Verify session timeout after inactivity |

---

## Module 4: Product Search & Browse

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_SEARCH_01 | FR-SEARCH-01 | Verify product search using valid keyword |
| TS_SEARCH_02 | FR-SEARCH-02 | Verify product search using invalid keyword |
| TS_SEARCH_03 | FR-SEARCH-03 | Verify search result when no product is found |
| TS_SEARCH_04 | FR-SEARCH-04 | Verify product search using partial keyword |
| TS_SEARCH_05 | FR-SEARCH-05 | Verify search suggestions / auto-complete |
| TS_SEARCH_06 | FR-SEARCH-06 | Verify browsing products by category |
| TS_SEARCH_07 | FR-SEARCH-07 | Verify product listing pagination |

---

## Module 5: Product Details Page

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_PDP_01 | FR-PDP-01 | Verify product details page loads correctly |
| TS_PDP_02 | FR-PDP-02 | Verify product name, price, and description |
| TS_PDP_03 | FR-PDP-03 | Verify product images and zoom functionality |
| TS_PDP_04 | FR-PDP-04 | Verify availability / stock status |
| TS_PDP_05 | FR-PDP-05 | Verify product ratings and reviews |
| TS_PDP_06 | FR-PDP-06 | Verify similar / recommended products |

---

## Module 6: Add to Cart

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_CART_01 | FR-CART-01 | Verify product can be added to cart |
| TS_CART_02 | FR-CART-02 | Verify updating product quantity in cart |
| TS_CART_03 | FR-CART-03 | Verify removing product from cart |
| TS_CART_04 | FR-CART-04 | Verify cart total price calculation |
| TS_CART_05 | FR-CART-05 | Verify cart persistence after logout/login |

---

## Module 7: Checkout & Address Management

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_CHK_01 | FR-CHK-01 | Verify user can proceed to checkout |
| TS_CHK_02 | FR-CHK-02 | Verify login is required before checkout |
| TS_CHK_03 | FR-CHK-03 | Verify adding a new delivery address |
| TS_CHK_04 | FR-CHK-04 | Verify mandatory address field validation |
| TS_CHK_05 | FR-CHK-05 | Verify selecting existing address |

---

## Module 8: Payment

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_PAY_01 | FR-PAY-01 | Verify payment using Credit/Debit Card |
| TS_PAY_02 | FR-PAY-02 | Verify payment using UPI |
| TS_PAY_03 | FR-PAY-03 | Verify Cash on Delivery option |
| TS_PAY_04 | FR-PAY-04 | Verify payment failure handling |
| TS_PAY_05 | FR-PAY-05 | Verify secure payment processing |

---

## Module 9: Order Confirmation

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_ORD_01 | FR-ORD-01 | Verify order confirmation after successful payment |
| TS_ORD_02 | FR-ORD-02 | Verify unique order ID generation |
| TS_ORD_03 | FR-ORD-03 | Verify order details in confirmation page |
| TS_ORD_04 | FR-ORD-04 | Verify order appears in My Orders |

---

## Module 10: Order Tracking & Cancellation

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_TRACK_01 | FR-TRACK-01 | Verify order tracking status |
| TS_TRACK_02 | FR-TRACK-02 | Verify order cancellation before shipment |
| TS_TRACK_03 | FR-TRACK-03 | Verify cancellation confirmation message |
| TS_TRACK_04 | FR-TRACK-04 | Verify refund initiation after cancellation |

---

## Module 11: Non-Functional Requirements

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS_NFR_01 | NFR-PERF-01 | Verify page load performance |
| TS_NFR_02 | NFR-SEC-01 | Verify password masking |
| TS_NFR_03 | NFR-SEC-02 | Verify session timeout |
| TS_NFR_04 | NFR-COMP-01 | Verify browser compatibility |
| TS_NFR_05 | NFR-USE-01 | Verify usability and error messages |

---
