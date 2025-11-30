# Password Policy Template

## Purpose

This policy defines the minimum password requirements to ensure the protection of ClearCaptions systems and data from unauthorized access. It applies to all employees, contractors, and third-party users who access company systems.

---

## Scope

This policy applies to:

- All systems that require user authentication
- All personnel using ClearCaptions-owned or managed systems
- All third-party vendors or service accounts with access to internal systems

---

## Policy Requirements

| Control Area         | Requirement                                                                 |
|----------------------|------------------------------------------------------------------------------|
| **Password Length**  | Minimum of 12 characters                                                     |
| **Complexity**       | Must include uppercase, lowercase, number, and special character            |
| **Reuse Limit**      | Cannot reuse any of the last 5 passwords                                    |
| **Expiration**       | Passwords must be changed at least every 90 days                            |
| **Lockout**          | Account locked after 5 failed login attempts                                |
| **Storage**          | Passwords must be hashed and salted using modern cryptographic techniques   |
| **Multi-Factor Auth**| MFA required for privileged or remote system access                         |

---

## Best Practices

- Avoid using common words or patterns (e.g., “Password123!”)
- Use a password manager to generate and store secure credentials
- Do not write down or share passwords with others

---

## Violations

Failure to adhere to this policy may result in disciplinary action, including revocation of access rights or termination of employment. Security incidents caused by password negligence will be subject to incident response procedures.

---

## Review Cycle

This policy shall be reviewed annually or when significant changes occur in system architecture, threat landscape, or regulatory requirements.

---

## References

- NIST SP 800-63B
- ISO/IEC 27001 Annex A.9: Access Control
- CIS Controls v8 – Control 5 (Account Management)
