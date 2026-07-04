# Accessibility Report

## Summary

The application is generally usable with keyboard navigation and assistive technology, but focus visibility and low-contrast disabled controls require remediation.

## Key Findings

| ID | Severity | Finding | Recommendation |
| --- | --- | --- | --- |
| A11Y-FOCUS-001 | High | Secondary buttons do not show a visible focus state. | Add a clear focus outline that meets contrast requirements. |
| A11Y-CONTRAST-001 | Medium | Disabled button text has insufficient contrast. | Increase contrast while preserving disabled state styling. |

## Recommendation

Fix high-impact keyboard and contrast issues before release, then rerun accessibility checks against affected screens.
