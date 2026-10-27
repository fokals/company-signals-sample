---
license: cc-by-4.0
pretty_name: Fokals company signals, October 2026 sample
language:
  - en
tags:
  - technographics
  - company-data
  - web-technology
  - ecommerce
  - hiring
  - b2b
size_categories:
  - n<1K
---

# Fokals company signals: October 2026 sample

The figures behind the findings of the [Fokals monthly reports](https://www.fokals.com/reports) for October 2026: which technologies websites run and how fast they spread, what online shops change on their storefronts, and how hiring shifts across industries.

Each finding links to its report, where the chart, the reading and the method sit beside the numbers.

The files are in `2026-10/`, as published on 27 October 2026. The October reports are brought up to date with the whole month in early November, and these files with them.

## Files

**findings.csv**: one row a finding.

| Column | What it holds |
| --- | --- |
| report | The report's address name, for example `monthly-2026-10` |
| report_title, edition | The report's title and month |
| finding_id, finding | The finding's id (its anchor on the report page) and name |
| takeaway | The finding in one sentence |
| trend | rising, spreading, starting, replacing or falling |
| signal_score | The finding's signal score, 0 to 10 (see [how to read a report](https://www.fokals.com/reports/framework)) |
| share_percent | How common the thing measured is, in percent |
| growth_percent_a_month | How fast it is growing, in percent a month |
| url | The finding on the report page |

**figures.csv**: the numbers of each finding's chart, one value a row.

| Column | What it holds |
| --- | --- |
| report, finding_id | Which finding the chart belongs to |
| chart, measure, unit | The chart's title, what it measures, and its unit (percent, ratio, points) |
| group | The chart's view or series, where it has more than one |
| label | The row: an industry, a technology, a role |
| period | The week or the before and after, where the chart compares |
| value | The number |

## Example questions it answers

- Which industries run Cloudflare, Klaviyo or Shopify the most?
- Which website technologies grew fastest in October 2026, and which fell?
- When did shops start naming Black Friday on their banners?
- Which roles grew as a share of job postings, by industry?

## Licence and credit

The figures are free to use under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit Fokals and link to the report the figure comes from, or to https://www.fokals.com/reports.

Citation: Fokals, October 2026 reports, https://www.fokals.com/reports

## More

New reports come out each month at [fokals.com/reports](https://www.fokals.com/reports). The same signals for any company, from your AI assistant or your own code: [fokals.com](https://www.fokals.com).
