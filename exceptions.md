# Exceptions

## Purpose
This file documents approved control exceptions and any compensating controls used in the sample NIST control mapping project.

## Exception Management Rules
- Every exception should have an owner.
- Every exception should have a clear justification.
- Every exception should have a defined scope.
- Every exception should have an expiry or review date.
- Every exception should include compensating controls when needed.
- Exceptions should be reviewed regularly so they do not become permanent by accident.

## Exception Table

| Exception ID | Control ID | Exception Title | Scope | Justification | Compensating Controls | Owner | Approver | Expiry Date | Review Cadence | Related Risk | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|
| E-01 | CM-2 | Baseline configuration not yet formalized | Sample system baseline only | The baseline document has not been fully completed yet. | Manual configuration review and change approval process. | Infrastructure Team | Project Owner | 2026-09-30 | Monthly | R-04 | Open |
| E-02 | IA-2 | MFA evidence limited for sample users | Selected sample accounts | MFA is enabled, but the repo only contains limited proof for some users. | Identity provider MFA enforcement and sign-in monitoring. | IAM Team | Project Owner | 2026-08-30 | Monthly | R-03 | Open |

## Notes
Exceptions in this repository are portfolio examples and are meant to show how exceptions are tracked, reviewed, and tied back to risk.
