# User Account Issues

This document focuses on user account problems such as password resets, account lockouts, and access issues.
## Issue 1: User Account Locked Out

### Scenario
A user reports they cannot log in due to multiple failed login attempts.

### Severity: High

### Symptoms
- User cannot log in
- Error message: "Account locked due to too many failed login attempts"

### Expected Result
User should be able to log in normally

### Actual Result
Account is locked; user access denied

### Troubleshooting Steps
1. Verified user identity
2. Checked account status in Active Directory
3. Unlocked the user account
4. Reset the password
5. Advised the user to update saved passwords on all devices

### Resolution
Unlocking the account and resetting the password restored user access

### Skills Demonstrated
- User account management
- Active Directory basics
- Password reset procedures
- Documentation skills
- Security best practices

### Lessons Learned
- Always verify identity before making changes
- Educate users on password management

### Lab Simulation (No Hardware Required)
| Step | Action | Expected Outcome |
|------|--------|----------------|
| 1 | Check account status in AD | Confirm lockout |
| 2 | Unlock account | User can log in |
| 3 | Reset password | Ensure credentials are updated |
| 4 | Advise user | Prevent future lockouts |

### Next Steps / Improvements
- Explore automated account lockout alerts
- Practice managing accounts in a virtual AD lab
- Implement multi-factor authentication testing

