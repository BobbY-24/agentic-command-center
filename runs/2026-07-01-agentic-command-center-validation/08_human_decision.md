# Human Decision

## Bob's decision

Approve the IC recommendation: `small test`.

Bob should not fully commit to the command center as his default workflow yet. He should also not park or simplify it before testing it on one more real project.

## Rationale

The repo has crossed the threshold from prompt library to usable operating kit: it has a front door, modes, decision outcomes, competing teams, an IC scorecard, and execution specs.

But the most important evidence is still missing: whether it helps Bob make better real decisions and ship better artifacts.

## Commitment

Bob will run one real research or career idea through Standard Mode within 45 minutes.

The test succeeds if it produces at least one of:

- a clearer decision than Bob had at the start
- a better Codex task spec
- a sharper research plan
- a justified decision to kill, park, or reframe the idea
- a public artifact plan that avoids overexposure

## Stop condition

If the next real run creates mostly ceremonial files and does not change the decision or artifact quality, Bob should simplify the system before adding any new prompts or templates.

## Concrete next action

Pick the next crude idea and create:

```text
runs/YYYY-MM-DD-real-project-name/00_crude_idea.md
```

Then run `prompts/00_entrepreneur_meta_planner.md` and keep the planning phase under 45 minutes.
