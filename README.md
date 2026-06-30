# blueprint-x

An AI-powered planning workspace that transforms vague ideas into actionable software project blueprints.

## What is this?

This is not a traditional application codebase. Instead, it's a personal workspace designed to act as a team of specialized consultants—evaluating, challenging, refining, and architecting ideas before development begins.

### The Problem

Most projects fail because:
- The problem is unclear
- Scope grows uncontrollably
- Architecture decisions happen too early
- Features are added without validation
- Development begins before planning is complete

### The Solution

**blueprint-x** intentionally slows down the process and forces strategic thinking first. Rather than jumping directly to code generation, it guides ideas through a structured planning workflow:

1. **Idea Intake** — capture the initial concept
2. **Discovery Engine** — deep exploration through systematic questioning
3. **Multi-Agent Analysis** — specialized evaluation by Strategist, Architect, and Planner
4. **Scoring & Assessment** — validate viability and alignment
5. **Recommendations** — produce actionable deliverables

### Key Goals

- ✅ Reduced project ambiguity
- ✅ Faster planning cycles
- ✅ Better architecture decisions
- ✅ Lower development costs
- ✅ Higher project completion rate

## Getting Started

**New to this workspace?** Start here:

1. **[AGENTS.md](AGENTS.md)** — Understand the purpose and system overview
2. **[memory/philosophy.md](memory/philosophy.md)** — Learn the core principles (when available)
3. **[active/current-project.md](active/current-project.md)** — See the current project context
4. **Agent guides** — Review role definitions:
   - `agents/strategist/` — Strategic evaluation
   - `agents/architect/` — Technical architecture
   - `agents/planner/` — Implementation roadmap

## Repository Structure

```
blueprint-x/
├── agents/              # Agent role guidance and scorecards
│   ├── strategist/
│   ├── architect/
│   └── planner/
├── engines/             # Decision and discovery engines
├── outputs/             # Generated deliverables
│   ├── product-specification.md
│   ├── architecture-recommendation.md
│   ├── implementation-roadmap.md
│   └── master-build-prompt.md
├── memory/              # Persistent assumptions, decisions, lessons
├── AGENTS.md            # System instructions and overview
└── README.md            # This file
```

## Key Conventions

- **Favor simplicity** — the smallest solution that solves the problem
- **Avoid overengineering** — no enterprise patterns or premature optimization
- **Preserve ideas** — keep non-essential concepts in a Parking Lot rather than expanding scope
- **Treat decisions as settled** — unless new information or clear contradiction appears
- **Prefer free/open-source/local solutions** — unless explicitly requested otherwise

## How to Use This Workspace

1. **For AI Assistants:** Read [AGENTS.md](AGENTS.md) for full behavioral instructions
2. **For Project Managers:** Use templates in `templates/` for consistent deliverables
3. **For Builders:** Reference `active/current-project.md` and generated outputs in `outputs/`

## How to Behave

- Use existing planning guides and templates rather than inventing new structures
- Link deliverables to the appropriate output artifact style
- If a task is ambiguous, ask for clarification rather than guessing
- Do not assume this repository contains executable code or tests

## Notes

- This workspace is designed to support an individual builder working on MVP-style projects
- Keep recommendations practical and actionable
- Focus on progress over excessive analysis

---

**Created:** June 2026  
**Status:** Active workspace  
**License:** Personal use
