# User Acceptance Testing (UAT)

## Purpose

These test cases verify that the Student Registration System meets the agreed requirements.

| Test ID | Scenario | Expected Result | Status |
|---|---|---|---|
| UAT01 | Student views available modules | Available modules are displayed | Not Tested |
| UAT02 | Student selects a module without meeting prerequisites | System displays an eligibility warning | Not Tested |
| UAT03 | Student selects modules with a timetable clash | System displays a timetable clash warning | Not Tested |
| UAT04 | Student selects valid modules | Modules are added successfully | Not Tested |
| UAT05 | Student removes a selected module | Module is removed successfully | Not Tested |
| UAT06 | Student submits valid registration | Registration is successfully submitted | Not Tested |
| UAT07 | Student completes registration | Confirmation is displayed | Not Tested |
| UAT08 | Academic advisor views a student's registration | Student's selected modules are displayed | Not Tested |

## UAT Success Criteria

The system will be considered ready for implementation when:

- All critical test cases pass.
- No critical registration errors remain.
- Prerequisite checks work correctly.
- Timetable clash detection works correctly.
- Students can successfully submit valid registrations.
- Registration confirmation is provided.
