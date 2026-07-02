# Competing Deal Teams Prompt

Copy everything below into GPT Thinking after the decision question and basic context are clear.

```text
You are designing competing analyst-banker teams for Bob.

Your job is to create real disagreement before Bob commits. Each team should have a distinct thesis, evidence plan, and recommendation. Do not collapse the teams into a consensus. The Investment Committee will compare them later.

Project context:
[PASTE PROJECT CONTEXT]

Decision question:
[PASTE DECISION QUESTION]

Known evidence:
[PASTE EXISTING EVIDENCE OR SAY "NONE YET"]

Constraints:
[PASTE CONSTRAINTS]

Create at least these three teams:

1. Bull / Builder
- Finds the strongest version of the opportunity.
- Assumes the idea may be valuable if executed well.
- Must still name evidence gaps and risks.

2. Bear / Skeptic
- Finds the strongest case against the idea.
- Tests evidence quality, incentives, opportunity cost, and failure modes.
- Must still name what would make the idea attractive.

3. Operator / MVP
- Finds the smallest useful test, prototype, artifact, or decision path.
- Optimizes for speed, reversibility, and learning.
- Must still name what the test cannot prove.

Add any optional teams that would materially improve the decision:
- Research Strategist
- Career/Reputation Banker
- Product/Market Banker
- Technical Architect

For each team, produce:

Team name:

Banker thesis:
The strategic argument this team would make to Bob.

Analyst assignment:
The evidence this team's analyst must gather.

Evidence needed:
Specific evidence, sources, interviews, files, benchmarks, examples, or observations.

Assumptions:
Separate strong assumptions from fragile assumptions.

Recommendation:
What this team recommends Bob do.

Risks:
What could go wrong if Bob follows this team.

What would change its mind:
Name the evidence that would cause the team to revise or abandon its recommendation.

Quality bar:
- Make the teams genuinely disagree.
- Steelman each team.
- Do not let the Bear team become lazy negativity.
- Do not let the Bull team ignore evidence.
- Do not let the Operator team reduce the idea to a trivial task if the strategic stakes are real.

Finish with:
- Recommended order to run the teams
- Which team needs human data from Bob first
- Which team output should feed the Investment Committee
```
