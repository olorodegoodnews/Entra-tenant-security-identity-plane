# Emergency Access Design

## Purpose
Provide tenant recovery access if Conditional Access, MFA, device requirements, or other identity controls block normal administrative sign-in.

## Accounts
- emergency.access.01@tenant.onmicrosoft.com
- emergency.access.02@tenant.onmicrosoft.com

### Screenshot: Users Created

![Users Created](../Evidence/01-Users-created.png.png)

## Design Decisions
- Both accounts are cloud-only.
- Both accounts are reserved for emergency recovery and controlled validation only.
- Both accounts are assigned Global Administrator in this lab tenant.
- These accounts are excluded from Conditional Access controls that could block tenant recovery.

## Security Controls
- Strong unique passwords
- No day-to-day administrative use
- Sign-in activity monitored
- Credentials stored securely
