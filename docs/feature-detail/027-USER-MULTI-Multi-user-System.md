# USER-MULTI - Multi-user System

## Overview
This feature supports multiple users within the system for collaborative emission tracking.

## Category
User & Company Management

## Description
- Allow multiple users per company
- User authentication and authorization
- Shared data access with permissions
- User activity logging

## API Endpoints
- POST /api/users/invite
- GET /api/users/list
- PATCH /api/users/update

## Implementation Notes
- Use JWT for authentication
- Role-based permissions
- Secure data sharing

## Related Features
- USER-ROLE (Role-based Access)
- AUDIT-TRAIL (Data Audit Trail)