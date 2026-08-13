# Bug Reports — E-Commerce Website

## BUG-001 — Postal Code Field Accepts Invalid Characters

### Summary
The Postal Code field accepts letters and special characters during checkout.

### Module
Checkout

### Severity
Medium

### Priority
Medium

### Preconditions
User is logged in and has a product in the cart.

### Steps to Reproduce
1. Login to the application.
2. Add a product to the cart.
3. Open the cart and proceed to checkout.
4. Enter a valid First Name.
5. Enter a valid Last Name.
6. Enter `!!!@@@` in the Postal Code field.
7. Click Continue.

### Expected Result
If the requirement specifies a numeric-only postal code, the application should reject invalid characters and display an appropriate validation message.

### Actual Result
The application accepts `!!!@@@` as the Postal Code and allows the user to continue.

### Status
New

### Evidence
Screenshot captured during test execution.

### Note
The defect should be confirmed against the application's documented Postal Code validation requirement before being classified as a confirmed bug.
