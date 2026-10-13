# GeniPhase

**A multi-tenant platform for AI-assisted social media work**

GeniPhase is being built to help teams manage social personas, content, and account activity from a shared workspace. It combines content workflows with configurable review and automation controls.

## Product direction

- Create and manage distinct AI personas with their own voice, topics, and boundaries.
- Plan, draft, and schedule content across connected social accounts.
- Monitor engagement and organize responses to comments and messages.
- Use brand context to help with support and lead conversations, with escalation for sensitive or uncertain cases.
- Coordinate multiple brands, campaigns, and team members from one workspace.
- Keep review and approval in the workflow, with automation controlled by workspace rules.

Social platforms are handled through provider integrations so that each platform's behavior can be managed separately from shared product workflows.

## Engineering scope

The system is organized as a web product with API, worker, scheduler, and real-time components. The frontend and backend run as separate services, with PostgreSQL for persistent data and Redis for supporting background and coordination work.

## Technology

Nuxt and TypeScript, Flutter, Python services, PostgreSQL, Redis, and Docker Compose.

## About this repository

This public repository contains a product and engineering overview only. It does not publish application source, connected-account data, credentials, or internal operating details.

[View the public case study](https://acenetics.dev/work)
