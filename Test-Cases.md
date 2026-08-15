Test Cases — E-Commerce Website

1. Login Testing

TC ID| Test Case| Preconditions| Test Steps| Expected Result| Actual Result| Status
TC-LOGIN-001| Login with valid credentials| Login page is accessible| Enter valid username and password, then click Login| User should be logged in successfully| Products page displayed successfully| Pass
TC-LOGIN-002| Login with invalid username| Login page is accessible| Enter invalid username and valid password, then click Login| Appropriate error message should be displayed| Error message displayed| Pass
TC-LOGIN-003| Login with invalid password| Login page is accessible| Enter valid username and invalid password, then click Login| Appropriate error message should be displayed| Error message displayed| Pass
TC-LOGIN-004| Login with empty username| Login page is accessible| Leave username empty and enter password| Username validation message should be displayed| Validation message displayed| Pass
TC-LOGIN-005| Login with empty password| Login page is accessible| Enter username and leave password empty| Password validation message should be displayed| Validation message displayed| Pass
TC-LOGIN-006| Login with both fields empty| Login page is accessible| Leave username and password empty, then click Login| Required field validation should be displayed| Validation message displayed| Pass
TC-LOGIN-007| Login with invalid credentials| Login page is accessible| Enter invalid username and invalid password| Login should be rejected with an error message| Login rejected and error message displayed| Pass

2. Product Testing

TC ID| Test Case| Preconditions| Test Steps| Expected Result| Actual Result| Status
TC-PROD-001| View product details| Products page is accessible| Open a product| Product name, price and details should be displayed correctly| Product details displayed correctly| Pass
TC-PROD-002| Add product to cart| Product is available| Click Add to Cart| Product should be added to the cart| Product added to cart successfully| Pass
TC-PROD-003| Remove product from cart| Product is already in cart| Open cart and click Remove| Product should be removed from the cart| Product removed successfully| Pass
TC-PROD-004| Verify product price| Products page is accessible| Open product and observe price| Correct product price should be displayed| Product price displayed correctly| Pass

3. Cart Testing

TC ID| Test Case| Preconditions| Test Steps| Expected Result| Actual Result| Status
TC-CART-001| Verify added product in cart| Product has been added| Open cart| Added product should be displayed with correct details and price| Product details and price displayed correctly| Pass
TC-CART-002| Continue shopping after removing product| Product is in cart| Remove product and select Continue Shopping| User should be returned to the product/shop page| User returned to products page| Pass
TC-CART-003| Verify empty cart| Cart is accessible| Remove all products from cart| Cart should display no selected products| Cart displayed without selected product| Pass
TC-CART-004| Verify cart product details| Product is in cart| Open cart and review product information| Product name and price should be displayed correctly| Product information displayed correctly| Pass
TC-CART-005| Remove product from cart| Product is in cart| Click Remove| Selected product should be removed| Product removed successfully| Pass
TC-CART-006| Add multiple products to cart| Products are available| Add more than one product| Selected products should be added to the cart| Products added successfully| Pass
TC-CART-007| Verify cart count| Product is available| Add a product and observe cart icon| Cart count should update correctly| Cart count updated correctly| Pass
TC-CART-008| Verify cart after re-login| User has selected products| Log out and log in again| Cart should retain products according to application behavior| Cart behavior verified successfully| Pass

4. Checkout Testing

TC ID| Test Case| Preconditions| Test Steps| Expected Result| Actual Result| Status
TC-CHECKOUT-001| Validate required checkout information| Product is in cart| Proceed to checkout and leave required fields empty| Required field validation should be displayed| Required field validation displayed| Pass
TC-CHECKOUT-002| Complete checkout with valid information| Product is in cart| Enter valid checkout information and continue| User should proceed successfully through checkout| Checkout completed successfully| Pass
TC-CHECKOUT-003| Verify order confirmation| Checkout information is valid| Complete the checkout process| Order confirmation should be displayed| Order confirmation displayed| Pass
TC-CHECKOUT-004| Validate postal code field| Checkout page is accessible| Enter postal code information and continue| Postal code should be validated according to requirements| Behavior verified and documented| Pass

5. Test Execution Summary

Metric| Result
Total Test Cases| 20
Passed| 20
Failed| 0
Overall Status| Passed

6. Evidence

Test execution evidence is available in the "Test-Evidence" folder.

Evidence was grouped where the same screenshot supported multiple related test cases.

7. Defect Reference

Potential defect identified during testing:

BUG-001 — Postal Code Validation

The defect is documented separately in "Bug-Reports.md" (Bug-Reports.md).
