# Project A — Real-time Research Insight Platform

Stack: React + TypeScript (frontend) • Node.js + GraphQL (backend) • PostgreSQL (database) • FastAPI + spaCy (ML service) • WebSockets (real-time)

Overview
A demo platform for ingesting, tagging, summarizing, and visualizing qualitative research notes in real time. Backend exposes GraphQL endpoints; a Python microservice provides NLP tagging/summaries; frontend consumes streaming updates and displays a split-screen workspace.

Running locally
1. `docker-compose up` (starts Postgres)
2. `npm install`
3. `npm run dev` (starts backend)
