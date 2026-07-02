# Tool Prompt Packets

## Packet 1: GPT Thinking

Tool: GPT Thinking

Purpose: Produce competing views and an IC decision for whether the command center deserves continued use.

Exact prompt:

```text
You are evaluating Bob's `agentic-command-center` repo as an operating system, not as a prompt library.

Decision question:
Should Bob keep using and developing this command center as a serious personal AI workflow system, or should he simplify/park it?

Context:
The repo includes START_HERE.md, run modes, an Entrepreneur Meta-Planner, tool prompt packets, competing deal-team prompts, an Investment Committee prompt, an IC scorecard template, post-run learning, templates, and examples.

Create three banker-team memos:
1. Bull / Builder: argue that the command center is a valuable compounding system.
2. Bear / Skeptic: argue that it risks becoming productivity theater.
3. Operator / MVP: recommend the smallest useful next test.

Then create an IC scorecard and choose exactly one outcome: kill, park, gather evidence, small test, commit, or reframe.

Keep the output concise and operational.
```

Expected output: Three team memos, an IC scorecard, and a decision.

Stop condition: Stop if the recommendation becomes generic process advice instead of a concrete decision.

Escalation trigger: Ask Bob if the decision depends on private career goals or actual friction from prior workflows.

## Packet 2: Codex

Tool: Codex

Purpose: Create the validation run as durable GitHub artifacts.

Exact prompt:

```text
Create `runs/2026-07-01-agentic-command-center-validation/` with the requested run files. Fill each file with realistic content that demonstrates the repo workflow. Do not add new global templates or prompts. Do not modify README or operating files unless absolutely necessary.
```

Expected output: A complete run folder with ten filled markdown files.

Stop condition: Stop when all files exist, no placeholders remain, and the IC decision has one concrete outcome.

Escalation trigger: Ask Bob if the run requires personal data about career goals, risk tolerance, or actual usage history.

## Packet 3: Bob As Human Data Collector

Tool: Bob

Purpose: Validate the workflow against lived usefulness.

Exact prompt:

```text
After using the command center on one real project, answer:
1. What decision did it clarify?
2. Which artifact changed the outcome?
3. Which artifact was unnecessary?
4. Did it produce a better Codex task, research plan, or public artifact?
5. Would you voluntarily use it again without being asked?
```

Expected output: A short post-run judgment that can feed `templates/post_run_learning.md`.

Stop condition: Stop after one real project; do not theorize across imaginary usage.

Escalation trigger: If the workflow feels useful but too heavy, trigger a simplification pass.

## Packet 4: GitHub

Tool: GitHub

Purpose: Store this run as the repo's first proof that the workflow can operate on itself.

Exact prompt:

```text
Review the validation run in `runs/2026-07-01-agentic-command-center-validation/` and confirm that it contains the crude idea, meta-plan, tool prompt packets, Bull/Bear/Operator memos, IC scorecard, IC decision, human decision, and execution log.
```

Expected output: A clean repository state with the run committed when Bob chooses to publish the change.

Stop condition: Stop once the run is stored and inspectable.

Escalation trigger: If the run suggests global repo changes, create a separate future task instead of mixing it into this validation.
