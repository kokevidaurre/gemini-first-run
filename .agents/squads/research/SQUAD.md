---
name: research
lead: lead
channel: "#research"
model: sonnet
effort: high
schedule: "0 10 * * 1,3,5"
approvals:
  policy:
    auto:
      - memory.update
      - agent.run.readonly
    approve:
      - agent.run.write
---

# Research

Market, competitor, and trend research. Produces actionable intelligence.

## Goals

- [ ] Identify market landscape and key competitors
- [ ] Produce initial research report
- [ ] Establish research rhythm (3x per week)

## Agents

| Agent | Role | Purpose |
|-------|------|---------|
| lead | lead | Defines research agenda and coordinates focus |
| analyst | doer | Conducts deep research and domain analysis |
| synthesizer | doer | Synthesizes findings into cohesive reports |

## Pipeline

`lead` defines → `analyst` researches → `synthesizer` reports
