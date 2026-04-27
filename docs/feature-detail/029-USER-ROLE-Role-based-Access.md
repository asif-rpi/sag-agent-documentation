# USER-ROLE - Role-based Access

## Overview
This feature implements role-based access control for different user types.

## Category
User & Company Management

## Description
- Define roles: Admin, User, etc.
- Assign permissions based on roles
- Secure access to features and data
- Audit role changes

## API Endpoints
- GET /api/roles/list
- PATCH /api/users/role

## Implementation Notes
- Use RBAC model
- Default roles and custom roles
- Permission matrix

## Related Features
- USER-MULTI (Multi-user System)
- AUDIT-TRAIL (Data Audit Trail)