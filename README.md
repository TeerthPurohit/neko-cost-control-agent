# Neko Cost Control Agent

Kotlin Android personal finance agent with local transaction capture, a private
backend, configurable AI cost limits, focused task agents, and durable correction
memory.

## Project layout

- `app/` and `core/`: Android app and ledger logic.
- `backend/`: Node API, Postgres migrations, durable tasks, and AI budget controls.
- `agent-service/`: private LangGraph/Nanobot task agents.
- `preview/`: browser interface preview.
- `docs/agent-learning.md`: correction memory and specialist behavior.

## Configuration

Copy `.env.example` to `.env` locally and supply your own configuration. Real
credentials, local environment files, signing keys, databases, and personal
spending policy are excluded from Git. Model API keys belong on the backend.
Raw transaction SMS stays on the Android device.

This is a sanitized public source snapshot. Personal finance names are replaced
with generic examples, and backend and deployment values are placeholders.
Configure your own deployment before use. Never commit real credentials or
personal financial records.
