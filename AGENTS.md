# AI Agent Instructions

## Purpose

This repository is a personal AI-powered planning workspace for transforming vague ideas into actionable software project blueprints. It is not a traditional application codebase.

**System Vision:** Create a project intelligence engine that acts as a team of specialized consultants—evaluating, challenging, refining, and architecting ideas before development begins. The goal is to generate clarity, not code.

**Core Problem:** Most projects fail because:
- The problem is unclear
- Scope grows uncontrollably
- Architecture decisions happen too early
- Features are added without validation
- Development begins before planning is complete

Current AI tools often jump directly to code generation. This system intentionally slows the process down and forces strategic thinking first.

**System Workflow:**
1. Idea Intake → 2. Discovery Engine (9-category questioning) → 3. Multi-Agent Analysis (Strategist, Architect, Planner) → 4. Scoring & Assessment → 5. Recommendations (Product Spec, Architecture, Roadmap, Build Prompt) → 6. Development

**Key Goals:**
- Reduced project ambiguity
- Faster planning
- Better architecture decisions
- Lower development costs
- Higher project completion rate

## What to read first
- `README` — repository overview
- `memory/philosophy.md` — project principles and decision rules
- `active/current-project.md` — current project context (if populated)
- `agents/*/agent.md` — role definitions for Strategist, Architect, and Planner
- `outputs/*` — expected document outputs
- `templates/*` — preferred output structure

## Key conventions
- Favor the smallest solution that solves the problem.
- Avoid overengineering, enterprise patterns, and premature optimization.
- Preserve non-essential ideas in the Parking Lot rather than expanding scope.
- Treat accepted decisions as settled unless new information or a clear contradiction appears.
- Prefer free/open-source/local solutions unless the user explicitly requests otherwise.

For more detailed rules and decision guidance, see `memory/philosophy.md`.

## Repository structure
- `agents/` — agent role guidance and scorecards
- `engines/` — decision and discovery engines
- `outputs/` — generated deliverables like product specs and roadmaps
- `memory/` — persistent project assumptions, decisions, and rules
- `templates/` — reusable output templates
- `active/` — current active project details

## How to behave
- Use the existing planning guides and templates rather than inventing new output structure.
- When asked to produce a deliverable, link it to the appropriate `outputs/` artifact style.
- If a task is ambiguous, ask the user for the current objective or clarify requirements rather than guessing.
- Do not assume there is executable application code or tests in this repository unless evidence appears.

## Notes for contributors
- This workspace is designed to support an individual builder and MVP-style projects.
- Keep recommendations practical and actionable.
- Avoid excessive analysis and focus on progress.
