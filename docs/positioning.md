# Positioning

Cross-product themes observed in the catalogue. [catalogue] unless marked [inferred].

## The portfolio in one view

Two clusters plus one cross-cutting platform:

| Cluster | Products | Common thread |
| --- | --- | --- |
| Financial-crime & compliance | NMT Shield, NMT KYC 360 | Risk scoring for banks: transactions (Shield) and customers (KYC 360), each with an API, a dashboard and alert/report tooling |
| Document & evidence processing | NMT SDR, NMT 4n6 | Turn unstructured inputs into structured, usable data: identity documents (SDR), digital evidence (4n6) |
| General-purpose AI platform | TeamPilot | Self-hosted conversational AI with agents, RAG and MCP, usable across the organisation |

[inferred] Shield and KYC 360 are natural cross-sell: same buyer (bank risk/compliance), same architecture
pattern (scoring API + dashboard). SDR feeds KYC 360 in principle (extracted identity data into customer risk
scoring), but the catalogue does not say they are integrated.

## Recurring promises

| Theme | Where it appears |
| --- | --- |
| Data sovereignty / local hosting | Deck headline; TeamPilot (local or sovereign cloud, "zéro trust") |
| Security and regulatory compliance | Shield, KYC 360, TeamPilot, 4n6 |
| Real-time / speed | Shield (real-time scoring), SDR (accelerated processing), 4n6 (accelerated analysis) |
| Fewer false positives / fewer errors | Shield, KYC 360 (false positives), SDR (data-entry errors) |
| Integration into existing systems | Shield (API), SDR, TeamPilot (connectors, API) |
| Scalability | TeamPilot, 4n6 |

## Differentiator the catalogue leans on

Sovereignty: hosting and control of data stay local, aimed at institutions that cannot or will not send
sensitive data to foreign public clouds [inferred from emphasis; the catalogue does not name competitors].

## Weaknesses in how the offer is currently presented [inferred]

- Benefits are qualitative. "Réduction significative des fraudes et des faux positifs" has no figure, baseline,
  pilot or customer behind it in this document.
- No proof points: no named customers, case studies, certifications or benchmarks.
- No pricing or commercial model (licence, subscription, per-seat, per-transaction, project).
- Readiness is inconsistent. See `products/README.md`: only some products carry a status badge.
- Five unrelated products under one brand, with two buyer personas, risk diluting the message.
