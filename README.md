<!-- solve-problem:9bab7ce6-7be3-4c83-807f-c46bcab67570 -->
# ALGO-000134: Linear-space lower bound for two-pass Max-Cut estimation

A [Tangle Solve problem](https://solve.tangle.tools/problems/9bab7ce6-7be3-4c83-807f-c46bcab67570).

Source verification label: unverified. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000134: Linear-space lower bound for two-pass Max-Cut estimation
- **Subfield:** Online algorithms and streaming
- **Open:** Prove that two passes over an adversarially ordered graph stream still require \(\Omega(n)\) space to approximate Max-Cut value within \(1/2+\varepsilon\).
- **Status:** The extra pass defeats important one-pass arguments; the stated lower bound remains open in Singer’s formulation.
- **Type:** impossibility
- **Why:** Separates the value of rereading data from retaining it.
- **Key works:** Singer (2025), *Nine Lower Bound Conjectures on Streaming Approximation Algorithms for CSPs*.
- **Related:** Data engineering—multipass processing under memory limits.
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-gpt6pro-reply-1

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "id": "ALGO-000134",
  "label": "unverified",
  "open_check_method": "openalex",
  "open_checked_at": "2026-10-11",
  "origin": "sourced",
  "source_kind": "fleet-census",
  "triage": "clean",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/9bab7ce6-7be3-4c83-807f-c46bcab67570?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000134.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000134)
