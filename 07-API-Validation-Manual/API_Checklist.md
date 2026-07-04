# API Checklist

| ID | Check | Expected Result | Status |
| --- | --- | --- | --- |
| API-001 | Authenticated GET request | Returns 200 and expected response body | Pass |
| API-002 | POST with valid payload | Creates record and returns created response | Pass |
| API-003 | POST with missing required field | Returns validation error | Pass |
| API-004 | PUT with valid payload | Updates record successfully | Pass |
| API-005 | DELETE existing record | Deletes record or marks it inactive | Pass |
| API-006 | Request without token | Returns 401 unauthorized | Pass |
| API-007 | Invalid endpoint | Returns clear 404 response | Pass |
