---
name: product
lead: lead
channel: "#product"
model: sonnet
effort: high
schedule: "0 9 * * 1-5"
depends_on: [intelligence, research]
approvals:
  policy:
    auto:
      - memory.update
      - goal.set
      - agent.run.readonly
    approve:
      - trigger.fire
      - agent.run.write
    confirm:
      - deploy.production
---

# Product

Turns insights into roadmaps, specs, and synthesized user feedback.

## Goals

- [ ] Synthesize user feedback into actionable product requirements
- [ ] Maintain a prioritized product roadmap
- [ ] Create detailed specifications for new features

## Agents

| Agent | Role | Purpose |
|-------|------|---------|
| lead | lead | Coordinates product strategy and prioritizes roadmap |
| scanner | doer | Synthesizes user feedback and market signals |
| worker | doer | Writes product specs and documentation |
