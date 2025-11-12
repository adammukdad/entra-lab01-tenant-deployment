# Lab Report: Microsoft Entra ID Tenant Deployment

## Step-by-Step Execution

### Step 1: Tenant Deployment
- Logged into the Microsoft Entra Admin Center and confirmed initial setup.
- Verified default tenant configuration and renamed the directory from **Default Directory** to **Lab1-Tenant**.

### Step 2: Verify Tenant Information
Captured and recorded the following key tenant details:
- Tenant Name: Lab1-Tenant
- Primary Domain: ADAMMUKDAD97GMAIL.onmicrosoft.com
- Tenant ID: REDACTED FOR SECURITY. It will be a string of letters & numbers.
- License: Microsoft Entra ID Free

### Step 3: Create Global Administrator
- Created a new administrative account: **Lab1-Admin@ADAMMUKDAD97GMAIL.onmicrosoft.com**
- Display Name: **Lab1 Administrator**
- Assigned **Global Administrator** role.
- Verified via role assignment screenshot.

### Step 4: First Login and MFA Setup
- Signed in as **Lab1-Admin**.
- Updated password at first login.
- Configured Microsoft Authenticator for MFA verification.
- Successfully verified sign-in via app prompt.

### Step 5: Self-Service Password Reset (SSPR)
- Navigated to Password Reset configuration.
- Verified admin-level SSPR availability.
- Tested password reset via https://passwordreset.microsoftonline.com.
- Successfully reset password after verification through Microsoft Authenticator.

## Verification and Screenshots
All verification steps were documented with screenshots stored in `/screenshots`.

## Lab Reflection
This lab reinforced my understanding of Entra ID architecture, administrative roles, and secure authentication flows. Establishing a tenant manually deepened my grasp of directory services, MFA, and the security benefits of SSPR in real-world environments.
