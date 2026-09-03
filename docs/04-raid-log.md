# RAID Log

## Purpose

The RAID log provides a central record of project Risks, Assumptions, Issues and Dependencies.

It is reviewed regularly throughout delivery to ensure that threats to scope, schedule, quality and release readiness are identified early, assigned to an appropriate owner and actively managed.

## RAID Definitions

| Type | Definition |
|---|---|
| Risk | An uncertain event that may affect the project in the future |
| Assumption | Something currently believed to be true for planning purposes |
| Issue | A problem that has already occurred and requires action |
| Dependency | Something the project relies on in order to progress |

---

## Risks

| ID | Risk | Probability | Impact | Owner | Mitigation | Status |
|---|---|---|---|---|---|---|
| R-01 | External stakeholder approval of requirements may be delayed | Medium | High | Project Manager | Schedule early review sessions and track outstanding approvals | Closed – requirements approved in Week 2 |
| R-02 | UAT participants may have limited availability during the planned testing window | Medium | High | Project Manager | Confirm participants in advance and identify backup representatives | Closed – materialised as I-01 and resolved |
| R-03 | Development may take longer than estimated due to unforeseen technical complexity | Medium | High | Technical Lead | Review estimates early and monitor progress against milestones | Closed – development completed in Week 6 |
| R-04 | Defects identified during QA or UAT may threaten release readiness | Medium | High | QA Lead | Prioritise defects by severity and maintain sufficient time for resolution and retesting | Closed – testing completed with no blocking defects |
| R-05 | Late scope changes may affect the fixed delivery timeline | Medium | High | Product Owner | Apply formal change control and assess schedule impact before approval | Closed – CR-01 delivered without moving the release milestone |
---

## Assumptions

| ID | Assumption | Owner | Validation | Status |
|---|---|---|---|---|
| A-01 | Required development resources will remain available throughout delivery | Project Manager | Confirm resource allocation with Technical Lead | Validated |
| A-02 | External stakeholders will participate in requirements validation and UAT | Project Manager | Confirm named representatives and availability | Validated |
| A-03 | Existing platform architecture can support the required change without major redesign | Technical Lead | Confirm through technical assessment | Validated |
| A-04 | Required test environments will be available according to the delivery plan | QA Lead | Confirm environment schedule before QA begins | Validated |

---

## Issues

| ID | Issue | Impact | Owner | Resolution Action | Status |
|---|---|---|---|---|---|
| I-01 | Primary external UAT representative became unavailable during the planned UAT window | Potential delay to UAT completion and sign-off | Project Manager | Activate backup participant, confirm availability and reschedule affected UAT scenarios within Week 8 | Resolved |

---

## Dependencies

| ID | Dependency | Required By | Owner | Impact if Delayed | Status |
|---|---|---|---|---|---|
| D-01 | Requirements approval from Product and relevant external stakeholders | Week 2 | BA / Product Owner | Development start may be delayed | Complete |
| D-02 | Technical assessment and delivery estimate | Week 2 | Technical Lead | Development plan cannot be confirmed | Complete |
| D-03 | Test environment availability | Week 6 | QA Lead | QA and UAT milestones may be delayed | Complete |
| D-04 | External stakeholder availability for UAT | Week 8 | Project Manager | UAT sign-off may be delayed | Complete |
| D-05 | UAT sign-off | Week 8 | Product Owner | Release readiness approval cannot complete | Complete |
| D-06 | Operational readiness confirmation | Week 9 | Operations | Production release cannot proceed | Complete |

---

## RAID Review Process

The RAID log will be reviewed during the weekly project status meeting.

The Project Manager will:

- Review existing RAID items and confirm whether their status has changed
- Identify new risks, assumptions, issues or dependencies
- Confirm that each active item has an appropriate owner
- Track agreed mitigation or resolution actions
- Review target dates for time sensitive items
- Escalate items where the potential impact exceeds the project team's authority
- Close items when they no longer require active management

## Risk Escalation

A RAID item should be considered for escalation when it:

- Threatens a key project milestone
- Could affect the fixed regulatory deadline
- Requires a decision outside the project team's authority
- Has a significant impact on scope or quality
- Remains unresolved beyond its agreed target date
- Requires additional resources or senior stakeholder intervention

Escalation does not transfer ownership of the problem away from the project team. It ensures that the appropriate level of management has visibility and can support resolution.

## Final RAID Summary

**Overall RAID Status: Green**

All identified project risks have been closed following successful completion of delivery.

Risk R-02 materialised as issue I-01 when the primary external UAT representative became unavailable. A backup participant was confirmed and the affected UAT scenarios were completed within Week 8.

Risk R-05 was actively monitored following approval of CR-01 because the additional scope reduced schedule contingency. The change was successfully delivered without moving the Week 10 production release milestone.

All project assumptions were validated and all identified dependencies were satisfied.

There are no unresolved project issues or dependencies requiring further action.

The project proceeded to successful production release in Week 10 and formal closure in Week 11.
The project can proceed to the Week 9 release readiness review.
