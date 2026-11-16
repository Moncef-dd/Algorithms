# Numidia Mind Technologies (NMT)

Working repository for the business: what it sells, to whom, and how it positions and grows.

Numidia Mind Technologies builds sovereign, secure, tailor-made AI products for banks, enterprises and
administrations. It is based in Kouba, Algiers (Algeria). Its customer-facing language is French.

This repository is a business workspace, not a single software project. Source code for individual
products is expected to live in its own repositories and be linked from `products/`.

## Layout

| Path | Purpose |
| --- | --- |
| `docs/company.md` | Who the company is, what it claims, contact details |
| `docs/positioning.md` | Pillars, value propositions, cross-product themes in the catalogue |
| `docs/open-questions.md` | What the catalogue does not tell us and needs a human answer |
| `products/README.md` | Portfolio overview and status matrix |
| `products/<name>/README.md` | One file per product: scope, features, benefits, status, unknowns |
| `sources/` | Original inputs, kept untouched, plus a text extraction of each |
| `CLAUDE.md` | Conventions for AI-assisted work in this repo |

## Conventions

- **Sourced vs. inferred.** Every fact is tagged with where it came from. Anything not in a source
  document goes under "Unknowns" or `docs/open-questions.md`, never into the facts.
- **Source files are immutable.** Add new inputs to `sources/`; do not edit existing ones.
- **Language.** Working docs are in English. Product names, taglines and quoted catalogue text stay in
  French as published.

## Current state

Scaffolded from `sources/Catalogue_produits_NMT_v3.pptx` (product catalogue v3). The catalogue is the only
input so far; it contains no pricing, customer, team, financial or technical-architecture information.
