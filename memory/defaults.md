# System Defaults & Verified Assumptions

Defaults exist to reduce unnecessary questioning and accelerate progress. Defaults may be overridden at any time by explicit user request.

---

## Active System Defaults

| Parameter | Default | Notes |
|-----------|---------|-------|
| **Scope** | Personal-use projects only | Reduces complexity; eliminates multi-user requirements |
| **Builder** | Solo Builder | One person building useful software usually to help with their workflow |
| **Target Platform** | Mobile + Desktop | Mac and iOS prioritized if complexity is high |
| **Budget** | Minimal cost | Recurring expenses questioned; prefer free/open-source | trial ok
| **Infrastructure** | Minimal | Static hosting or local preferred |
| **Database** | None unless required | Markdown/JSON preferred for storage |
| **Authentication** | None unless required | Can be delayed to post-MVP | if user wants basic security, add a four digit PIN/FACE ID lock/unlock as the default auth solution
| **APIs** | Free only | Avoid paid APIs unless justified |
| **Architecture** | Simplest viable | No microservices, Kubernetes, or premature scaling |
| **Scale** | Single-user | No expansion or enterprise assumptions |
| **Maintenance** | Lowest-maintenance option | Prefer solutions requiring minimal upkeep |
| **Development Priority** | Completion over optimization | Finish first, optimize later |

---

## Verified Assumptions

### Project Assumptions

- Users prefer guided questioning over blank forms
- Most projects can be reduced to one primary problem
- Mobile-first workflow is sufficient and preferred

### Technical Assumptions

- Local storage is sufficient for MVP
- Authentication can be delayed

---

## Decision History

**2026-06-10**
- Only support personal-use projects initially
- Reason: Reduces complexity and eliminates multi-user requirements
- Status: Active

---

## Override Rule

Defaults are temporary assumptions. The user may override any default at any time. Explicit user requests or requirements always supersede defaults.
