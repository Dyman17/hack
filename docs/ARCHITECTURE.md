# ARCHITECTURE

## High-level architecture

User
  |
  v
Frontend
  |
  | HTTP / JSON
  v
FastAPI Backend
  |
  +---- PostgreSQL
  |
  +---- AI Services
  |
  +---- OCR / CV
  |
  v
Result

## Principles

- Frontend communicates with backend through API.
- Backend contains business logic.
- PostgreSQL stores persistent data.
- AI functionality is isolated in service modules.
- Secrets are stored in environment variables.
- Services should have clear responsibilities.
- Avoid unnecessary complexity.

## Planned stack

Frontend:
- TBD

Backend:
- Python
- FastAPI

Database:
- PostgreSQL

AI:
- LLM API
- Structured output
- RAG when required

Infrastructure:
- Docker
- Docker Compose
- Linux
