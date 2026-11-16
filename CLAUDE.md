# CLAUDE.md

Business workspace for Numidia Mind Technologies (NMT), an Algerian AI solutions vendor. See `README.md`
for layout.

## Rules

- Do not invent facts about the company: no customers, revenue, pricing, team size, technology choices,
  certifications or market figures unless a file in `sources/` or the user states them. Put gaps in
  `docs/open-questions.md`.
- Tag claims by origin: `[catalogue]` for statements from the product catalogue, `[inferred]` for
  conclusions drawn from it, `[user]` for facts the user gave directly. Add the tag when writing
  facts into `docs/` or `products/`.
- Marketing claims in the catalogue (e.g. "réduction significative des fraudes") are unquantified.
  Report them as claims, not as measured results.
- Never edit files in `sources/`. Add new ones; derive text extractions next to them.
- Keep product names exactly as published: NMT Shield, NMT KYC 360, NMT SDR, TeamPilot, NMT 4n6.
- Customer-facing deliverables are in French unless the user says otherwise; internal docs are in English.
- Commit on the branch assigned to the session; do not open pull requests unless asked.
