# Test Cases: E-commerce Website

| Test Case ID | Module | Scenario | Steps | Expected Result | Status |
| --- | --- | --- | --- | --- | --- |
| TC-ECOM-001 | Registration | Register with valid data | Open registration page, enter valid details, submit form | Account is created and user is signed in or redirected to login | Pass |
| TC-ECOM-002 | Login | Login with invalid password | Enter valid email with incorrect password | Error message is shown and user remains logged out | Pass |
| TC-ECOM-003 | Search | Search existing product | Enter product keyword and submit search | Matching products are displayed | Pass |
| TC-ECOM-004 | Cart | Update item quantity | Add product to cart, increase quantity, view total | Quantity and cart total update correctly | Pass |
| TC-ECOM-005 | Coupon | Apply expired coupon | Enter expired coupon during checkout | Coupon is rejected with a clear message | Pass |
| TC-ECOM-006 | Checkout | Complete checkout with missing address | Leave required address fields blank and continue | Required field validation is displayed | Pass |
| TC-ECOM-007 | Order History | View completed order | Complete test order and open order history | Latest order appears with correct status | Fail |
