# AUTH-RESET-PASSWORD: Reset Password

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | AUTH-RESET-PASSWORD |
| Feature Name | Reset Password |
| Category | Authentication & Authorization |
| Priority | High |
| Implementation Phase | Phase 1 |

---

## Purpose

Complete password reset with new password.

---

## Reset Process

| Step | Description |
|------|-------------|
| 1 | User clicks reset link |
| 2 | Validate reset token |
| 3 | Enter new password |
| 4 | Validate password strength |
| 5 | Update password hash |
| 6 | Invalidate all sessions |

---

## Password Requirements

| Requirement | Rule |
|--------------|------|
| Length | Minimum 8 characters |
| Uppercase | At least 1 uppercase |
| Lowercase | At least 1 lowercase |
| Number | At least 1 number |
| Special | At least 1 special char |

---

## Post-Reset Actions

| Action | Description |
|--------|-------------|
| Invalidate Sessions | Logout all devices |
| Send Notification | Email user |
| Clear Reset Token | Delete used token |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/auth/reset-password | POST | Reset password |
| /api/auth/change-password | POST | Change password |

---

## Implementation Notes

- Strong password policy
- Session invalidation
- Notification sent

---

## Related Features

- AUTH-FORGOT-PASSWORD (Forgot Password)
- AUTH-LOGIN (User Login)
- AUTH-MFA (Multi-Factor Authentication)