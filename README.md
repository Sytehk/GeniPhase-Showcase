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

GeniPhase treats AI as a governed part of the workflow. Brand memory, allowed topics, banned topics, confidence thresholds, and approval modes help guide what can be drafted or actioned. Teams can keep work fully manual or choose limited automation where suitable.

An AI account-manager direction extends this idea beyond publishing. It can use a workspace's approved brand context to help identify sales or support conversations, prepare possible responses, and raise uncertain or risky cases for a person to handle.

## Multi-tenant engineering

Workspace separation shapes the platform from the beginning. Personas and connected accounts belong to workspaces; platform-specific behavior is kept behind provider adapters; and reusable workflows can serve different brands without merging their settings or credentials.

The system is organized as a web product with API, worker, scheduler, and real-time service components. Longer-running publishing and monitoring work can happen outside the interactive user interface. PostgreSQL stores application state, Redis supports asynchronous coordination, and Docker Compose brings the local services together.

## Technology

Nuxt, TypeScript, Flutter, Python, PostgreSQL, Redis, and Docker Compose.

## Screenshots

The available app capture shows a named social account and engagement figures, so it is not included in this public showcase.

## Main site

[Visit GeniPhase](https://geniphase.live)

## This repository

This is a public project overview only. It does not include private source code, connected social-account information, credentials, internal prompts, or operating configuration.

[View the AceNetics case study](https://acenetics.dev/work)
