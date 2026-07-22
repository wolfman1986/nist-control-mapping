# NIST Control Mapping

This repository demonstrates a NIST control mapping exercise for a sample system. It shows how security controls can be organized, traced to evidence, and reviewed for gaps.

The goal of this project is to present a practical GRC artifact that shows control traceability, implementation status, and supporting evidence.

## Scope

This repository uses a sample system to demonstrate NIST control mapping.

### In Scope
- One example information system.
- A small set of NIST SP 800-53 Rev. 5 controls.
- Control status, evidence, and gap tracking.

### Out of Scope
- Full enterprise assessment.
- Certification or formal audit readiness.
- All NIST controls and families.

## Control Matrix

| Control ID | Control Name | Status | Evidence | Owner |
|---|---|---|---|---|
| AC-2 | Account Management | In Progress | evidence/ac-2.md | Security Team |
| AU-2 | Event Logging | Implemented | evidence/au-2.md | IT Operations |
| CM-2 | Baseline Configuration | Planned | evidence/cm-2.md | Infrastructure Team |
| IA-2 | Identification and Authentication | Implemented | evidence/ia-2.md | IAM Team |
| IR-4 | Incident Handling | In Progress | evidence/ir-4.md | SOC Team |

## Evidence and Gaps

### Evidence
- `evidence/ac-2.md` — Account management example evidence.
- `evidence/au-2.md` — Logging example evidence.
- `evidence/ia-2.md` — Authentication example evidence.
- `evidence/ir-4.md` — Incident response example evidence.

### Gaps
- Some controls are still in progress.
- Some evidence is only a placeholder.
- This project is a demonstration, not a full audit package.

## Usage

Review the control matrix, evidence files, and gap analysis to understand how the sample NIST mapping is organized.

## License

This project is for portfolio and educational purposes.
