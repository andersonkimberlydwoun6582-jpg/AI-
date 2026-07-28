# Internal Linking

## Purpose

Internal links should help users move to the next useful task while showing the relationship among hubs, supporting pages, tools, and entities.

## Base architecture

Use a layered model where appropriate:

```text
Homepage
  -> Primary hubs
      -> Supporting guides, tools, comparisons, or entity pages
          -> Closely related detail pages
```

Child pages should link back to their relevant hub through breadcrumbs, contextual links, or both.

## Required link types

- primary navigation for the most important sections;
- breadcrumbs for hierarchy and orientation;
- contextual body links where another page completes the user's task;
- related-content modules based on real topical relationships;
- hub-to-child links covering important pages;
- child-to-hub links reinforcing category membership;
- trust and legal links in stable navigation or the footer.

## Anchor-text policy

Use descriptive, varied anchors that accurately predict the destination.

Preferred examples:

```text
compare beginner character builds
see the complete item database
check the current game codes
learn how the scoring system works
```

Avoid:

- repeating the same exact-match anchor site-wide;
- unrelated anchors added only for keyword targeting;
- generic `click here` when a descriptive phrase fits;
- linking every occurrence of a keyword;
- hiding important links behind scripts or non-link elements.

## Context rules

A link is justified when the destination:

- answers a question raised in the current section;
- provides a deeper explanation;
- supports a comparison or decision;
- offers a tool, database record, or next step;
- clarifies a named entity;
- updates time-sensitive information.

## Link distribution

Prioritize relevance over a fixed number. Important pages should receive links from several relevant sections, not only from the footer or sitemap.

Do not create a rigid rule such as “every article must contain exactly N links.” Use page purpose, length, and available destinations.

## Orphan-page prevention

Before indexing a page, verify:

- it is reachable from at least one indexable HTML page;
- it belongs to a documented hub or user journey;
- it appears in the correct sitemap when indexable;
- its inbound anchors are accurate;
- it links onward where a useful next step exists.

## Related-content selection

Rank candidates using:

1. shared intent or task;
2. shared entities;
3. same category or lifecycle stage;
4. complementary rather than competing content;
5. freshness and current indexation state.

Do not recommend a page merely because it shares one keyword.

## Audits

Track at minimum:

- orphan pages;
- broken internal links;
- redirecting internal links;
- links to non-canonical URLs;
- excessive site-wide exact-match anchors;
- pages with no useful outbound path;
- hub pages missing important children;
- child pages linked from unrelated categories;
- multilingual links pointing to the wrong locale.

## Page-level link brief

```text
Page URL:
Parent hub:
Required inbound sources:
Required outbound destinations:
Recommended anchor concepts:
Breadcrumb path:
Related-content rules:
Links to avoid:
```
