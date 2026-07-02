# Runs

A run is one project, question, or decision process. Use runs to preserve the reasoning that was actually useful, not to create paperwork.

Create a new run with this naming pattern:

```text
runs/YYYY-MM-DD-project-name/
```

Recommended structure:

```text
runs/YYYY-MM-DD-project-name/
├── 00_crude_idea.md
├── 01_meta_plan.md
├── 02_tool_prompt_packets.md
├── 03_team_A_bull_memo.md
├── 04_team_B_bear_memo.md
├── 05_team_C_operator_memo.md
├── 06_ic_decision.md
├── 07_human_decision.md
└── 08_execution_log.md
```

Not every run needs every file.

Use fewer files when the decision is simple. Use more files when the work is ambiguous, high-stakes, research-heavy, or likely to become a reusable artifact.

## Practical Run Flow

1. Start with `00_crude_idea.md`.
2. Paste the crude idea into the Entrepreneur Meta-Planner.
3. Save the output as `01_meta_plan.md`.
4. Run only the tool prompt packets that matter.
5. Save useful outputs, especially evidence and decisions.
6. Generate competing deal-team memos when the decision deserves disagreement.
7. Run the Investment Committee prompt.
8. Record Bob's final decision.
9. Use `08_execution_log.md` to track Codex work, GitHub changes, public artifacts, and follow-up decisions.

## After A Run

Use `templates/post_run_learning.md` after high-value runs.

Promote lessons only when they will improve future work: a better prompt, sharper template, clearer README instruction, or stronger example.

Do not update the repo after every small run. Small runs can simply end with a logged decision.

## What Belongs In A Run

Save:

- decision questions
- evidence summaries
- banker memos
- human data requests
- IC decisions
- Codex task specs
- final decisions
- execution notes

Skip:

- long chat transcripts with no decision value
- duplicate drafts
- generic advice
- unused prompt experiments
- public post drafts that were rejected for reputation or privacy reasons
