# AUTH-FORGOT-PASSWORD: Forgot Password

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | AUTH-FORGOT-PASSWORD |
| Feature Name | Forgot Password |
| Category | Authentication & Authorization |
| Priority | High |
| Implementation Phase | Phase 1 |

---

## Purpose

Password reset request via email.

---

## Reset Flow

| Step | Description |
|------|-------------|
| 1 | User enters email |
| 2 | Validate email exists |
| 3 | Generate reset token |
| 4 | Send reset email |
| 5 | Store token (expires 1h) |

---

## Security Features

| Feature | Description |
|---------|-------------|
| Token Expiry | 1 hour expiration |
| Rate Limiting | Prevent abuse |
| Email Masking | Don't reveal accounts |
| Audit Log | Log reset requests |

---

## Email Template

| Element | Content |
|---------|----------|
| Subject | Password Reset Request |
| Link | Reset password URL |
| Expiry | 1 hour warning |
| Support | Help contact |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/auth/forgot-password | POST | Request reset |
| /api/auth/validate-token | POST | Validate reset token |

---

## Implementation Notes

- Secure token generation
- Email delivery
- Expiration handling

---

## Related Features

- AUTH-LOGIN (User Login)
- AUTH-RESET-PASSWORD (Reset Password)
- AUTH-REGISTER (User Registration)