# Example: Synthetic Neologism / LLM Benchmark Research

## Crude idea

Bob is interested in whether synthetic neologisms can benchmark how well LLMs infer meaning from context. The idea might become a research artifact, benchmark dataset, blog post, or GitHub repo.

## Decision question

Should Bob turn the synthetic neologism idea into a serious benchmark project, and what evidence is needed before building it?

## Deep Research prompt

```text
Research whether synthetic neologisms, nonce words, pseudowords, or invented terminology have been used to test language model reasoning, human language acquisition, semantic inference, or contextual learning.

Focus on:
- prior academic work
- related NLP benchmarks
- psycholinguistics methods
- LLM evaluation papers
- risks of benchmark contamination
- ways to evaluate contextual inference rather than memorization

Output:
- short literature map
- closest existing benchmarks
- gaps this project could fill
- methodological risks
- recommended benchmark design principles
- citations with links

Stop if the idea is already fully covered by an existing benchmark and explain the overlap.
```

## Web Search prompt

```text
Search the public web for recent examples of LLM benchmarks that test novel word inference, invented terms, synthetic vocabulary, nonce words, or contextual meaning.

Return:
- project name
- link
- what it tests
- how close it is to Bob's idea
- whether the dataset or code is public
- any public discussion or criticism

Prioritize current benchmarks, GitHub repos, papers with project pages, and evaluation suites released in the last three years.
```

## Bull team

Banker thesis: This could become a distinctive benchmark because invented terms create a clean way to test contextual reasoning instead of memorized facts.

Analyst assignment: Find evidence that current benchmarks fail to isolate contextual semantic inference.

Evidence needed:
- papers on benchmark contamination
- examples where LLMs rely on memorized terms
- existing nonce-word evaluation methods
- small pilot showing model differences on invented terms

Recommendation: Build a small pilot dataset with 50 synthetic terms across domains and test 3 to 5 models.

Risks: The benchmark may accidentally test prompt style, cultural priors, or puzzle-solving instead of semantic inference.

What would change our mind: Strong evidence that existing benchmarks already isolate this capability well.

## Bear team

Banker thesis: The idea is interesting but may be methodologically fragile. Invented words can become arbitrary riddles, and scoring may be subjective.

Analyst assignment: Identify validity threats and prior work that undermines the novelty claim.

Evidence needed:
- existing benchmarks with similar synthetic language tasks
- examples of LLMs gaming artificial tasks
- scoring reliability methods
- human baseline requirements

Recommendation: Do not build a public benchmark until the construct is sharply defined and scoring can be made reliable.

Risks: Bob spends time on a benchmark that researchers dismiss as toy-like.

What would change our mind: A pilot with clear scoring, human baselines, and model separation.

## Research Strategist team

Banker thesis: Treat this first as a research design problem, not a product or repo problem.

Analyst assignment: Translate the idea into hypotheses, task formats, scoring rubrics, and validity checks.

Evidence needed:
- taxonomy of neologism types
- sample generation rules
- human annotation plan
- leakage and memorization controls
- model evaluation protocol

Recommendation: Produce a research design memo before writing code.

Risks: Over-planning delays the quick pilot that would reveal whether the benchmark has signal.

What would change our mind: If a one-day pilot already demonstrates obvious signal and scoring clarity.

## Human data request

Why AI needs Bob: Bob must define what kind of reputation and artifact he wants: serious research note, public benchmark, playful demo, or LinkedIn thought piece.

What Bob should collect:
- 5 examples of invented terms he finds compelling
- 3 examples of model answers that feel clearly good or bad
- target audience: researchers, builders, investors, or general AI practitioners
- tolerance for public methodological criticism

How to collect it:
- Write a small set of terms and contexts.
- Test them manually on two models.
- Save outputs and score them informally.

Minimum useful version:
- 10 examples, 2 models, rough scoring notes.

Ideal version:
- 50 examples, 5 models, human baseline, scoring rubric, and error taxonomy.

Priority: High before public positioning.

How this will affect the decision:
- If the pilot shows clear differences and interpretable failures, proceed to benchmark design.
- If scoring feels subjective, reframe as a research essay or exploratory post.

## IC decision

Areas of agreement:
- The idea is promising but needs methodological discipline.
- A public claim should wait until there is a pilot artifact.
- Human judgment is needed to define what counts as a good inference.

Areas of disagreement:
- Bull wants a fast pilot dataset.
- Bear wants stronger validity work before public release.
- Research Strategist wants a design memo first.

Recommended decision:
Run a small pilot, but frame it as research design rather than a finished benchmark.

Next action:
Ask Codex to create a simple repo skeleton for `neologism-benchmark-pilot` with data schema, scoring rubric, sample cases, and an evaluation script stub.
