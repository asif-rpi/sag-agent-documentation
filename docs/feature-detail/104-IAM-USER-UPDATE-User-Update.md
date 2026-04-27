# IAM-USER-UPDATE: User Update

## Feature Basic Information

| Item | Content |
|------|---------|
| Unique ID | IAM-USER-UPDATE |
| Feature Name | User Update |
| Category | Identity & Access Management |
| Priority | High |
| Implementation Phase | Phase 1 |

---

## Purpose

Update user profile and settings.

---

## Updatable Fields

| Field | Description |
|-------|-------------|
| Full Name | Display name |
| Department | Department |
| Phone | Contact number |
| Avatar | Profile image |
| Preferences | User settings |

---

## Update Process

| Step | Description |
|------|-------------|
| 1 | User edits profile |
| 2 | Validate input |
| 3 | Update user record |
| 4 | Log audit trail |
| 5 | Return updated data |

---

## Validation Rules

| Field | Rule |
|--------|------|
| Name | Required, max 100 chars |
| Phone | Valid phone format |
| Email | Cannot change email |

---

## API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/users/:id | PUT | Update user |
| /api/users/me | PUT | Update current user |

---

## Implementation Notes

- Self-service update
- Admin can update any
- Audit logging

---

## Related Features

- IAM-USER-GET (User Get)
- IAM-USER-LIST (User List)
- USER-PROFILE (Company Profile)