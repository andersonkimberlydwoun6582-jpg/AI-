# Keyword Mapping

## Objective

Turn keyword data into a page plan that satisfies search intent without creating cannibalization or thin pages.

## Required keyword fields

Use `templates/keyword-map.csv` and record:

- keyword;
- locale and country;
- search intent;
- topic cluster;
- parent topic;
- estimated demand and difficulty, with source and date;
- SERP observations;
- assigned URL;
- page type;
- primary or supporting status;
- content status;
- indexation decision.

## Clustering procedure

1. Normalize spelling, punctuation, singular/plural variants, and obvious duplicates.
2. Compare the actual result-page intent, not only lexical similarity.
3. Group phrases that can be satisfied by the same page and same dominant answer.
4. Split phrases when the user expects a different page type, task, audience, product, location, or freshness level.
5. Choose one canonical target page per cluster.
6. Record secondary phrases as supporting terms, not additional pages by default.

## Page ownership

Each indexable page should have:

```text
Primary cluster:
Primary intent:
Canonical URL:
Page type:
Main promise:
Supporting questions:
Related entities:
Competing internal URLs:
```

When two pages overlap, choose one action:

- merge them;
- narrow one page's intent;
- redirect the weaker page;
- keep both but document the distinct intent and internal-link relationship.

## Placement framework

Use the primary topic naturally in:

- the title when it improves clarity;
- the H1;
- the opening answer or product description;
- the URL when stable and readable;
- one or more relevant headings;
- image alt text only when it describes the image;
- internal anchors where natural;
- metadata and structured data where accurate.

Supporting terms belong in the sections that answer them. Do not force every phrase into every SEO field.

## Homepage and hub rules

The homepage normally targets the broad brand or category promise. It should route users to major tasks and hubs rather than competing with every detail page.

Hub pages should:

- explain the category;
- link to all important child pages;
- surface subtopics and decision paths;
- receive contextual links back from relevant children;
- avoid becoming a list with no unique value.

## Validation questions

- Does every valuable cluster have exactly one intended primary URL?
- Does every indexable URL have a documented cluster?
- Are several pages targeting the same primary phrase or intent?
- Are pages being created only because modifiers differ slightly?
- Does the chosen page type match the current result-page intent?
- Are demand and difficulty metrics dated and sourced?
