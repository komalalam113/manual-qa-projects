# BUG-SaaS-017: User Is Logged Out After Saving Profile Settings

| Field | Details |
| --- | --- |
| Module | Profile Settings |
| Environment | Chrome 137, Windows 11, staging |
| Severity | High |
| Priority | High |
| Status | Open |

## Preconditions

User is logged in with an active session.

## Steps to Reproduce

1. Login with valid credentials.
2. Navigate to Profile.
3. Update the display name.
4. Click Save.

## Expected Result

Profile details are saved and the user remains logged in.

## Actual Result

The session expires immediately and the user is redirected to the login page.
