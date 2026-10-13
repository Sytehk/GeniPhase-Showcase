# GeniPhase

**AI-assisted social media operations for brands and creator teams**

GeniPhase is a multi-tenant platform concept for managing social personas, content, and account activity from a shared workspace. It brings content planning and publishing together with approvals, engagement monitoring, and team controls.

The product direction is to help a team coordinate the work around one or more online personas without giving an AI system unlimited authority over a brand's voice or connected accounts.

## Product workflows

- **Create personas:** define a persona's voice, topics, content boundaries, and engagement rules.
- **Plan and prepare content:** generate drafts, organize campaigns, and schedule approved posts.
- **Review before publishing:** keep human review and approval in the workflow, with automation settings controlled by the workspace.
- **Monitor responses:** organize comments and conversations, identify support or lead requests, and escalate sensitive or uncertain cases.
- **Manage multiple workspaces:** keep brands, personas, campaigns, settings, and account connections separated by tenant.

Social platforms are handled through provider-specific integrations. Each platform can have its own capabilities and rules while sharing the wider content and approval workflow. The exact availability of a platform integration depends on the connected account and current product configuration.

## Built for controlled automation

GeniPhase treats AI as a governed part of the workflow. Brand memory, allowed topics, banned topics, confidence thresholds, and approval modes are used to guide what can be drafted or actioned. Teams can keep work fully manual or choose limited automation where it is suitable.

The system is organized as a web product with API, worker, scheduler, and real-time service components. Long-running publishing and monitoring work can be handled outside the interactive user interface.

## Engineering

The frontend is built with Nuxt and TypeScript, with Flutter experiences for mobile workflows. Python services provide API and background processing, while PostgreSQL and Redis support data and asynchronous coordination. Docker Compose provides a local multi-service development environment.

## Technology

Nuxt, TypeScript, Flutter, Python, PostgreSQL, Redis, and Docker Compose.

## This repository

This is a public project overview only. It does not include private source code, connected social-account information, credentials, internal prompts, or operating configuration.
