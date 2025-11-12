# NIST CSF and Zero Trust Alignment

## NIST Cybersecurity Framework (CSF) Mapping

| Function | Category | Control ID | Description | Lab Implementation |
|-----------|-----------|-------------|--------------|--------------------|
| Identify | Asset Management | ID.AM-1 | Identify and manage assets and systems within the organization | Microsoft Entra tenant deployed and documented |
| Govern | Roles and Responsibilities | GV.RR | Assign and manage administrative privileges | Lab1-Admin assigned Global Administrator role |
| Protect | Access Control | PR.AC-4 | Enforce least privilege and secure authentication | MFA and SSPR configured for administrator |
| Protect | Identity Management | PR.AC-6 | Manage digital identities and credentials securely | Entra ID directory created and governed |
| Detect | Security Continuous Monitoring | DE.CM-1 | Monitor network and user behavior for anomalies | Entra ID Sign-in logs accessible in portal |

## Zero Trust Principles Applied

| Principle | Implementation |
|------------|----------------|
| Verify Explicitly | Enforced MFA and verified authentication with Microsoft Authenticator |
| Least Privilege Access | Scoped Global Admin role to Lab1-Admin only |
| Assume Breach | Implemented password recovery and strong authentication policies |
