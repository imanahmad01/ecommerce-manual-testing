
# Test Cases — E-Commerce Website

## 1. Login

| TC ID | Test Case | Preconditions | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC-LOGIN-001 | Login with valid credentials | Registered user exists | Enter valid username and password, then click Login | User should be logged in successfully | To be tested | Not Run |
| TC-LOGIN-002 | Login with invalid username | Login page is accessible | Enter invalid username and valid password, then click Login | Appropriate error message should be displayed | To be tested | Not Run |
| TC-LOGIN-003 | Login with invalid password | Login page is accessible | Enter valid username and invalid password, then click Login | Appropriate error message should be displayed | To be tested | Not Run |
| TC-LOGIN-004 | Login with empty username | Login page is accessible | Leave username empty, enter password, then click Login | Username validation message should be displayed | To be tested | Not Run |
| TC-LOGIN-005 | Login with empty password | Login page is accessible | Enter username, leave password empty, then click Login | Password validation message should be displayed | To be tested | Not Run |

## 2. Product

| TC ID | Test Case | Preconditions | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC-PROD-001 | View product details | Products page is accessible | Open a product | Product name, price and details should be displayed correctly | To be tested | Not Run |
| TC-PROD-002 | Add product to cart | Product is available | Click Add to Cart | Product should be added to the cart | To be tested | Not Run |
| TC-PROD-003 | Remove product from cart | Product is already in cart | Open cart and click Remove | Product should be removed from the cart | To be tested | Not Run |

## 3. Cart

| TC ID | Test Case | Preconditions | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC-CART-001 | Verify added product in cart | Product has been added | Open cart | Added product should be displayed with correct details and price | To be tested | Not Run |
| TC-CART-002 | Continue shopping after removing product | Product is in cart | Remove product and select Continue Shopping | User should be returned to the product/shop page | To be tested | Not Run |

## Test Execution

Test execution results will be updated after performing the test cases on the selected e-commerce web application.
