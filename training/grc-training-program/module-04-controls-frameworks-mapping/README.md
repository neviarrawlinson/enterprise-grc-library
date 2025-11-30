# Module 4: Controls, Frameworks, and Mapping

## Objective
Understand how controls support compliance, how to use popular frameworks, and how to map controls across different standards like ISO 27001, NIST 800-53, and SOC 2.

## What You'll Learn
- What is a control and why it matters
- Types of controls: Preventive, Detective, Corrective
- Overview of major frameworks (ISO 27001, NIST 800-53, SOC 2, HIPAA)
- How to map controls across frameworks
- Introduction to Control Libraries and Matrices

---

## Section 1: What is a Control?

A **control** is a safeguard or countermeasure designed to reduce risk or ensure compliance.

### Types of Controls
| Type       | Description                                 | Example                                 |
|------------|---------------------------------------------|-----------------------------------------|
| Preventive | Stop incidents before they occur            | Firewalls, MFA, access controls         |
| Detective  | Identify incidents after they occur         | Logging, IDS, alerting systems          |
| Corrective | Respond to or fix incidents post-occurrence | Incident response, backups, patching    |

---

## Section 2: Control Frameworks Overview

| Framework     | Focus                     | Audience            |
|---------------|---------------------------|---------------------|
| ISO 27001     | Information Security (global) | Enterprises worldwide |
| NIST 800-53   | Federal systems, high assurance | U.S. Government + regulated industries |
| SOC 2         | Trust Services Criteria    | SaaS, startups, B2B platforms |
| HIPAA         | Healthcare security/privacy | U.S. healthcare and providers |

Each framework defines its own **control categories** (e.g., Access Control, Change Management, Asset Management).

---

## Section 3: Control Mapping

Why map controls?
- Reduces duplication of effort
- Simplifies audits across multiple standards
- Builds unified compliance strategies

### Example: ISO 27001 vs NIST 800-53 Mapping

| ISO 27001 Control | Description                       | NIST 800-53 Control |
|-------------------|-----------------------------------|---------------------|
| A.9.2.3           | Management of privileged access   | AC-6, AC-17         |
| A.12.4.1          | Logging and monitoring            | AU-2, AU-6          |
| A.14.1.2          | Secure transmission of data       | SC-12, SC-13        |

Refer to: `control-mapping/iso27001-annex-a-vs-nist-800-53.md`

---

## Section 4: Control Libraries

A **Control Library** is a master list of all active controls used in your organization. It typically includes:
- Control ID
- Description
- Framework Source
- Control Owner
- Status (Implemented, Not Started, In Progress)
- Last Reviewed
- Evidence Location

✅ You will create one in Module 6

---

## Section 5: Activities and Exercises

✅ Activity: Choose a control from ISO 27001 and find its NIST equivalent

✅ Activity: Review your org’s policy and identify if each control is:
- Preventive
- Detective
- Corrective

✅ Group Exercise: Create a simple matrix showing overlap across 2-3 frameworks

---

## Practice Assignment

Build a basic Control Mapping Table using:
- ISO 27001 Annex A
- NIST 800-53 (or SOC 2)

Document 5 controls and their equivalents, including control descriptions.

---

## Summary

Control frameworks are the foundation of GRC. Mastery of how to evaluate, map, and organize controls across frameworks is key to building scalable, audit-ready programs.

---

## Resources

- [ISO 27001 Annex A Controls Overview](https://www.iso.org/standard/75652.html)
- [NIST 800-53 Catalog](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [AICPA SOC 2 Trust Criteria](https://www.aicpa.org/topic/audit-assurance/soc)
- [HIPAA Security Rule Summary](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html)

