# ISO 27001 Annex A vs NIST SP 800-53 Control Mapping

This document provides a comparative reference between ISO/IEC 27001:2022 Annex A controls and NIST SP 800-53 Rev. 5 controls. It helps organizations that operate in regulated environments or are preparing for dual-framework audits.

---

## Overview

| ISO 27001:2022 Control | Description (ISO)                                  | Mapped NIST 800-53 Controls |
|------------------------|-----------------------------------------------------|-----------------------------|
| A.5.1 Policies for ISMS | Establishment of management direction and support  | PM-1, PL-1, PL-2             |
| A.5.7 Threat Intelligence | Collecting and analyzing cyber threat information | IR-4, CA-2, RA-5             |
| A.5.23 Cloud Services   | Security for use of cloud services                 | AC-20, SA-9, SR-3            |
| A.6.1 Access Control    | Identity and access control policies               | AC-1, AC-2, AC-3, AC-5       |
| A.6.4 Privileged Access | Management of admin privileges                     | AC-6, AC-17, IA-2            |
| A.7.4 Physical Security | Protecting physical premises                       | PE-1, PE-2, PE-3             |
| A.8.9 Configuration Mgmt | Baselines and change control                      | CM-2, CM-3, CM-6             |
| A.8.16 Monitoring       | Security event and operations monitoring           | AU-6, AU-12, SI-4            |
| A.8.26 Continuity       | Planning for operational continuity                | CP-1 through CP-10           |
| A.8.28 Recovery Planning | Recovery of operations after incidents            | IR-4, CP-10, IR-8            |
| A.5.30 Third Parties    | Security in third-party relationships              | SR-1 through SR-9, SA-9      |

---

## Key Similarities

- **Risk-Based Approach**: Both standards emphasize risk assessment and control selection based on risk.
- **Control Families**: ISO groups controls by themes. NIST organizes into control families (AC, AU, IR, PE, etc.), but both emphasize access, auditing, monitoring, and continuity.
- **Documentation and Governance**: Each requires formal policies, implementation evidence, and review cycles.

---

## Key Differences

| Area | ISO 27001 | NIST 800-53 |
|------|-----------|-------------|
| Prescriptiveness | High-level, outcome-oriented | Granular, control-specific |
| Industry Usage | Global, broad industries | U.S. Federal and regulated industries |
| Certification | Formal ISO certification possible | No direct certification, but audit evidence required |
| Scope | Focused on ISMS and related risks | Broad coverage including privacy, personnel, systems, and supply chain |

---

## Use Cases for Mapping

- Bridging ISO-based and FedRAMP/NIST-based compliance requirements
- Demonstrating alignment for SOC 2 + ISO 27001 dual audits
- Developing unified GRC dashboards and control libraries
- Supporting crosswalk tables for audit readiness

---

## References

- [ISO/IEC 27001:2022](https://www.iso.org/standard/82875.html)
- [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [NIST 800-53 Control Catalog](https://csrc.nist.gov/Projects/risk-management/sp800-53-controls)

*This mapping is for educational and planning use only. Always consult a certified auditor or compliance expert before relying on mappings for assessments.*

