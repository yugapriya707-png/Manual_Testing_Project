# Test Plan — ShopLite
**Version:** 1.0 | **Type:** Sample training document

## Objective
Validate the main customer workflows and identify defects before release.

## Scope
In scope: authentication, product search, cart operations, checkout and order confirmation.
Out of scope: payment-provider certification, load testing, penetration testing and third-party integrations.

## Test approach
Functional, negative, boundary, usability, compatibility smoke and regression testing. Use equivalence partitioning and boundary-value analysis for input validation.

## Environment
Windows 11, Chrome (latest stable), staging build 1.0.4, test account and sandbox payment data.

## Entry criteria
Build deployed; requirements available; test environment reachable; test data prepared.
## Exit criteria
All critical cases executed; no open critical defects; high defects dispositioned; regression completed; summary approved.

## Risks
Unstable staging environment, incomplete test data, third-party payment outage. Mitigate with environment checks, controlled data and documented blockers.

## Deliverables
Scenarios, test cases, execution log, defect reports and test summary report.