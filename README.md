# ManageEmployees Frontend

Next.js 15 SPA for employee and task management with MUI v6 and TypeScript.

## Tech Stack

- Next.js 15 (App Router, Turbopack)
- React 18 / TypeScript 5
- MUI v6 / TanStack React Table
- Axios with Gateway pattern
- Context API for state management

## Running

```bash
# Local
npm install
npm run dev       # http://localhost:3000

# Docker (full stack — from ManageEmployees.Api/)
docker compose up --build
```

## Default Login

- **Email:** `admin@company.com`
- **Password:** `Admin123!`

## Documentation

| Document | Description |
|----------|-------------|
| [PRESENTATION.md](docs/PRESENTATION.md) | Architecture decisions and technical summary |
| [GENAI_USAGE.md](docs/GENAI_USAGE.md) | AI usage methodology and contributions |
| [TEST_VALIDATION_PLAN.md](docs/TEST_VALIDATION_PLAN.md) | Requirement traceability matrix |
