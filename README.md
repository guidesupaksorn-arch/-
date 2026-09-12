# Guide AI Customer OS

MVP customer-service AI for small businesses. The web interface lets a business configure its context, approved knowledge, and tone, then test customer conversations and human-handoff rules.

## Routes

- `/` — customer-service testing interface
- `/api/status` — configuration health check
- `/api/chat` — OpenAI-backed chat endpoint (`POST`)

## Environment

`OPENAI_API_KEY` must be configured in Vercel. Never commit the key to this repository.

## Local setup

```bash
npm install
vercel dev
```

The production project is `guide-ai-customer-os` and deploys from the `main` branch.
