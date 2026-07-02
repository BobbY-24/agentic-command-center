# agentic-command-center

An operational command center for turning crude ideas into AI-directed work.

This repo is not a documentation showcase. It is a small set of reusable prompts, templates, run folders, and examples that help Bob move from "I have a rough idea" to "I have a decision, an artifact plan, and execution instructions."

## Core Loop

```text
Crude idea
→ Entrepreneur Meta-Planner
→ tool prompt packets
→ competing analyst-banker teams
→ investment committee synthesis
→ human stakeholder decision
→ Codex/GitHub execution
→ optional LinkedIn/public artifact
```

## How It Starts

Start with a crude idea, not a polished brief. Use [templates/crude_idea_intake.md](templates/crude_idea_intake.md) if helpful, or paste a messy paragraph directly into [prompts/00_entrepreneur_meta_planner.md](prompts/00_entrepreneur_meta_planner.md).

The goal of the first step is not to get an answer. The goal is to discover the real decision question and route the work to the right AI and human workers.

## What the Entrepreneur Meta-Planner Does

The Entrepreneur Meta-Planner is the front door. It turns the crude idea into:

- a restated idea
- the real decision question
- an opportunity thesis
- strategic options
- recommended AI worker routing
- copy-paste tool prompt packets
- competing analyst-banker teams
- human-only data requests for Bob
- a GitHub artifact plan
- Codex implementation instructions when useful
- an optional LinkedIn/public artifact plan
- the next three actions

Use it whenever the idea is still blurry, political, high-leverage, research-heavy, or likely to become a project.

## Tool Prompt Packets

A tool prompt packet is a self-contained instruction for one worker: ChatGPT Instant, GPT Thinking, Deep Research, Web Search, Codex, GitHub, LinkedIn, or Bob as a human data collector.

Each packet should say:

- what tool to use
- why that tool is being used
- the exact prompt to paste
- what inputs it needs
- what output to expect
- when to stop
- when to escalate back to Bob

Use [prompts/01_tool_prompt_packet_generator.md](prompts/01_tool_prompt_packet_generator.md) or [templates/tool_prompt_packet.md](templates/tool_prompt_packet.md) to create packets.

## Competing Analyst-Banker Teams

This system avoids one-model, one-answer thinking. For consequential work, run competing teams:

- Bull / Builder: finds the strongest version of the opportunity.
- Bear / Skeptic: finds the failure modes, weak evidence, and bad incentives.
- Operator / MVP: finds the smallest useful test or implementation path.

Each team has an analyst role and a banker role. Analysts produce evidence. Bankers produce options, recommendations, and narratives. The teams should disagree in useful ways.

Use [prompts/02_competing_deal_teams.md](prompts/02_competing_deal_teams.md) and [templates/deal_team_memo.md](templates/deal_team_memo.md).

## Investment Committee Packet

The Investment Committee compares banker memos. It does not simply average them. It identifies where teams agree, where they disagree, which assumptions matter, what evidence is missing, and what Bob must decide.

Use [prompts/03_investment_committee.md](prompts/03_investment_committee.md) and [templates/ic_decision_packet.md](templates/ic_decision_packet.md).

## Create a New Run

Create one folder per meaningful project:

```text
runs/YYYY-MM-DD-project-name/
```

Copy only the files you need from [templates/](templates/). A normal run might contain:

```text
00_crude_idea.md
01_meta_plan.md
02_tool_prompt_packets.md
03_team_A_bull_memo.md
04_team_B_bear_memo.md
05_team_C_operator_memo.md
06_ic_decision.md
07_human_decision.md
08_execution_log.md
```

Not every run needs every file. Preserve useful reasoning and decisions; do not create bureaucracy.

## How Codex Fits

Codex is the implementation worker. Use it after the decision question has been clarified and the output can be expressed as files, scripts, templates, tests, repo changes, or automation.

The best Codex task specs include:

- objective
- context
- files to create or modify
- exact requirements
- acceptance criteria
- things not to do
- tests or checks
- final summary requirements

Use [prompts/04_codex_executor.md](prompts/04_codex_executor.md) and [templates/codex_task_spec.md](templates/codex_task_spec.md).

## How LinkedIn Fits

LinkedIn is optional. It is for public communication after the work has produced a real artifact, decision, or lesson. Do not publish private reasoning, confidential data, or half-formed claims just because the work was interesting.

Use [prompts/05_linkedin_distiller.md](prompts/05_linkedin_distiller.md) after a project has a completed artifact, clear insight, and a reputation-safe public angle.

## Repository Map

```text
prompts/     Copy-paste prompts for running the workflow.
templates/   Concise run artifacts Bob can duplicate.
runs/        Project folders created during real work.
examples/    Realistic examples showing the workflow in motion.
```

## Fastest Path

1. Write a messy idea in a new run folder.
2. Paste it into the Entrepreneur Meta-Planner prompt.
3. Save the meta-plan.
4. Run the recommended tool prompt packets.
5. Generate competing banker memos.
6. Run the Investment Committee synthesis.
7. Make the human decision.
8. Send a precise Codex task spec for execution.
9. Decide whether the result deserves a public LinkedIn artifact.
