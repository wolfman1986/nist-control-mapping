# Methodology

## Purpose
This file explains how control status, evidence, and risk were evaluated in this NIST control mapping project, and which authoritative NIST sources were used to build the repo.

## Authoritative Sources
The project was based on official NIST publications and NIST-hosted control mapping resources, including:
- NIST SP 800-53 Rev. 5, Security and Privacy Controls for Information Systems and Organizations.
- NIST SP 800-53A Rev. 5, Assessing Security and Privacy Controls in Information Systems and Organizations.
- NIST SP 800-53B, Control Baselines for Information Systems and Organizations.
- NIST OSCAL Control Mapping Model documentation.
- NIST IR 8477, Mapping Relationships Between Documentary Standards, Regulations, Frameworks, and Guidelines.
- NIST IR 8286A, Identifying and Estimating Cybersecurity Risk for Enterprise Risk Management.

## How The Sources Were Used
- SP 800-53 Rev. 5 was used as the main control catalog for the sample control set.
- SP 800-53A Rev. 5 informed how evidence and assessment thinking were organized.
- SP 800-53B was used to understand baseline and tailoring context.
- OSCAL documentation informed how to think about control relationships, mappings, and traceability.
- IR 8477 informed how to think about mappings between standards, frameworks, and guidelines.
- IR 8286A informed the risk register structure, including likelihood, impact, and risk treatment.

## Status Definitions
- **Implemented**: The control is supported by documented evidence.
- **In Progress**: Some implementation or evidence exists, but it is not complete.
- **Planned**: The control has been identified, but implementation has not started.
- **Exception**: The control is not fully met, but a compensating control or temporary workaround exists.

## Risk Scoring Method
- **Likelihood**: 1 = Rare, 2 = Unlikely, 3 = Possible, 4 = Likely, 5 = Almost certain.
- **Impact**: 1 = Low, 2 = Minor, 3 = Moderate, 4 = Major, 5 = Critical.
- **Score**: Likelihood × Impact.
- **Inherent Risk**: Risk level before current controls are considered.
- **Residual Risk**: Risk level after current controls are considered.

## Evaluation Approach
Each control and risk was reviewed using the following questions:
- Is there a clear control requirement in the authoritative source?
- Is there evidence that the control exists?
- Is the evidence current and relevant?
- Are there gaps or exceptions?
- Is a compensating control needed?
- What is the likely impact if the gap remains open?

## Evidence Rules
- Evidence should be tied to the specific control.
- Evidence should be easy to identify and review.
- Placeholder evidence is acceptable for a portfolio project, but it should be labeled clearly.
- Control status and risk status should reflect the evidence available in the repo.

## Notes
This methodology is intended for a portfolio demonstration and not as a formal audit procedure.
