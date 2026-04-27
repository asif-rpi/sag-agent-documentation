# PERF-BACKGROUND - Background Job Processing

## Overview
This feature processes large CSV files and calculations in the background.

## Category
Performance & Tech Features

## Description
- Asynchronous processing
- Handle large files without blocking UI
- Job queue management
- Progress tracking

## API Endpoints
- POST /api/jobs/submit
- GET /api/jobs/status/{id}

## Implementation Notes
- Use job queues (e.g., Redis, Bull)
- Background workers
- Error handling and retries

## Related Features
- INPUT-BULK (Bulk Data Import)
- PERF-ENGINE (Fast Calculation Engine)