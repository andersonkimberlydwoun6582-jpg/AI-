# SEO Validation

## Pre-index validation

Every indexable page should pass these checks.

### Identity and intent

- The URL, title, H1, content, category, and canonical describe the same page.
- The page has one documented primary intent.
- No unrelated brand, topic, product, or template residue appears.
- The page adds value beyond navigation or duplicated text.

### Crawl and indexation

- The intended status is explicit: index or noindex.
- Canonical points to the correct absolute production URL.
- Robots directives do not conflict across meta tags, headers, and robots.txt.
- Indexable pages are present in the correct sitemap.
- Non-indexable and redirecting URLs are excluded from indexable sitemaps.
- Important pages are reachable through crawlable HTML links.

### Metadata

- Title and description are unique and accurate.
- H1 is clear and consistent with the page intent.
- Open Graph and social images resolve on the production domain.
- Structured data matches visible content and uses valid URLs.

### Internal links

- No important orphan page exists.
- Internal links use canonical destinations.
- Broken and redirecting internal links are removed or corrected.
- Breadcrumbs reflect the documented hierarchy.
- Related links are topically useful rather than mechanically generated.

### Multilingual

- Locale codes and language labels are correct.
- Canonical and hreflang are self-consistent.
- Alternate pages are true equivalents.
- Incomplete fallback translations remain non-indexable.
- Language switching leads to the corresponding page when available.

### Experience and performance

- Mobile and desktop layouts do not overflow or hide essential navigation.
- Interactive elements work with keyboard and touch.
- Images have dimensions and do not cause avoidable layout shift.
- Critical content is not blocked by ads, consent layers, or scripts.
- Third-party scripts are limited and intentionally approved.
- Core page content remains usable when optional scripts fail.

### Content integrity

- Sources, dates, versions, and official links are current where needed.
- Claims are supported and uncertainty is disclosed.
- Generated or imported content has passed contamination and duplication scans.
- Trust and legal pages match the site's actual behavior.

## Site-wide audits

Track:

- status-code distribution;
- canonical conflicts;
- duplicate titles, descriptions, and H1s;
- orphan and low-linked pages;
- redirect chains and loops;
- broken assets and links;
- sitemap counts versus intended indexable counts;
- robots and noindex changes;
- hreflang errors;
- schema validation;
- page speed and layout shifts;
- unrelated-term contamination;
- content freshness and source-review deadlines.

## Launch gate

Production indexing should be enabled only after:

1. the official domain resolves correctly;
2. HTTPS and redirects are correct;
3. canonical URLs use the official domain;
4. preview or platform domains are not exposed as canonical targets;
5. the intended pages pass content and internal-link review;
6. robots.txt and sitemaps reflect the launch decision;
7. analytics and ads match explicit approvals;
8. trust and legal pages are present where required;
9. a production crawl finds no blocking defect.

## Post-launch checks

Immediately after launch and again after search engines recrawl:

- verify representative URLs return the intended status;
- inspect rendered canonical, robots, hreflang, and schema;
- confirm sitemap and robots availability;
- check analytics only when approved;
- monitor indexing, crawl errors, ranking queries, and internal-link changes;
- investigate unexpected traffic or ranking changes before attributing cause.

## Result format

```text
Check:
Status: pass / fail / warning / not applicable
Evidence:
Affected URLs:
Required action:
Owner:
Recheck date:
```
