# Exploratory Testing Notes

## Charter 1: Form Validation

Goal: Explore required fields, invalid formats, boundary values, and unclear error messages.

Findings:

- Required field validation appears consistently.
- Email format validation works.
- Long text inputs should be tested further for truncation and layout behavior.

## Charter 2: Session Handling

Goal: Explore timeout behavior, browser refresh, duplicate tabs, and back-button behavior after logout.

Findings:

- User is redirected to login after timeout.
- Back button does not expose authenticated content after logout.
- Timeout warning message could be clearer.

## Charter 3: File Upload

Goal: Explore allowed file types, file size limits, upload progress, and error messages.

Findings:

- Valid PDF and PNG files upload successfully.
- Unsupported file type returns a generic message.
- File size limit should be shown before upload.
