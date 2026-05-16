# Public GitHub resource cluster map

Credit Plainly maintains a small set of public repositories that help U.S. consumers navigate credit reports, scores, disputes, and related topics in plain English. This map describes what exists today, what each repo is for, and what we are **not** building yet.

**Hub repository:** [credit-plainly-resources](https://github.com/creditplainly/credit-plainly-resources) (this repo).

---

## Existing repositories

| Repository | What it covers | Primary Credit Plainly pages it supports |
|------------|----------------|------------------------------------------|
| [credit-plainly-resources](https://github.com/creditplainly/credit-plainly-resources) | Central hub: official links, topic matrix, structured metadata | Cross-cutting; see [topic-matrix.md](topic-matrix.md) |
| [credit-report-dispute-starter-kit](https://github.com/creditplainly/credit-report-dispute-starter-kit) | Ordered dispute learning path, situation table | Free report, read report, dispute workflow, bureau guides, checklists |
| [credit-score-learning-path](https://github.com/creditplainly/credit-score-learning-path) | Score literacy sequence | Check score, ranges, FICO vs VantageScore, factors, build/improve credit |
| [credit-report-glossary-map](https://github.com/creditplainly/credit-report-glossary-map) | Term → short definition → guide links | Report/score glossaries, dispute and repair vocabulary |
| [credit-monitoring-basics-guide](https://github.com/creditplainly/credit-monitoring-basics-guide) | Monitoring vs reports vs scores vs freezes | [Credit monitoring hub](https://www.creditplainly.com/credit-monitoring), identity guide |
| [creditplainly/.github](https://github.com/creditplainly/.github) | Organization profile and repo index | Site hubs only |

Machine-readable cluster metadata: [`data/resource-cluster-map.json`](../data/resource-cluster-map.json).

---

## Recommended future repositories (only when site content is ready)

| Proposed repo | Why wait | Site pages that would unlock it |
|---------------|----------|----------------------------------|
| `accounts-not-recognized-guide` | Needs a dedicated published guide | Future `/credit-reports/accounts-i-do-not-recognize` (not on site today) |
| `identity-theft-consumer-workbook` | Avoid overlapping thin hubs | Consolidated freeze/alert guide when editorially distinct from existing identity article |
| `credit-report-error-workbook` | Only if downloadable worksheets add value beyond live checklist | `/resources/credit-report-error-checklist` already covers core intent |

We will **not** create repos whose main purpose is “remove collections,” pay-for-delete letters, loan comparisons, or product roundups.

---

## Repositories we should not create

| Idea | Reason |
|------|--------|
| “Best credit monitoring” or card comparison repos | Commercial comparison and disclosure burden |
| Loan / debt consolidation funnels | Out of scope for Credit Plainly education |
| Background check / tenant screening playbooks | Different permissible use and risk profile |
| People-search or reverse-phone tools | Misuse risk; not consumer credit education |
| One repo per keyword phrase | Thin doorway pattern; prefer depth in existing repos |

---

## How repos relate to the website

- **Deep links only** to guides that are live on [creditplainly.com](https://www.creditplainly.com).
- **Official sources** bundled in every topical repo (CFPB, FTC, AnnualCreditReport.com, IdentityTheft.gov, bureau dispute portals).
- **No paid placements** and no partner tracking URLs.

Maintainers: see [linking-policy.md](linking-policy.md) and [maintenance-checklist.md](maintenance-checklist.md). Page-level metadata: [`data/site-pages.json`](../data/site-pages.json).
