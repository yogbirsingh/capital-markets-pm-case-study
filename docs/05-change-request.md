# Change Request — CR-01

## Change Summary

| Field | Detail |
|---|---|
| Change ID | CR-01 |
| Title | Addition of supplementary reference-data field |
| Requested By | External Financial Institution |
| Date Raised | Week 3 |
| Priority | Medium |
| Status | Approved |
| Decision Owner | Product Owner |

## Background

Following approval of the original regulatory reference data requirements, an external financial institution requested that an additional reference data field be included within the planned change.

The requested field was not included within the requirements approved at the end of Week 2.

As development has already entered its planned delivery window, the request requires formal assessment before being added to project scope.

## Requested Change

Add one supplementary reference data field to the existing regulatory data output.

The requesting institution believes the additional field would improve its ability to integrate the regulatory dataset with its internal reporting processes.

The request does not change the underlying regulatory deadline.

## Initial Project Manager Response

The request will not be added directly to the delivery backlog until its impact has been assessed.

The Project Manager will coordinate an impact assessment involving:

- Product Owner
- Business Analyst
- Technical Lead
- QA
- Relevant external stakeholder

The assessment will consider:

- Business value
- Regulatory relevance
- Requirements impact
- Development effort
- Testing effort
- Dependencies
- Delivery schedule
- UAT impact
- Release risk

## Impact Assessment

### Business Analysis

The Business Analyst confirmed that the additional field can be incorporated through an amendment to the existing requirements.

No fundamental change to the agreed business process is required.

**Impact: Low**

### Product

The Product Owner confirmed that the additional field provides sufficient stakeholder value to justify consideration within the current release.

The change remains aligned with the purpose of the regulatory data service.

**Impact: Low**

### Technical

The Technical Lead estimated that implementation would require approximately two additional development days.

No architectural redesign is required.

**Impact: Medium**

### QA

QA confirmed that existing test cases will require updating and additional validation will be required for the new field.

The additional testing can be incorporated within the current QA window provided development completes within the revised internal target.

**Impact: Medium**

### UAT

The additional field will be included within the existing UAT scenarios.

No extension to the planned Week 8 UAT window is currently required.

**Impact: Low**

## Schedule Impact

The additional development effort uses part of the contingency available within the delivery plan.

Development remains forecast to complete within Week 6.

QA, UAT and the Week 10 production release remain achievable.

The regulatory deadline is therefore **not currently forecast to be affected**.

## Risk Assessment

Accepting the change reduces available schedule contingency.

This increases the impact of any subsequent development or testing delays.

Risk `R-05 — Late scope changes may affect the fixed delivery timeline` was monitored throughout delivery and was closed following successful completion of the Week 10 production release.

## Decision

**Decision: APPROVED**

The Product Owner approved the change for inclusion in the current release following review of the impact assessment.

Approval is conditional on:

- No change to the Week 10 production-release target
- Updated requirements being documented
- Development estimate being incorporated into delivery tracking
- QA test coverage being updated
- Any subsequent scope changes being assessed separately

## Actions

| Action | Owner | Target | Status |
|---|---|---|---|
| Update requirements to include additional field | Business Analyst | Week 3 | Complete |
| Update development estimate | Technical Lead | Week 3 | Complete |
| Add implementation work to delivery board | Project Manager | Week 3 | Complete |
| Update QA test coverage | QA Lead | Week 4 | Complete |
| Include new field within UAT scenarios | BA / QA | Week 7 | Complete |
| Monitor reduced schedule contingency | Project Manager | Ongoing | Closed – release completed as planned 

## Project Status Following Decision

**Overall project status: Green**

The change has been approved and can currently be accommodated without moving a key project milestone.

However, schedule contingency has been reduced.

Any further scope increase or delivery delay will require careful assessment against QA, UAT and the fixed production release target.
