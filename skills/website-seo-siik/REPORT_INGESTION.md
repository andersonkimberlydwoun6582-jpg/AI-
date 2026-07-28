# Report Ingestion Protocol

Use this file whenever the user supplies a report, transcript, screenshot, spreadsheet, audit, or case study.

## Step 1: Extract

Separate the material into:

- factual observations;
- recommendations;
- assumptions;
- examples and case studies;
- metrics and dates;
- tools or data sources;
- unresolved questions;
- direct conflicts with existing rules.

## Step 2: Evaluate

For each important claim, record:

```text
Claim:
Source:
Date:
Scope:
Evidence type:
Confidence: high / medium / low
Can it be independently verified?: yes / no
Applies to: all sites / site type / named project only
Decision: confirmed rule / project-specific / experiment / reference / rejected
```

## Step 3: Reconcile

- Preserve the user's explicit decisions unless they are later changed.
- Flag contradictions instead of silently choosing one version.
- Treat time-sensitive platform, search, legal, software, and policy claims as requiring fresh verification.
- Do not turn correlation into causation.
- Do not generalize a single site's traffic or ranking result into a universal outcome.

## Step 4: Update the skill

Only confirmed decisions should be promoted into the execution modules. Each promotion must update:

1. the relevant module;
2. `DECISIONS.md`;
3. the version or changelog note;
4. any affected template or validation rule.

## Step 5: Preserve traceability

Every material rule should be traceable to one of:

- a user-approved decision;
- a named report section;
- official documentation;
- a reproducible test;
- a clearly marked experiment.

## Conversation summary format

After a topic is resolved, summarize it as:

```text
Topic:
Approved conclusion:
Applies to:
Implementation rule:
Validation rule:
Exceptions:
Source or reasoning:
Files to update:
```
