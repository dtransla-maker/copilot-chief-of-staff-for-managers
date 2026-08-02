# Three-Phase Rollout

## Phase 1: Manager Foundation

Goal: prove daily value with manual prompts.

Deploy:

- Daily Manager Briefing
- Meeting Prep Brief
- Team Commitments and Follow-Up Review

Exit criteria:

- managers use the core prompts several times
- outputs are short and specific
- managers identify at least one useful missed item or follow-up
- prompt noise is low enough to move into Agent Builder

## Phase 2: Agent Builder and Reusable Cadence

Goal: convert stable prompts into a reusable Manager Operating Agent.

Deploy:

- Manager Operating Agent description
- Manager Operating Agent instructions
- starter prompts
- approved knowledge sources
- Weekly Manager Review
- optional scheduled prompts for stable read-only routines

## Phase 3: Governed Scale and Controlled Execution

Goal: scale the proven pattern across teams with governance.

Deploy:

- department rollout package
- champion training
- success metrics
- governance checklist
- selective Copilot Studio use for approved execution

## Visual rollout map

```mermaid
journey
    title Manager Copilot Rollout Journey
    section Phase 1: Manager Foundation
      Run Daily Manager Briefing manually: 5: Manager
      Prepare for high-stakes meetings: 4: Manager
      Review team commitments: 4: Manager
      Remove noisy sections: 3: Pilot Lead
    section Phase 2: Agent Builder
      Create Manager Operating Agent: 4: Pilot Lead
      Add starter prompts: 4: Pilot Lead
      Add approved knowledge sources: 3: IT/Owner
      Schedule stable read-only prompts: 3: Manager
    section Phase 3: Governed Scale
      Publish playbook: 4: Program Owner
      Train manager cohort: 4: Champions
      Track metrics: 3: Program Owner
      Review controlled execution: 2: IT/Governance
```
