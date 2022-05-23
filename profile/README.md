# VCS

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)

The VCS Collection System is used by organizations to allow their people to submit and review documents necessary to comply with government/legal requirements.

## Is VCS for you?

Is your organization looking for a tool to collect employee submitted data/documentation? Are __you__ willing to build, deploy, configure, and support the application for the duration of its use in your organization? If you answered yes to both of the previous questions, then VCS _might_ be the tool for you. Keep reading below to learn more about VCS.

## Background

VCS was created out of necessity when organizations asked for a tool to track COVID-19 vaccination, testing, and recovery records in order to comply with various government mandates.

## Use Case

There are 3 original and distinct use cases for VCS:

1. Vaccination status collection
2. Test result collection
3. Recovery status collection

For each of these use cases, VCS can be configured to send notifications to employees about non-compliant statuses. The resulting submission data can be analyzed to generate organization-wide statistics about compliance that can be helpful when performing risk analysis calculations or making decisions related to RTO (return to office) policies.

## Technical Design Considerations

The system was designed with privacy, security, and scalability in-mind from the start.

VCS was thoroughly evaluated, penetration tested, and load tested (to withstand 1.8M daily active users) on Red Hat's ROSA OpenShift platform.

To give you an idea of the number of users who have interacted with VCS, below are the rough combined submission numbers throughout all VCS deployments as of Q2 2022:

| Type | Unique | Total |
|------|--------|-------|
| Vaccination| 60,000 | 125,000|
| Test | 10,000 | 100,000 |
| Recovery | unavailable | unavailable |

## Deploying VCS

### Local development

Local development instructions for each of the components can be found in the respective repositories:

- [Frontend](https://github.com/VCS-Collection-System/frontend)
- [Backend](https://github.com/VCS-Collection-System/backend)
- [Auto-Approver](https://github.com/VCS-Collection-System/auto-approver)

### Full system deployment

Documentation on how to deploy the entire VCS system is currently minimal. Any contributions in this area would be greatly appreciated.

---

## Misc

### Meet V.C.S.

Victor Charlie Squirrel:

<img src="https://github.com/VCS-Collection-System/.github/raw/main/profile/images/squirrel.png" alt="Victor Charlie Squirrel" width="100"/>
