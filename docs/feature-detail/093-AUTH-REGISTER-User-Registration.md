# AUTH-REGISTER: User Registration

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | AUTH-REGISTER |
| Feature Name | User Registration |
| Category | Authentication & Authorization |
| Priority | Critical |
| Implementation Phase | Phase 1 |

---

## Purpose

New user signup with email verification and company creation.

---

## Registration Flow

| Step | Description |
|------|-------------|
| 1 | User enters email/password |
| 2 | Send verification email |
| 3 | User clicks verification link |
| 4 | Create user account |
| 5 | Create default company |

---

## Registration Fields

| Field | Required | Validation |
|-------|----------|------------|
| Email | Yes | Valid email format |
| Password | Yes | Min 8 chars, complexity |
| Company Name | Yes | Non-empty |
| Full Name | Yes | Non-empty |

---

## Verification

| Type | Description |
|------|-------------|
| Email | Verify email ownership |
| Optional | Phone verification |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/auth/register | POST | User registration |
| /api/auth/verify | POST | Verify email |
| /api/auth/resend | POST | Resend verification |

---

## Implementation Notes

- Email verification required
- Company auto-creation
- Welcome email sent

---

## Related Features

- AUTH-LOGIN (User Login)
- IAM-USER-LIST (User List)
- USER-PROFILE (Company Profile)