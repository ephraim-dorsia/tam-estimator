---
name: tam-estimator
description: Estimate addressable company counts and potential buyer contacts for a defined B2B niche, geography, and company-size range. Use for TAM estimates and outbound market sizing before building a lead list. Distinguish the total market from reachable accounts; financial revenue TAM is optional when requested.
license: MIT
---

# TAM Estimator

Produce a sourced, directional estimate of companies and buyer contacts. Here,
TAM means the account universe for a specified market; it does not automatically
mean annual revenue opportunity or a verified prospect list.

## Establish the scope

Use the user's niche, geography, and company-size definition. Ask for missing
details when they would materially change the estimate. Reuse context already
provided. A narrow niche does not resolve an unspecified geography or size gate.

State inclusions, exclusions, the counting unit, and the research date. For a
broad label such as "marketing agencies," explain whether blended agencies,
consultancies, design studios, and development shops qualify. Resolve ordinary
scope choices with a stated assumption; ask when competing interpretations would
change the user's decision.

Company size can mean enterprise employment, local establishment employment,
full-time equivalents, or a directory headcount band. Preserve the user's unit
and disclose any proxy. Do not silently turn a 10–200 employee request into
10–249 or 10–500.

## Find the best count

Use live web research when available. Prefer original statistics, industry
associations, and research organizations publishing their own observations.
Search the requested geography and the latest available release; distinguish
the data's reference year from its publication date. An older, exact-scope count
may be more useful than a newer count for a different population.

Choose a method that fits the evidence:

1. **Direct count:** Use published company counts matching the niche, size,
   and geography. Skip market-revenue and average-company-revenue calculations.
2. **Broader company count:** Apply explicit geography, size, and niche shares
   to a broader count. Source each share where possible. Otherwise show it as
   an assumption and test a plausible range.
3. **Revenue proxy:** If no useful count exists, divide revenue for the target
   segment by mean revenue per company in that same segment. Do not divide
   whole-industry revenue by a typical small firm's revenue. A median or the
   midpoint of a size range is not necessarily the mean. If the scopes cannot
   be aligned, report insufficient evidence instead of manufacturing a count.

For every important input record its value, source URL, reference year, unit,
and whether it is published, calculated, or assumed. Read the supporting source;
a search snippet or an inaccessible paywall does not verify the underlying data.
If browsing is unavailable, use supplied evidence or provide a clearly labeled
scenario with unverified inputs. Do not claim fresh research.

### Reconcile incompatible counts

- Firms, locations, licensed individuals, association members, directory
  listings, and provider search results measure different populations.
- Prefer companies for account TAM. Treat establishments as a proxy unless
  local branches actually purchase independently.
- Industry classifications may miss digital or blended businesses and may
  include adjacent services. Explain that mismatch before choosing a count.
- Do not add overlapping industry or directory totals as unique companies.
  Deduplicate if records are available; otherwise bound or model overlap and
  label the uncertainty. Do not add parent and subsidiary counts blindly.
- Sum disjoint size bands once; exclude subtotals. For a partially overlapping
  band, show a bound or an assumed allocation. Never imply the exact cutoff is
  published when it is not.
- Multiplying separate geography, size, and service-mix percentages assumes
  those shares transfer to the target segment. Flag that assumption when joint
  data is unavailable.
- When useful sources disagree, compare their year, population, and methodology.
  Do not average incompatible totals or hide the disagreement in one number.

## Separate the market from reachable inventory

Show these stages separately:

```text
Eligible companies = broader count × applicable segment shares
Modeled reachable accounts = eligible companies × reachable fraction
Potential buyer contacts = modeled reachable accounts × relevant buyers per account
```

The eligible-company count is the scoped account TAM. Reachable accounts are a
smaller planning estimate. Only call contacts verified or sendable when an
actual sourcing and verification run establishes that.

Use measured reachability when available. Otherwise show an illustrative
sensitivity range and explain what it covers, such as shared buying authority,
contact discoverability, and account eligibility. Do not turn a generic discount
into an observed fact. Do not reapply exclusions already reflected upstream.

Use one combined reachability factor when losses overlap. Apply multiple factors
sequentially only when each describes an additional loss in the remaining pool;
show the formula. Never simply add overlapping discounts.

Estimate relevant, distinct buyers per account. One founder may fill several
titles. A planning range of 1–2 can fit smaller companies; more stakeholders
need a reason. Fractional averages are acceptable across a population. Titles
and buyer counts depend on the offer: use supplied context, or state the assumed
purchase and make the suggestions provisional.

## Show uncertainty and the decision

If assumptions materially affect the result, show low, base, and high scenarios
with their inputs and arithmetic. These are planning scenarios, not statistical
confidence intervals. Keep exact arithmetic auditable and round the headline
results. Do not select a convenient single point merely to cross a viability
threshold.

Explain campaign headroom using unique accounts, buyer concentration, planned
new-contact volume, and replacement needs when known. About 10,000 potential
contacts can be a rough planning heuristic, never a universal pass/fail rule.
Two buyers at one account do not create two independent customer opportunities.

If the market is tight, suggest one or two specific scope expansions and identify
which original constraint would change. Keep the original estimate intact.

## Deliver the brief

Return the result in chat unless the user requests an artifact or an established
workflow supplies its destination. A useful brief contains:

- **TAM: niche** — geography, size, inclusions/exclusions, date, and confidence.
- **The math** — count, adjustments, eligible companies, reachable accounts,
  and potential buyer contacts, with sources beside published inputs and
  assumptions labeled beside estimated inputs. Omit unused revenue rows.
- **Scenarios** — low/base/high where needed, including the factors that change.
- **Verdict** — practical headroom and the main limit on the conclusion.
- **Target titles** — two to four likely roles, distinguishing the economic
  buyer from a champion when the offer is known.
- **Key assumptions** — the few uncertainties that most affect the result and
  what evidence would resolve them.

An example of a completed live-research run is in
[examples/us-marketing-agencies.md](examples/us-marketing-agencies.md). It is a
dated illustration, not a default input for future estimates.

## Scope of this skill

Market sizing does not authorize paid sourcing, enrichment, lead-list uploads,
outreach, campaign changes, or publication. Use public or supplied evidence for
the estimate and obtain the user's applicable authorization for any additional
action. Keep private business records out of public examples.
