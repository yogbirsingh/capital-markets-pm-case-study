# User Acceptance Testing (UAT) Plan

## Purpose

This document defines the approach for coordinating User Acceptance Testing (UAT) for the regulatory reference data change.

UAT will confirm that the delivered changes meet the agreed business requirements and are suitable for production release.

## UAT Scope

UAT will validate:

- Approved regulatory reference data requirements
- Existing functionality affected by the change
- Supplementary reference data field introduced through CR-01
- Expected business outputs
- Relevant validation and error handling behaviour

## Participants

| Role | Responsibility |
|---|---|
| Project Manager | Coordinate UAT, track progress, actions and blockers |
| Product Owner | Confirm business acceptance and approve UAT outcome |
| Business Analyst | Clarify requirements and support scenario validation |
| QA Lead | Support defect investigation and testing evidence |
| Technical Lead | Coordinate technical investigation and fixes where required |
| External Stakeholders | Execute agreed UAT scenarios and provide feedback |

## Entry Criteria

UAT can begin when:

- System and integration testing is complete
- No unresolved blocking QA defects remain
- UAT scenarios have been prepared
- UAT environment is available
- External participants are confirmed
- CR-01 functionality is available for testing

## UAT Scenarios

| ID | Scenario | Expected Result | Status |
|---|---|---|---|
| UAT-01 | Validate standard reference data submission | Submission processed successfully | Not Started |
| UAT-02 | Validate required regulatory data fields | Required fields processed correctly | Not Started |
| UAT-03 | Validate supplementary field introduced by CR-01 | New field accepted and returned correctly | Not Started |
| UAT-04 | Validate submission with invalid data | Appropriate validation response returned | Not Started |
| UAT-05 | Validate existing functionality after change | Existing functionality remains unaffected | Not Started |

## Defect Management

Any defects identified during UAT will be recorded and assessed according to severity.

| Severity | Definition | Response |
|---|---|---|
| Critical | Prevents completion of UAT or creates unacceptable business impact | Immediate escalation and resolution required |
| High | Significant functionality affected with no acceptable workaround | Prioritise before UAT sign-off |
| Medium | Functionality affected but workaround exists | Assess impact on release decision |
| Low | Minor issue with limited business impact | May be scheduled for later resolution |

The Project Manager will track defects, owners, target dates and impact on the release schedule.

## Sign-Off Criteria

UAT will be considered complete when:

- Required UAT scenarios have been executed
- Results have been recorded
- No Critical or High defects remain unresolved
- Remaining defects have been assessed and accepted where appropriate
- Outstanding actions are documented
- Product Owner and relevant stakeholders confirm business acceptance
- UAT sign-off is recorded

## Planned Timeline

UAT is scheduled for **Week 8**.

Successful UAT completion is required before the project proceeds to the Week 9 release readiness review and Week 10 production release.

## Current Status

**UAT Status: Planned**

UAT preparation is progressing in line with the delivery plan.
