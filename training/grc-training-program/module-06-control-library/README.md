# Module 6: Building a Control Library

## Objective
Understand how to structure, maintain, and map controls in a centralized control library aligned to GRC frameworks like ISO 27001, NIST, and SOC 2.

---

## What You'll Learn

- What is a control library and why it matters
- Control types: preventive, detective, corrective
- Mapping controls to frameworks (ISO, NIST, SOC 2)
- Structuring your library in tools like Confluence, Excel, or GRC platforms
- Keeping controls up to date

---

## Section 1: What Is a Control Library?

A **control library** is a centralized collection of technical, administrative, and physical controls your organization uses to manage risks and maintain compliance.

Each control in your library should include:

- Unique ID
- Control title
- Description
- Control owner
- Frequency
- Associated policies/procedures
- Mapped frameworks or standards

---

## Section 2: Types of Controls

| Type         | Description                                 | Example                             |
|--------------|---------------------------------------------|-------------------------------------|
| Preventive   | Stop threats before they happen             | MFA, firewall, access provisioning  |
| Detective    | Identify or alert when something occurs     | Logging, SIEM alerts, audit logs    |
| Corrective   | Minimize impact and recover from incidents  | Backup restores, patch management   |

---

## Section 3: Framework Mapping

Mapping your controls to external frameworks helps demonstrate compliance. Examples:

| Control ID | Control Title           | ISO 27001 | NIST CSF | SOC 2 |
|------------|--------------------------|-----------|-----------|--------|
| CL-001     | User Access Reviews      | A.9.2.5   | PR.AC-4  | CC6.1 |
| CL-002     | Security Awareness Training | A.7.2.2 | PR.AT-1  | CC1.4 |

👉 View examples in the [control-mapping](../../control-mapping) folder.

---

## Section 4: Control Library Tools

Common ways to manage your control library:

- **Confluence or SharePoint** — Easy for collaboration
- **Excel or Google Sheets** — Simple and flexible
- **GRC platforms** — Built-in libraries and mapping (e.g., AuditBoard, Anecdotes, Tugboat Logic)

### Sample Format:

| ID | Title | Description | Owner | Frequency | Frameworks | Last Reviewed |
|----|-------|-------------|-------|-----------|------------|----------------|
| CL-001 | Access Reviews | Ensure user access is reviewed quarterly | IT Security | Quarterly | ISO, NIST | 2025-06-01 |

---

## Section 5: Keeping Your Library Current

- Assign review dates and owners
- Set calendar reminders
- Review controls during audits and major incidents
- Archive outdated controls

---

## Section 6: Activities

✅ Create a 5-control mini library in markdown or Excel  
✅ Try mapping 3 controls to both ISO and NIST  
✅ Identify whether your controls are preventive, detective, or corrective  
✅ Link one control to an existing policy or SOP

---

## Summary

Your control library is the foundation of GRC maturity. A well-maintained control inventory helps streamline audits, align with frameworks, and reduce risk.

---

## Resources

- [NIST CSF Controls Reference](https://www.nist.gov/cyberframework)
- [ISO 27001 Annex A Control List](https://advisera.com/27001academy/knowledgebase/iso-27001-annex-a-controls/)
- [How to Build a Control Library](https://medium.com/@neviarrawlinson/how-to-set-up-a-control-library-for-it-governance-32591a3a81ef)
- [Control Mapping Samples](../../control-mapping)
