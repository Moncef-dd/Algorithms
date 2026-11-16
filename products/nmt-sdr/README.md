# NMT SDR

Extraction and structuring of information from administrative documents. [catalogue, slides 7-8]

"SDR" is not expanded anywhere in the catalogue.

## Summary

Module that automatically extracts the information in administrative documents (national ID card, passport,
driving licence) through a pipeline: **preprocessing → OCR → extraction → structured display**. It automates
data entry from official documents, reduces manual errors and speeds up administrative processes.

## Target user

Teams handling administrative or onboarding processes that capture identity-document data, including banks.
[inferred] The catalogue lists the domain as "Documents administratifs" with no named sector.

## Key features

1. **Automated document preprocessing.** Prepares documents before extraction.
2. **Intelligent OCR.** Reads the information in documents automatically.
3. **Reliable extraction.** Retrieves useful data with fewer input errors.
4. **Structured display.** Clear presentation of the information, ready to use.

## Key benefits (catalogue wording, as claims)

| Benefit | Claim |
| --- | --- |
| Intégration flexible | Fits existing administrative processes |
| Saisie automatisée | Fewer manual, repetitive tasks |
| Données fiabilisées | Fewer errors thanks to automated extraction |
| Traitement accéléré | Documents analysed and structured quickly |
| Multi-documents | ID cards, passports and driving licences supported |

## Status

"Projet phare" and "Produit finalisé, prêt à déployer" (finished product, ready to deploy). [catalogue, slide 7]

## Unknowns

- What the acronym stands for.
- Languages and scripts supported (Arabic, French, Latin and Arabic on the same document), and which
  countries' document formats.
- Accuracy per field and per document type; behaviour on poor scans and photos.
- Handling of MRZ and security features; any forgery or liveness checks (none claimed).
- Interfaces: API, web UI, or both. Output formats.
- OCR engine: in-house, open-source or third-party.
- Whether ready-to-deploy means deployed anywhere yet.
- Pricing model.
