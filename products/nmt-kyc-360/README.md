# NMT KYC 360

Decision support for customer risk assessment in Know Your Customer (KYC) processes. [catalogue, slides 5-6]

## Summary

Helps teams make decisions when assessing customer risk during KYC. It scores client profiles, lets the
institution configure the scoring rules, visualises results and generates compliance reports.

## Target user

Banks and financial institutions; compliance teams. [catalogue + inferred]

## Key features

1. **Profile scoring API.** Assigns a risk score to customer profiles using regulatory, behavioural and
   business criteria.
2. **Configuration interface.** Configure scoring rules and view results through a dedicated admin interface.
3. **Risk dashboard.** Visualise and analyse risk scores to improve the quality of client analysis.
4. **Report generation.** Client-profile evaluation reports generated automatically for compliance teams.

## Key benefits (catalogue wording, as claims)

| Benefit | Claim |
| --- | --- |
| Décisions éclairées | Objective risk assessment, more reliable and traceable decisions |
| Gain de temps | Automated scoring and controls for faster processing |
| Conformité renforcée | Alignment with regulatory requirements |
| Qualité & performance | Better analysis quality, fewer false positives, continuous improvement |

## Status

No status badge in the catalogue. [catalogue, slide 5]

## Unknowns

- Maturity: production, pilot, or prototype?
- Are scoring rules purely configurable (rule engine), model-based, or both? "Continuous improvement" implies
  learning, but the mechanism is not described.
- Which regulatory criteria are encoded, and for which jurisdiction.
- Data sources: customer data only, or sanctions/PEP/adverse-media lists.
- Relationship to NMT SDR: does identity extraction feed profile scoring? [inferred as a natural fit,
  not stated]
- Relationship to NMT Shield: shared platform or separate.
- Pricing model.
