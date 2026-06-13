# Architecture Recommendation

## Philosophy

Build the smallest system capable of producing high-quality project plans.

Avoid enterprise architecture.

Avoid microservices.

Avoid premature scaling.

—

## Frontend

Framework:
- React
- Vite
- TypeScript

UI:
- Tailwind
- shadcn/ui

State:
- Zustand

Benefits:
- Fast
- Cheap
- Simple

—

## Backend

Option A (Recommended)

Supabase

Use for:

- Authentication
- Database
- Storage

Benefits:

- Free tier
- Fast setup
- Minimal maintenance

—

## Database

Postgres (Supabase)

Core Tables:

Projects

Questions

Answers

AgentRuns

Scores

Outputs

Templates

—

## AI Layer

Primary Model:
- OpenAI

Fallback:
- Anthropic

Optional:
- Local LLM later

Agent execution:

Single orchestrator

↓

Multiple virtual agents

↓

Structured outputs

No need for separate agent services.

—

## Knowledge System

Markdown-based.

Store:

- templates
- scorecards
- agent definitions
- examples

Inside repository.

—

## Deployment

Frontend:
- Vercel

Backend:
- Supabase

Total Monthly Cost:

Target:
$0-$20/month

—

## Future Expansion

Phase 2

- Project memory
- Template marketplace
- Reusable frameworks

Phase 3

- Automated PRD generation
- Architecture diagrams
- Code scaffolding

Phase 4

- Local AI execution
- Offline mode
- 
- 
- 
- 
- 
 
 
 

Output 3: Architecture Recommendation

Philosophy

Prefer:

Manual
↓
Local
↓
Static
↓
Open Source
↓
Free
↓
Paid

⸻

Recommended MVP Stack

Frontend

Markdown files

or

Simple Next.js application

⸻

Storage

Markdown
JSON
Git

before

Database

⸻

Authentication

None initially.

⸻

Hosting

GitHub repository.

⸻

AI Layer

Single LLM provider.

No multi-model routing.

No agent swarm.

No orchestration framework.

⸻

Infrastructure

Git Repository
+
Markdown
+
LLM

⸻

Cost Estimate

Monthly:

$0-$20
