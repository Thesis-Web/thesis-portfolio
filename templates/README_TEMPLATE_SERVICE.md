
# <Service Name>

Short description of what this service does and the boundary it owns.

## What it does
- Bullet list of responsibilities
- Bullet list of non-responsibilities (important for services)

## Tech
- Node.js + TypeScript
- Fastify
- SQLite (better-sqlite3)

## API
List key endpoints with example requests.

## Local development
```bash
cp .env.example .env
npm install
npm run dev
```

## Build & run
```bash
npm run build
npm run start
```

## Ops / deployment
- Bind address (localhost vs public)
- Reverse proxy notes (nginx)
- systemd service notes (if used)

## Security posture
- Rate limiting
- Schema validation
- Helmet (or equivalent)
- Logging / audit (high-level)
