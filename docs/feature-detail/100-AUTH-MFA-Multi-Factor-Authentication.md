# AUTH-MFA: Multi-Factor Authentication

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | AUTH-MFA |
| API Name | Multi-Factor Authentication |
| Type | POST |
| Endpoint | /api/auth/mfa/setup |
| Category | Authentication & User Management |
| Status | Planned |

---

## Summary

Enable and verify MFA for enhanced security. Enhanced security with two-factor authentication.

---

## MFA Methods

| Method | Description | Setup |
|--------|-------------|-------|
| TOTP | Authenticator app | Scan QR code |
| SMS | Text message code | Phone verification |
| Email | Email code | Email verification |

---

## MFA Flow

| Step | Description |
|------|-------------|
| 1 | User enables MFA |
| 2 | Setup authenticator |
| 3 | Login with password |
| 4 | Enter MFA code |
| 5 | Validate and login |

---

## MFA Settings

| Option | Description |
|--------|-------------|
| Required | Force MFA for all users |
| Optional | User choice |
| Trusted Devices | Skip MFA for trusted |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/auth/mfa/setup | POST | Setup MFA |
| /api/auth/mfa/verify | POST | Verify MFA code |
| /api/auth/mfa/disable | POST | Disable MFA |

---

## Implementation Notes

- TOTP-based MFA
- Trusted device option
- Recovery codes

---

## Related Features

- AUTH-LOGIN (User Login)
- AUTH-REGISTER (User Registration)
- IAM-USER-ROLE (User Role Management)