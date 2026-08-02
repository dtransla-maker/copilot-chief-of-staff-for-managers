# Step-by-Step Deployment in Copilot

## Step 1: Prepare the tenant and manager group

1. Confirm Microsoft 365 Copilot licensing for pilot managers.
2. Confirm Agent Builder availability and sharing rules.
3. Confirm scheduled prompts availability if required.
4. Confirm Teams meeting transcription and recap policies if meeting context will be used.
5. Confirm knowledge-source permissions before adding SharePoint, OneDrive, or Teams content to any agent.

## Step 2: Build the manual prompt pack

1. Create the Daily Manager Briefing prompt.
2. Create the Meeting Prep Brief prompt.
3. Create the Team Commitments and Follow-Up Review prompt.
4. Create the Weekly Manager Review prompt.
5. Test the four prompts with a small pilot group.

## Step 3: Create the Manager Operating Agent

1. In Microsoft 365 Copilot, go to Agents and create a new agent.
2. Use the description in `agents/manager-operating-agent/description.md`.
3. Use the instructions in `agents/manager-operating-agent/instructions.md`.
4. Add approved knowledge sources only after owner and permission review.
5. Add starter prompts from `agents/manager-operating-agent/starter-prompts.md`.
6. Preview and test against real manager scenarios.

## Step 4: Schedule only stable read-only routines

Schedule only prompts that are repeatable, low-noise, read-only, useful without judgment calls, and safe to run without taking action.

## Step 5: Scale and govern

1. Create a champions group.
2. Publish one version of the prompt library and agent instructions.
3. Review outputs weekly.
4. Use success metrics to decide whether to scale, stabilize, or stop.
5. Move execution workflows to Copilot Studio only after governance review.
