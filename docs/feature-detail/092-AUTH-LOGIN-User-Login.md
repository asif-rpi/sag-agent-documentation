# AUTH-LOGIN: User Login

## API Basic Information

| Item | Content |
|------|---------|
| Unique ID | AUTH-LOGIN |
| API Name | User Login |
| Type | POST |
| Endpoint | /api/auth/login |
| Category | Authentication & User Management |
| Status | Planned |

---

## Summary

Secure user authentication with email/password and optional MFA. Authenticate user and issue JWT token.

---

## Authentication Methods

| Method | Description | Security |
|--------|-------------|----------|
| Email/Password | Standard login | Medium |
| Magic Link | Passwordless email | High |
| MFA | Multi-factor auth | Very High |
| SSO | Single sign-on | High |

---

## Request Body

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| email | string | Yes | User email address |
| password | string | Yes | User password |

---

## Response

| Field | Type | Description |
|-------|------|-------------|
| accessToken | string | JWT access token |
| refreshToken | string | JWT refresh token |
| user | object | User profile |

---

## Security Features

| Feature | Description |
|---------|-------------|
| Password Hash | bcrypt hashing |
| Rate Limiting | Prevent brute force |
| Session Timeout | Auto-logout |
| Device Tracking | Track login devices |
| Device Tracking | Track login devices |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/auth/login | POST | User login |
| /api/auth/logout | POST | User logout |
| /api/auth/refresh | POST | Refresh token |
| /api/auth/mfa/setup | POST | Enable MFA |

---

## Implementation Notes

- JWT-based authentication
- Secure token storage
- Session management

---

## Related Features

- AUTH-REGISTER (User Registration)
- IAM-USER-LIST (User List)
- USER-ROLE (Role-based Access)