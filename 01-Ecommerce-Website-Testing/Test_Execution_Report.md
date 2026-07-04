# Test Execution Report: E-commerce Website

## Summary

| Metric | Count |
| --- | ---: |
| Total Test Cases | 7 |
| Passed | 6 |
| Failed | 1 |
| Blocked | 0 |
| Deferred | 0 |
| Pass Percentage | 85.7% |

## Defect Summary

| Defect ID | Severity | Status | Summary |
| --- | --- | --- | --- |
| BUG-ECOM-001 | High | Open | Completed order is missing from order history after checkout. |

## Risks

- Order history defect may impact customer trust and support volume.
- Payment gateway behavior should be revalidated in a controlled staging environment.

## Recommendation

Proceed only after order history synchronization is fixed or formally accepted as a known release risk.
