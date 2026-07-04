# BUG-ECOM-001: Completed Order Missing From Order History

| Field | Details |
| --- | --- |
| Module | Order History |
| Environment | Chrome, Windows 11, staging |
| Severity | High |
| Priority | High |
| Status | Open |

## Preconditions

- User is logged in.
- Product is available for purchase.

## Steps to Reproduce

1. Add an available product to the cart.
2. Complete checkout using valid test payment details.
3. Open the user account area.
4. Navigate to order history.

## Expected Result

The completed order appears in order history with correct order number, amount, date, and status.

## Actual Result

The order confirmation page is shown, but the order does not appear in order history.
