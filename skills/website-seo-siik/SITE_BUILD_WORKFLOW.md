# Site Build Workflow

## 1. Positioning

Define the site's primary job in one sentence. Clarify audience, search demand, business goal, and why the site deserves to exist.

Deliverables:

- positioning statement;
- audience segments;
- primary conversion or success action;
- trust requirements;
- excluded topics.

## 2. Search-intent model

Classify demand into practical intent groups such as:

- navigational or brand;
- informational;
- comparison or commercial investigation;
- transactional or tool-use;
- support, troubleshooting, or update intent.

Do not create a page merely because a phrase exists. Create a page when the intent deserves a distinct answer or experience.

## 3. Information architecture

Choose page types before writing content:

- homepage;
- category or hub pages;
- detail pages;
- guides or articles;
- comparisons;
- tools or calculators;
- glossary, wiki, or entity pages;
- trust and legal pages.

Keep important pages reachable through normal HTML links. Avoid relying only on search boxes, client-side filters, or generated sitemaps.

## 4. URL architecture

Use stable, readable, lowercase URLs. Keep one canonical URL for each page intent. Document redirects before changing live URLs.

Example patterns:

```text
/
/category/
/category/topic/
/guides/topic/
/tools/tool-name/
/compare/a-vs-b/
/about/
```

URL depth should follow user understanding, not arbitrary keyword repetition.

## 5. Page specification

Every indexable page needs:

- primary intent;
- primary keyword cluster;
- supporting entities and questions;
- unique title and H1;
- clear answer or functional value near the top;
- required evidence and sources;
- internal-link inputs and outputs;
- canonical and indexation state;
- last-reviewed information where freshness matters.

## 6. Build sequence

1. Create the route and content model.
2. Build the shared layout and navigation.
3. Implement the highest-value page template.
4. Add content or structured data.
5. Add internal-link modules.
6. Add metadata, canonical, robots, sitemap, schema, and language handling.
7. Validate responsive behavior, accessibility, performance, and contamination.
8. Keep preview and incomplete content non-indexable.
9. Review locally and in a preview deployment.
10. Enable production indexing only after the launch gate passes.

## 7. Launch boundary

Planning, code changes, PR creation, merging, deployment, analytics, ads, and indexing are separate actions. Do not assume authorization for a later action from approval of an earlier one.
