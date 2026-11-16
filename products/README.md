# Products

Five products in catalogue v3. [catalogue, slide 2] unless marked otherwise.

| # | Product | Domain | One-line value | Status badge in catalogue |
| --- | --- | --- | --- | --- |
| 01 | [NMT Shield](nmt-shield/README.md) | Banking & finance | Financial fraud detection through risk scoring | "Déjà disponible" |
| 02 | [NMT KYC 360](nmt-kyc-360/README.md) | Banking & finance | Decision support for customer (KYC) risk assessment | none |
| 03 | [NMT SDR](nmt-sdr/README.md) | Administrative documents | Extraction and structuring of data from identity documents | "Projet phare" + "Produit finalisé, prêt à déployer" |
| 04 | [TeamPilot](teampilot/README.md) | Enterprises, banks, administrations | Sovereign, self-hosted conversational AI (local or cloud models) | "Projet phare" |
| 05 | [NMT 4n6](nmt-4n6/README.md) | Digital investigation | Digital forensics and centralised evidence handling | "Projet phare" + "Produit finalisé, prêt à déployer" |

## Reading the status column

The badges are the only maturity signal in the catalogue, and they are not a consistent scale:

- "Déjà disponible" (already available) and "Produit finalisé, prêt à déployer" (finished, ready to deploy)
  are readiness statements.
- "Projet phare" (flagship project) is a priority label, not a readiness statement. TeamPilot carries only
  this label, so its readiness is unknown.
- NMT KYC 360 has no badge. [inferred] It may be earlier-stage than the others, or the badge was omitted.
  Confirm with the company.

## Shared structure

Every product slide pair follows the same format: a "Fonctionnalités clés" slide (description and 3-5
features) and an "Avantages clés" slide (4-5 benefits). Each product file mirrors that, then adds
Unknowns to be filled in.

## Adding a product or a detail

Create `products/<slug>/README.md` using the same headings: Summary, Target user, Key features, Key benefits,
Status, Unknowns. Add the product to the table above.
