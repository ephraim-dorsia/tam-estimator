# TAM Estimator

A reusable agent skill for sizing a B2B market before building an outbound list.
It estimates eligible companies, modeled reachable accounts, and potential
buyer contacts, with sources, visible assumptions, and scenario ranges.

## Use it

Install this repository's root folder as a skill using your agent's normal
skill installation workflow. The entry point is [SKILL.md](SKILL.md).

Example request:

> Use the TAM estimator for US marketing agencies with 10–200 employees.
> Include agencies that blend marketing with design or development.

The agent needs web research or supplied source material. No API keys, paid
data subscription, or scripts are required. This is an instruction-based skill;
your agent performs the research and calculations.

## Example and validation

The [US marketing-agency example](examples/us-marketing-agencies.md) records a
live research run on November 7, 2026. Its base scenario estimates about 21,000
eligible companies, 18,000 reachable accounts, and 32,000 potential buyer
contacts. These are modeled planning figures, not a verified contact inventory.

Validation combined one live research example, checks of skill format, local
links and arithmetic, and a manual review of common failure cases: missing
scope, incompatible revenue denominators, overlapping counts, employee-band
boundaries, and unavailable web access. One live example does not establish
accuracy across every niche or agent.

## Method

Prefer a direct company count. If the available population is broader, show the
filters and their evidence. Use a revenue proxy only when numerator and
denominator describe the same segment. Separate market size from reachability
and state uncertainty instead of manufacturing precision.

This skill does not build or send campaigns. It follows the user's scope and
authorization for any additional work.

## License

[MIT](LICENSE). Third-party research remains subject to its own attribution and
reuse terms; the license covers the original skill and explanatory text.
