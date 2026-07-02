# Start Here

This is the first file to open when Bob has a crude idea.

## Step 1: Capture crude idea

Write or paste the messy idea. Do not polish it first. Use `templates/crude_idea_intake.md` if structure helps, or start with a plain paragraph.

## Step 2: Choose run mode

### Quick Mode

Use when the task is small, reversible, or mostly a drafting/planning problem.

Artifacts:
- crude idea
- meta-plan
- next 3 actions

### Standard Mode

Use when the task matters but does not need full research.

Artifacts:
- crude idea
- meta-plan
- tool prompt packets
- one or more deal-team memos
- IC decision

### Full IC Mode

Use when the task is research-heavy, public-facing, high-stakes, or career-relevant.

Artifacts:
- crude idea
- meta-plan
- Deep Research or Web Search outputs
- Bull memo
- Bear memo
- Operator memo
- IC scorecard
- IC decision
- human decision
- execution log

## Step 3: Run the Entrepreneur Meta-Planner

Open `prompts/00_entrepreneur_meta_planner.md`, copy the prompt, and paste the crude idea into it.

## Step 4: Save the meta-plan

Create:

```text
runs/YYYY-MM-DD-project-name/01_meta_plan.md
```

Save the Meta-Planner output there.

## Step 5: Run only the useful prompt packets

Do not run every worker by default. Use only the packets that reduce uncertainty, create a needed artifact, or prepare execution.

## Step 6: Decide

Choose one outcome:

- kill: stop because the case is weak.
- park: save it for later without more work now.
- gather evidence: collect specific missing evidence before deciding.
- small test: run a cheap reversible test.
- commit: proceed with real execution.
- reframe: change the decision question or project shape.

## Step 7: Execute or log

Send a task to Codex when the next step is a file, script, template, repo change, test, or implementation spec.

Log the decision when the right move is kill, park, gather evidence, or wait for Bob's human input.
