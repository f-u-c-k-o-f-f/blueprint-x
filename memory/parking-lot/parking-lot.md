# Parking Lot — Scope Protection & Future Ideas

## Objective

Prevent AI-induced scope creep by capturing useful ideas without allowing them to expand scope, increase complexity, or delay delivery.

---

## Purpose

The Parking Lot exists to preserve potentially valuable observations while protecting the current objective from scope creep. It provides a sandbox where expansion ideas can live safely without hijacking the current project requirements, architecture, roadmap, or MVP scope.

**Golden Rule:** Items placed in the Parking Lot must not influence or modify the current project specification.

---

## What Goes Here

Appropriate items for the Parking Lot:

- Future features
- Optimization opportunities
- Alternative implementations
- Scaling considerations
- Nice-to-have functionality
- Workflow enhancements
- User experience improvements
- Potential integrations
- Advanced features
- Performance optimizations

---

## What Does NOT Go Here

Do NOT place items in the Parking Lot if they are:

- Required for core functionality
- Required for MVP success
- Required to generate outputs
- Required to satisfy user requirements
- Required to prevent system failure
- Required for security, privacy, or legal compliance

**These must be surfaced immediately as Critical Issues.**

---

## Evaluation Rule

Before recommending any addition, ask:

1. **What breaks without it?** (If nothing, continue)
2. **Is it required to satisfy the user's objective?** (If no, continue)
3. **Is it required for MVP success?** (If no, continue)
4. **Is it required for system functionality?** (If no, continue)

If all answers indicate it is not required and does not break the project without it:

→ **DO NOT recommend it. Log it in the Parking Lot instead.**

Never modify scope, architecture, requirements, or roadmap based on Parking Lot ideas unless explicitly approved.

---

## Critical Distinction: Parking Lot vs. Blocker

### ✅ Parking Lot Example (Valid)

**AI thinks:** "Could support multiple users. Could support teams. Could support project history. Could support cloud sync. Could support agent collaboration. Could support versioning."

**Assessment:** All of those might be good ideas. None are required.

**Action:** → **Parking Lot**

---

### 🚫 Blocker Example (NOT Parking Lot)

**AI thinks:** "There is no way to export the build prompt."

**Assessment:** Without export:
- Idea → Discovery → Build Prompt... **STUCK**
- The system cannot complete its purpose
- This is a critical missing requirement

**Action:** → **Surface Immediately** (This is a Blocker, not a Parking Lot item)

---

## Stored Ideas

*(Items will be logged here by agents during project execution)*
