# Risk Register

## Purpose
This register tracks risks identified from the NIST control mapping exercise and documents assessment, ownership, and treatment.

## Scoring Guide
- Likelihood: 1 = Rare, 2 = Unlikely, 3 = Possible, 4 = Likely, 5 = Almost certain.
- Impact: 1 = Low, 2 = Minor, 3 = Moderate, 4 = Major, 5 = Critical.
- Score = Likelihood × Impact.

## Risk Table

| Risk ID | Risk Title | Description | Category | Root Cause | Inherent Likelihood | Inherent Impact | Inherent Score | Controls in Place | Residual Likelihood | Residual Impact | Residual Score | Response Strategy | Treatment & Next Action | Owner | Trigger / Indicator | Review Date | Status |
|---|---|---|---|---|---:|---:|---:|---|---:|---:|---:|---|---|---|---|---|---|
| R-01 | Incomplete account lifecycle evidence | Evidence for account provisioning, approval, and deprovisioning is incomplete for the sample system. | Compliance | Missing documentation and incomplete artifact collection. | 3 | 3 | 9 | Basic account request process documented; IAM in place. | 2 | 3 | 6 | Mitigate | Collect approval records, add deprovisioning logs, and schedule quarterly access reviews. | Security Team | Access review overdue; new user onboarding without approval. | 2026-10-01 | Open |
| R-02 | Insufficient log review evidence | Log configuration exists, but log review records and tuning evidence are missing. | Operational / Compliance | Logging is enabled, but review evidence is not being retained. | 3 | 4 | 12 | Logging enabled; SIEM forwarding configured. | 2 | 3 | 6 | Mitigate | Export sample logs, add a documented log-review checklist, and implement weekly review signoff. | IT Ops / SOC | No log-review entry for more than 30 days. | 2026-09-15 | Open |
| R-03 | Limited MFA evidence | MFA enforcement evidence is incomplete for certain user groups. | Security / Compliance | Identity provider settings are not fully documented and exceptions exist. | 4 | 5 | 20 | MFA available in identity provider; some users exempted. | 3 | 4 | 12 | Mitigate | Produce MFA enrollment report, remove unnecessary exemptions, and require MFA for privileged roles. | IAM Team | Privileged account detected without MFA enabled. | 2026-08-30 | Open |
| R-04 | Baseline configuration not documented | No approved, versioned baseline configuration exists for the sample system. | Configuration Management | Baseline has not been formally defined or stored. | 4 | 3 | 12 | Standard hardening guidance exists but is not formalized. | 2 | 2 | 4 | Mitigate | Create baseline document, store it in the repo, and link it to change control and drift detection. | Infrastructure Team | New deployment without baseline reference. | 2026-09-30 | Planned |
| R-05 | Evidence freshness risk | Some evidence is placeholder content or older than the desired review window. | Documentation / Compliance | Evidence collection is incomplete and not yet maintained on a schedule. | 3 | 3 | 9 | Some artifacts are dated; placeholders are labeled. | 2 | 2 | 4 | Mitigate | Replace placeholders with recent exports or screenshots and add evidence review dates. | Project Owner | Evidence older than 12 months. | 2026-10-15 | Open |

## Notes
- Inherent score is the risk level before considering current controls.
- Residual score is the remaining risk after current controls are considered.
- Open risks should be reviewed regularly and updated as supporting evidence improves.
- Closed risks should include closure evidence and a final review date.
