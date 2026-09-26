# Base44 development notes

- Start the live preview with `docker compose -f docker-compose.base44.yml up -d`.
- The site is a static HTML page served by `server.mjs`; it has no package dependencies, database, or external credentials.
- Verify it with `curl -f http://localhost:3000/` and confirm the Drift Haus page title.
