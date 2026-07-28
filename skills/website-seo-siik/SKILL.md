---
name: website-seo-siik
description: A reusable workflow for turning research reports and confirmed decisions into a complete website architecture, keyword map, internal-link system, content plan, technical SEO specification, and launch checklist.
version: 0.1.0-draft
status: draft
---

# Website SEO SIIK

## Purpose

Use this skill to plan and validate a content website from research to launch. It is designed to absorb future reports and confirmed conversation decisions without treating unverified claims as permanent rules.

## Scope

This skill covers:

- site positioning and search intent;
- page types and information architecture;
- keyword research, clustering, and page mapping;
- title, H1, heading, body, image, and metadata placement;
- internal links, hub pages, breadcrumbs, related-content modules, and orphan-page prevention;
- content briefs and article quality standards;
- canonical, robots, sitemap, hreflang, schema, performance, and indexation gates;
- pre-launch and post-launch validation.

## Source hierarchy

When sources conflict, use this order:

1. Explicit decisions approved by the user.
2. Current first-party data, official documentation, and verified site data.
3. Research reports supplied by the user and independently checked where required.
4. Repeatable test results from the target site.
5. General SEO practices.
6. Individual anecdotes and unverified claims.

Never convert a single case study, ranking correlation, or personal opinion into a mandatory rule without confirmation.

## Evidence labels

Every new rule added from future discussions must be marked as one of:

- **Confirmed rule** — approved and suitable for repeated use.
- **Project-specific rule** — valid only for a named site or business model.
- **Experiment** — testable hypothesis with a measurement plan.
- **Reference** — useful context, not an execution requirement.
- **Rejected** — considered but intentionally excluded.

## Standard workflow

1. Read the supplied report or brief.
2. Extract claims, recommendations, assumptions, examples, and missing information.
3. Separate confirmed facts from hypotheses and anecdotes.
4. Build or update the site brief.
5. Create the keyword universe and cluster it by search intent.
6. Assign one primary intent and one canonical target page to each keyword cluster.
7. Design the site hierarchy and URL structure.
8. Define page-level keyword placement and content requirements.
9. Build the internal-link graph and anchor-text rules.
10. Define technical SEO and indexation gates.
11. Produce implementation tasks and validation checks.
12. Record approved decisions in `DECISIONS.md` and update the relevant module.

## Required inputs

Use `INPUT_TEMPLATE.md`. Do not guess business-critical information such as domain, language, target audience, monetization model, official sources, or deployment authority.

## Required outputs

A complete run should produce:

- completed site brief;
- site architecture and URL map;
- keyword-to-page map;
- page briefs;
- internal-link plan;
- content production plan;
- technical SEO specification;
- launch checklist;
- decision log and unresolved questions.

## Non-negotiable safeguards

- One page must not target several unrelated search intents.
- Several pages must not intentionally compete for the same primary intent without a documented reason.
- Generated or imported content must be checked for unrelated brands, games, products, and topic contamination.
- Internal links must help users continue a task; they must not exist only to repeat exact-match anchors.
- New or uncertain pages should not be indexed merely because they exist.
- Ads, analytics, deployment, account systems, and indexing require their own project decisions.
- Do not fabricate traffic, keyword difficulty, rankings, conversion rates, or source authority.

## Module files

- `INPUT_TEMPLATE.md`
- `REPORT_INGESTION.md`
- `SITE_BUILD_WORKFLOW.md`
- `KEYWORD_MAPPING.md`
- `INTERNAL_LINKING.md`
- `CONTENT_STANDARDS.md`
- `SEO_VALIDATION.md`
- `DECISIONS.md`
- `templates/`

## Current maturity

This is a foundation only. The final rules will be expanded and frozen after the user supplies reports and approves the resulting decisions.
