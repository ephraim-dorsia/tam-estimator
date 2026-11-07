# TAM: US Marketing Agencies, 10–200 Employees

Research date: November 7, 2026. Confidence: low to moderate; useful for planning,
with unmeasured assumptions about service mix and reachability.

Scope: US-headquartered agencies delivering marketing services, including
blended marketing/design/development agencies. Exclude pure development and
pure design shops, freelancers, and internal marketing teams. Published
full-time-equivalent size bands proxy the requested employee count.

## Published inputs

| Input | Value | Evidence |
|---|---:|---|
| US digital agencies tracked | 65,000+ | [Promethean Research, Titan Agency Opportunity Map](https://prometheanresearch.com/titan-agency-opportunity-map/), accessed November 7, 2026; underlying observation date unspecified |
| US agencies with 10–49 FTEs | 31% | Same Titan source |
| US agencies with 50–249 FTEs | 10% | Same Titan source |
| North American marketing / blended shares | 19% / 64% | [Promethean Research, Digital Agency Industry Report](https://prometheanresearch.com/digital-agency-industry-report/), 2026 landscape |

Use 65,000 as a rounded anchor, not an exact census of all agencies. The 83%
combined service share is a proxy; its transfer to US firms of this size is
unverified. The report does not publish the joint distribution needed for an
exact answer.

Source attribution: Promethean Research, Digital Agency Industry Report,
https://prometheanresearch.com/digital-agency-industry-report. The report data
remain subject to its attribution and reuse terms, including retaining that
acknowledgment when redistributing those data or derived work.

## The math

| Factor | Low | Base | High | Status |
|---|---:|---:|---:|---|
| Share of the 50–249 band inside 50–200 | 80% | 90% | 95% | Assumed boundary allocation |
| Resulting 10–200 share | 39% | 40% | 40.5% | Calculated: 31% + 10% × allocation |
| Marketing-service share within that size range | 70% | 80% | 83% | Assumed; 83% anchored to the broader service mix |
| Reachable fraction of eligible companies | 75% | 85% | 90% | Illustrative sensitivity, not measured coverage |
| Relevant distinct buyers per reachable account | 1.5 | 1.8 | 2.0 | Assumed population average |
| **Eligible companies** | **~18,000** | **~21,000** | **~22,000** | Scoped account TAM |
| **Modeled reachable accounts** | **~13,000** | **~18,000** | **~20,000** | Eligible companies × reachable fraction |
| **Potential buyer contacts** | **~20,000** | **~32,000** | **~39,000** | Reachable accounts × buyers per account |

Base calculation, before rounding:

```text
65,000 × (0.31 + 0.10 × 0.90) = 26,000 digital agencies in the size range
26,000 × 0.80 = 20,800 eligible marketing agencies
20,800 × 0.85 = 17,680 modeled reachable accounts
17,680 × 1.80 = 31,824 potential buyer contacts
```

These scenarios vary selected assumptions. They are not confidence intervals
or strict lower/upper bounds; unknown source coverage and correlated factors
could put the actual count outside this range.

## Cross-check

The [Census 2022 SUSB detailed employment dataset](https://www.census.gov/data/datasets/2022/econ/susb/2022-susb.html)
contains 2,195 advertising-agency firms (541810) and 3,763 marketing-consulting
firms (541613) in disjoint 10–199 enterprise-employee bands. Their sum, 5,958,
is a count across those categories, not a deduplicated total for all marketing
agencies. Exactly 200 employees falls in a broader published band.

The two Census codes cover a different population from the digital-agency
dataset. Do not average or add these totals to the main model. The discrepancy
is a material definition and vintage limitation, not proof that either count
measures the user's exact market. See the [SUSB glossary](https://www.census.gov/programs-surveys/susb/about/glossary.html)
for firms, establishments, and enterprise size.

## Verdict

Under the broad marketing-services definition, the model suggests enough
headroom for an initial outbound test. Plan around approximately 18,000
reachable accounts and 32,000 potential buyer contacts, then replace the
illustrative coverage assumptions with a deduplicated sourcing sample. A
strict pure-marketing-only definition would produce a substantially smaller
market and needs its own calculation.

## Provisional buyer titles

Assuming the purchase is outsourced new-business support:

- Founder / Owner / CEO — likely economic buyer at smaller agencies.
- Managing Partner / President — likely economic buyer as the firm grows.
- Head of Growth / VP of Business Development — buyer or champion, depending
  on actual budget authority.
- COO — potential budget owner or operational champion.

## Key assumptions

- Blended agencies qualify when marketing is a client service. Restricting the
  definition to pure marketing changes the result most.
- National service-mix shares transfer to the selected US size cohort only
  approximately; joint size/service data would improve this estimate.
- FTE counts proxy employees, and the 200-person boundary is modeled.
- Reachability includes a combined allowance for duplicate buying authority,
  contact discovery, and practical account eligibility. No named list,
  suppression check, or email verification was performed.
- The source's tracked population and public size percentages may be rounded
  or incomplete. An actual company export and deduplication would provide
  stronger inventory evidence.
