# IAM-USER-CREATE: User Create

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-USER-CREATE |
| Feature Name | User Create |
| Category | Identity & Access Management |
| Priority | High |
| Implementation Phase | Phase 1 |

---

## Purpose

Create new users within a company.

---

## Create Fields

| Field | Required | Validation |
|-------|----------|------------|
| Email | Yes | Valid email, unique |
| Full Name | Yes | Non-empty |
| Role | Yes | Valid role |
| Department | No | Existing department |
| Send Invite | Yes | Email invitation |

---

## Create Process

| Step | Description |
|------|-------------|
| 1 | Admin enters user data |
| 2 | Validate input |
| 3 | Create user record |
| 4 | Send invitation email |
| 5 | Log audit trail |

---

## Invitation Flow

| Step | Description |
|------|-------------|
| 1 | Send invitation email |
| 2 | User clicks link |
| 3 | Set password |
| 4 | Activate account |
| 5 | Login allowed |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/users | POST | Create user |
| /api/users/invite | POST | Invite user |

---

## Implementation Notes

- Invitation-based creation
- Email verification
- Audit logging

---

## Related Features

- IAM-USER-LIST (User List)
- IAM-USER-ROLE (User Role Management)
- AUTH-REGISTER (User Registration)