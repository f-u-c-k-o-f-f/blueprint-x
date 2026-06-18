# Shared Scorecard Components

## Confidence Model (Used by All Agents)

Score confidence from 0-100 based on:

- Problem Clarity
- User Clarity
- Success Definition
- Constraint Clarity
- Assumption Validation

Confidence = average score.

Continue questioning until enough information has been obtained to provide all expected outputs, including a full-stack solution that meets the user where they want.

---

## Final Verdict Format (Used by All Agents)

🟢 APPROVED

🟡 APPROVED WITH REVISIONS

🔴 REJECTED

**Reason:** [Why this verdict?]

**Strengths:** [What's working well]

**Weaknesses:** [What needs improvement]

**Recommendations:** [What to improve]

---

## How Agents Use This Template

Each agent's scorecard includes:
1. Agent-specific evaluation criteria (unique scoring dimensions)
2. Individual scores for each criterion (/10)
3. Reference to this Confidence Model
4. Final Verdict using this format above

All agents use this confidence model and verdict structure.
