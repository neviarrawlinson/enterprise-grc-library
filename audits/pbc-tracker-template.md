# PBC (Provided By Client) Tracker Template

This template helps teams manage and track documentation or evidence requests during audits, assessments, or internal reviews. It ensures accountability, version control, and timely responses for every required item.

---

## Purpose

The PBC (Provided By Client) Tracker serves as a centralized system for:

- Managing incoming evidence requests
- Assigning ownership to internal stakeholders
- Recording submission dates and status
- Tracking file locations and notes for compliance and audit readiness

---

## Tracker Fields and Definitions

| **Field**                 | **Description**                                                                 |
|--------------------------|---------------------------------------------------------------------------------|
| **Request ID**           | Unique identifier for each item (e.g., PBC-001, PBC-002)                        |
| **Request Description**  | Description of the evidence or information being requested                      |
| **Requested On**         | Date the request was received                                                   |
| **Assigned To**          | Team member responsible for providing the requested item                        |
| **Status**               | Current status: Open, In Progress, Submitted, Approved, Rejected, Not Applicable |
| **Due Date**             | Deadline for when the item must be delivered                                    |
| **Date Submitted**       | Actual date the file or information was submitted                               |
| **Review Status**        | Reviewer status: Under Review, Accepted, Revision Required                      |
| **File Name / Location** | Link or location of the evidence (e.g., SharePoint, Confluence, Drive folder)   |
| **Last Updated By**      | Name of the person who last modified the item in the tracker                    |
| **Notes / Comments**     | Additional comments, blockers, versioning notes, or context                     |

---

## Sample PBC Entry

| Request ID | Request Description               | Requested On | Assigned To | Status     | Due Date  | Date Submitted | Review Status   | File Name / Location                      | Last Updated By | Notes                             |
|------------|------------------------------------|---------------|--------------|------------|------------|----------------|------------------|--------------------------------------------|------------------|-----------------------------------|
| PBC-001    | Current Org Chart with Roles       | 2025-08-15    | HR Manager   | Submitted  | 2025-08-20 | 2025-08-19     | Accepted         | [Org Chart PDF](https://...)              | HR Manager       | Sourced from BambooHR             |
| PBC-002    | Policy Acknowledgments Report       | 2025-08-15    | IT Governance| In Progress| 2025-08-22 |                | Under Review     | Pending export from Dayforce              | Governance Lead  | Waiting on HR export              |
| PBC-003    | MFA Enforcement Evidence            | 2025-08-16    | Security Team| Open       | 2025-08-25 |                | Not Started      |                                          |                  | Will attach screenshots + config  |

---

## Usage Tips

- Use consistent naming for request IDs (e.g., `PBC-###`) for traceability.
- Create one entry per deliverable, even if requests are bundled together.
- Use filters or color-coding if converting to Excel/Google Sheets.
- For internal-only trackers, consider adding classification tags (e.g., CONFIDENTIAL, INTERNAL).

---

## Formats

This tracker can be maintained in:

- Markdown (for Git-based collaboration)
- Excel or Google Sheets (for internal cross-team visibility)
- Confluence tables or Jira tickets (for integrated compliance workflows)

---

## Security Reminder

Never store confidential evidence directly in a public GitHub repo. Store files in access-controlled platforms (e.g., SharePoint, Google Drive) and only include secure links or references in this tracker.

