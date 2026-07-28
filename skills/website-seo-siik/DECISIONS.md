# Decision Log

Record only decisions that have been explicitly approved or clearly established through verified evidence.

## Status values

- Proposed
- Approved
- Superseded
- Rejected
- Experiment

## Entry template

```text
ID:
Date:
Topic:
Status:
Decision:
Applies to:
Reason:
Evidence or source:
Implementation impact:
Validation impact:
Exceptions:
Supersedes:
Approved by:
```

## Initial decisions

### D-001

```text
Status: Approved
Topic: Knowledge baseline
Decision: Reports and conclusions supplied after creation of this skill are treated as the new working knowledge base. Earlier unrelated project history must not be silently imported into the skill.
Applies to: website-seo-siik
Implementation impact: Every new report must pass REPORT_INGESTION.md before its recommendations become rules.
```

### D-002

```text
Status: Approved
Topic: Skill maturity
Decision: Version 0.1.0 is a draft foundation, not a frozen standard.
Applies to: website-seo-siik
Implementation impact: Future conversations will expand and correct the modules before a stable release is tagged.
```
