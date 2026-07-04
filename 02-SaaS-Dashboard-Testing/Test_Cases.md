# Test Cases: SaaS Dashboard

| Test Case ID | Module | Scenario | Steps | Expected Result | Status |
| --- | --- | --- | --- | --- | --- |
| TC-SaaS-001 | Login | User logs in with valid credentials | Open login page, enter credentials, submit | User lands on dashboard | Pass |
| TC-SaaS-002 | Roles | Viewer cannot access admin settings | Login as viewer and open admin settings URL | Access is denied | Pass |
| TC-SaaS-003 | Dashboard | Widgets load current metrics | Login and view dashboard | Widgets display expected data and labels | Pass |
| TC-SaaS-004 | CRUD | Create new record | Open records page, add required fields, save | New record appears in list | Pass |
| TC-SaaS-005 | Reports | Export report | Select report filters and click export | Report downloads successfully | Pass |
| TC-SaaS-006 | Settings | Save profile changes | Edit profile name and save | Profile updates without ending session | Fail |
