# ProTasker Search Frontend

## Overview

The ProTasker Search Frontend delivers global search capabilities across the platform.

Users can search for:

- Projects
- Tasks
- Collaborators
- Activity logs

Search results are filtered based on user permissions and access rights.

---

## Architecture

- React
- Amazon Cognito authentication
- JWT-secured API Gateway endpoints
- Backend search service (DynamoDB queries or search index integration)

---

## Responsibilities

- Global search input
- Filter by entity type
- Display categorized results
- Pagination of results
- Highlight matched keywords
- Role-based result filtering

---

## Security Model

- Cognito authentication required
- JWT token attached to all search requests
- Backend enforces access control filtering
- Users cannot retrieve unauthorized data

---

## Integration

Communicates with:

- protasker-search-service
- protasker-project-service
- protasker-task-service
- protasker-collaborator-service
- protasker-activity-service

---

## Tech Stack

- React
- AWS Amplify Auth
- Axios or Fetch
- React Router

---

## Status

Initial scaffold complete. Advanced filtering and search optimization planned.
