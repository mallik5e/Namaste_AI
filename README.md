# Make My Marriage

Initial application scaffold based on [`docs/SYSTEM_DESIGN.md`](docs/SYSTEM_DESIGN.md).
The project starts as a TypeScript Next.js modular monolith. Domain behavior and
external-service integrations have not been implemented yet.

## Structure

- `src/app` — Next.js application surfaces and REST route handlers
- `src/modules` — domain-owned business logic and persistence boundaries
- `src/server` — server-only database and external-service adapters

## Start locally

Use Node.js 20.9 or newer, install dependencies with `npm install`, then run
`npm run dev`.
