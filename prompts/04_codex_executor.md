# Codex Executor Prompt

Copy and adapt this when asking Codex to implement a specific task.

```text
You are Codex. Implement the task below in the repository.

Objective:
[STATE THE OUTCOME, NOT JUST THE ACTIVITY]

Context:
[PASTE RELEVANT DECISION PACKET, META-PLAN, OR BACKGROUND]

Files to create or modify:
[LIST FILES OR DIRECTORIES]

Exact requirements:
[LIST CONCRETE REQUIREMENTS]

Acceptance criteria:
[LIST HOW WE KNOW THE TASK IS DONE]

Do not do:
[LIST SCOPE LIMITS, UNWANTED REFACTORING, STYLE CONSTRAINTS, OR PRIVATE DATA TO AVOID]

Tests/checks:
[LIST COMMANDS, MANUAL CHECKS, LINTING, RENDERING, OR REVIEW STEPS]

Final summary requirements:
When finished, summarize:
1. Files created or modified.
2. What changed.
3. How you verified it.
4. Any limitations or recommended next improvements.

Working rules:
- Inspect the repo before editing.
- Follow existing structure and style.
- Keep changes scoped to this task.
- Do not invent extra architecture unless needed to satisfy the acceptance criteria.
- If blocked by missing information, ask for the smallest specific input needed.
```
