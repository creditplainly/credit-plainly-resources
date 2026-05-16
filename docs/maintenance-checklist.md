# Maintenance checklist

Use this checklist when updating [credit-plainly-resources](https://github.com/creditplainly/credit-plainly-resources) or coordinating changes across the public GitHub cluster.

## Quarterly link review (every ~3 months)

- [ ] Open [official-consumer-credit-resources.md](official-consumer-credit-resources.md) and spot-check each government URL (HTTP 200, content still matches the description).
- [ ] Sample Credit Plainly deep links from [README.md](../README.md) and [topic-matrix.md](topic-matrix.md).
- [ ] Check sibling repos listed in [resource-cluster-map.md](resource-cluster-map.md) for broken cross-links.
- [ ] Update “last reviewed” date in official-resources doc if you changed links.

## Credit Plainly URL hygiene

- [ ] Compare linked paths against [`data/site-pages.json`](../data/site-pages.json) (maintainers regenerate from the private site registry when pages ship or retire).
- [ ] Remove or replace any link that returns 404 on production.
- [ ] Do **not** link to pages that are not published on the public site (loan silos, unreleased guides, commercial review stubs).
- [ ] For monitoring topics, link to [/credit-monitoring](https://www.creditplainly.com/credit-monitoring) hub—not alternate child URLs unless they are confirmed live on the site.

## Official source hygiene

- [ ] Prefer CFPB, FTC, AnnualCreditReport.com, IdentityTheft.gov, and bureau **dispute** portals.
- [ ] Avoid pasting unverified bureau phone numbers or mailing addresses in GitHub; link to official dispute pages instead.
- [ ] When FTC or CFPB reorganizes URLs, file a broken-link issue and update the directory.

## Anchor and tone review

- [ ] No repeated exact-match anchors (e.g., the same phrase linked ten times in one file).
- [ ] No hype: “instant,” “guaranteed,” “boost 100 points,” “delete everything.”
- [ ] Disclaimers still state: educational only; no outcome guarantees; accurate negatives generally remain.
- [ ] Search changed files for forbidden strategy terms (see [linking-policy.md](linking-policy.md)).

## Disclaimer and independence

- [ ] README still states: not legal advice, not financial advice, not credit repair services.
- [ ] No new product recommendations or “best” roundups slipped into lists.
- [ ] [CONTRIBUTING.md](../CONTRIBUTING.md) still rejects affiliate and commercial pitches.

## Before adding new Credit Plainly links

- [ ] Confirm the guide is published and appropriate for public reference.
- [ ] Pick **one** best-fit repo to update first (avoid duplicating the same new link block in every README the same day).
- [ ] Add a row to [topic-matrix.md](topic-matrix.md) if the topic is a common reader question.
- [ ] Regenerate [`data/site-pages.json`](../data/site-pages.json) from the private site registry when the public page set changes.

## After edits

- [ ] Read diff for accidental internal planning language.
- [ ] Commit with a clear message (e.g., `docs: refresh official FTC dispute links`).
- [ ] Notify maintainers of sibling repos if a shared URL pattern changed.
