# Competitive landscape for an Algerian AI software vendor (fraud, KYC, ID OCR, sovereign conversational AI, digital forensics) — Algeria and Maghreb, state as of November 2026

Method note for the report writer (read before using these notes):
- Research date: 16 November 2026. Searches were run in French, English and Arabic-script queries.
- This session's network allowlist blocked direct page fetches for almost every news and vendor host (algeriatech.news, algerie-eco.com, menastartupdigest.com, cio-mag.com, biometricupdate.com, wearetech.africa all failed to resolve). Only github.com pages were fetched directly. Every other finding below rests on search-engine result summaries of the cited URL, not on a full read of the page. Treat exact wording, figures and dates as "per search summary" and re-open the URL before quoting.
- algeriatech.news appears repeatedly. It reads as strategy-style commentary, not primary reporting. Findings that rest only on it are flagged "(commentary, single source)".
- "No evidence found" means the searches run here returned nothing; it does not mean the vendor is absent from Algeria.

## 1. Fraud detection and AML transaction monitoring in Algerian banks: which solutions are deployed, and are there Algerian fraud/AML/RegTech startups?

### Takeaway
The only publicly documented card/switch platform in Algeria is BPC SmartVista (SATIM and Algérie Poste), and the only publicly documented AML tool at a named Algerian bank is SironAML at Société Générale Algérie; for every other global incumbent (NICE Actimize, SAS, Oracle FCCM, FICO Falcon, Feedzai, Featurespace, Fircosoft, Vneuron) no sourced Algerian deployment was found. No Algerian fraud/AML startup was found, while regulation tightened sharply in 2025-2026 (new AML regulation, KYC instruction 04-2026, FATF grey-list exit in June 2026), which implies open demand rather than an entrenched local competitor.

### Cited Findings

Card switch and interbank fraud layer (SATIM / GIE Monétique / Algérie Poste)
- BPC states that both Algérie Poste and the SATIM countrywide payment network are users of SmartVista; Edahabia–interbank interoperability went live on 5 January 2020. — [BPC blog](https://www.bpcbt.com/blog/bpc-facilitates-interoperability-in-algeria-millions-to-use-country-wide-network)
- BPC publishes a (gated) SATIM case study claiming SmartVista helped SATIM, the national switch, double card adoption; the fraud set-up is not described in the public part. — [BPC case study SATIM](https://www.bpcbt.com/case-study-satim)
- BPC sells a SmartVista Fraud Management module (real-time, cross-channel). No source confirms SATIM or Algérie Poste licensed this module. — [BPC risk and fraud management](https://www.bpcbt.com/smartvista-solutions/risk-fraud-management)
- Maghreb Emergent reports SATIM's platform-migration contract was signed with a MONETIX/BPC grouping, that the local partner Monetix SpA failed and BPC proposed a direct BPC–SATIM arrangement, and that the contract carried a 14-year maintenance commitment (article date not confirmed from the summary). — [Maghreb Emergent](https://maghrebemergent.news/fr/monetique-comment-la-satim-a-marie-bpc-aux-kouninef/)
- ProgressSoft announced deployment of an interoperable instant payments system at SATIM (title only; date not captured). — [ProgressSoft](https://www.progressoft.com/news/deployment-of-interoperable-instant-payments-system-at-satim)
- SATIM is described as upgrading with AI fraud detection, card tokenisation, biometrics and open APIs, with the interoperability network expected to reach 15 banks in 2026; no supplier is named (commentary, single source, 2026). — [algeriatech.news](https://algeriatech.news/?p=33968)
- SATIM is reported certified to personalise Visa and Mastercard cards in Algeria (headline only). — [Algérie Eco](https://algerie-eco.com/?p=330487)
- GIE Monétique said SATIM had acquired the interbank mobile-payment solution and was working toward Visa certification; the Banque d'Algérie sits on GIE Monétique's management committee. — [dzair-tube](https://www.dzair-tube.dz/en/algeria-gie-monetique-launch-of-mobile-payment-interoperability-in-2024/)
- HPS (Morocco) and Enigma announced an AI fraud-detection partnership integrated in HPS's payment platform (4 March 2025). No Algerian HPS PowerCARD client was found in searches. — [HPS press release](https://www.hps-worldwide.com/news-and-media/hps-and-enigma-join-forces-revolutionise-fraud-detection-ai)

AML / transaction monitoring / screening at named Algerian banks
- A Université de Béjaïa thesis on Société Générale Algérie lists "outils de filtrage des transactions et des clients" and "l'outil de profilage clientèle : l'application SironAML V.10" (thesis date not captured). — [Univ. Béjaïa thesis](https://www.univ-bejaia.dz/jspui/bitstream/123456789/4237/1/Blanchiment%20D%27argent.pdf)
- Banque Extérieure d'Algérie launched a tender for an anti-money-laundering IT solution (25 December 2013). Outcome not found. — [Financial Afrik](https://www.financialafrik.com/2013/12/25/algerie-la-bea-cherche-une-solution-informatique-contre-le-blanchiment/)
- Tunisian services firm Vitalis was reported in 2015 as engaged to implement AML / capital-flight software for an unnamed Algerian public bank. — [L'Economiste Maghrébin](https://www.leconomistemaghrebin.com/?p=126653)
- BADR Bank went live with ISO 20022 in partnership with Eastnets, described as the first financial institution in Algeria to do so (22 October 2025). This is payment messaging, not AML; no Algerian SafeWatch screening client is named. — [Business Wire](https://www.businesswire.com/news/home/20251022624893/en); [Eastnets BADR case study PDF](https://www.eastnets.com/hubfs/Sibos%202025%20Content/Case%20Studies%202025/Case%20Study%20-%20BADR%20-%20Algeria.pdf)
- Eastnets says SafeWatch Screening is installed in over 360 banks worldwide (12 November 2024). — [Business Wire](https://www.businesswire.com/news/home/20241112685712/en/SafeWatch-Screening-5-Eastnets-Sanction-Screening-Solution-Gains-Global-Momentum)
- BEA International Bank (the French subsidiary of BEA, not the Algerian parent) went live with Temenos core banking and Financial Crime Mitigation as SaaS. — [IBS Intelligence](https://ibsintelligence.com/ibsi-news/bea-international-bank-goes-live-with-temenos-saas-in-europe/); [The Paypers](https://thepaypers.com/fintech/news/bea-international-bank-goes-live-with-temenos-saas-in-france)
- Al Baraka Bank Algeria publishes an AML/CFT/proliferation-financing policy summary (June 2025); no tool is named in the summary seen. — [Al Baraka Algérie](https://www.albaraka-bank.dz/wp-content/uploads/2025/06/ملخص-سياسات-مكافحة-غسل-الأموال-وتمويل-الإرهاب-وتمويل-أسلحة-الدمار-الشامل.pdf)

Core-banking incumbents (their bundled AML/fraud modules are the default substitute)
- Al Salam Bank Algeria: Temenos T24 (2010); CNEP-Banque: Temenos T24 (2013), per a customer database. — [Apps Run The World, Al Salam](https://www.appsruntheworld.com/customers-database/customers/view/al-salam-bank-algeria-algeria); [Apps Run The World, CNEP](https://www.appsruntheworld.com/customers-database/customers/view/la-caisse-nationale-depargne-et-de-prevoyance-banque-cnep-algeria)
- Housing Bank Algeria selected Infosys Finacle to replace Sopra Banking Amplitude (core, trade finance, internet banking, analytics, Islamic banking). — [Finacle press release](https://www.finacle.com/news-room/press-release/housing-bank-algeria-selects-infosys-finacle-power-operations); [FinTech Futures](https://www.fintechfutures.com/bankingtech/housing-bank-algeria-in-tech-revamp-with-infosys-finacle)
- BDL deployed SAB's core banking software (January 2014). — [Retail Banker International](https://www.retailbankerinternational.com/news/algerian-bank-bdl-deploys-sabs-core-banking-software-230114-4164002/)
- Natixis Algérie (now Banxy) is an SBS (ex-Sopra Banking) Amplitude customer story (February 2026). — [SBS customer story](https://sbs-software.com/wp-content/uploads/2026/02/CUSTOMER-STORY-Natixis.pdf)
- BNH is to acquire a new banking information system (headline only). — [Algérie Eco](https://algerie-eco.com/?p=214835)

Regional vendors (Tunisia, Morocco, Jordan)
- Vneuron (Tunis): Reis Risk & Compliance suite (CDD, transaction monitoring, case management, FATCA). Claims 200+ clients in 28 countries across Europe, Africa and the Middle East. Named African wins: Atlantic Financial Group (Cameroon, Gabon, Comoros, Mali) and CBZ Bank (Zimbabwe). No Algerian client was found. — [PR Newswire, AFG](https://prnewswire.com/news-releases/atlantic-financial-group-afg-selects-vneuron-risk--compliance-technology-to-keep-growing-and-digitizing-its-operations-in-full-compliance-with-regulations-301227709.html); [The Anchor, CBZ](https://www.theanchor.co.zw/?p=10242); [Graces community listing](https://www.graces.community/outils/vneuron-risk--compliance)
- Vneuron funding: second round from the Tunisian American Enterprise Fund, amount undisclosed (12 April 2021); an aggregator lists total funding of about US$6.5m (unverified). Offices in France, Tunisia, Cameroon and Doha. — [WeeTracker](https://weetracker.com/2021/04/12/tunisias-vneuron-raises-funding-from-tunisian-american-enterprise-fund/); [AI ecosystem map](https://mindmaps.ai-ecosystem.org/map/firms/70411); [PR Newswire, Doha](https://prnewswire.com/news-releases/vneuron-the-global-software-vendor-opens-its-doors-in-doha-qatar-301483059.html)
- Vneuron profiled as a unified financial-crime compliance platform (22 June 2026). — [FinTech Global](https://fintech.global/2026/06/22/how-vneuron-is-tackling-financial-crime-through-unified-compliance-platforms/)
- ScreenEdge (Morocco): new platform dedicated to KYC and AML/CFT screening obligations (5 December 2025). No Algerian activity found. — [Médias24](https://medias24.com/2025/12/05/hazim-sebbata-explique-la-nouvelle-plateforme-screenedge-dediee-aux-obligations-lcb-ft-1589517/)
- NetGuardians was chosen by Bank of Africa (group) for internal and payment fraud prevention; not an Algerian deployment. — [IBS Intelligence](https://ibsintelligence.com/ibsi-news/bank-of-africa-chooses-netguardians-ai-software-to-reinforce-internal-and-payment-fraud-prevention/)

Regulatory demand drivers
- Banque d'Algérie Regulation 25-14 of 24 September 2025 amends the July 2024 AML regulation. — [Banque d'Algérie PDF](https://www.bank-of-algeria.dz/stoodroa/2025/10/REG-N%C2%B025-14-FR.pdf); [TSA](https://www.tsa-algerie.com/?p=293517)
- Banque d'Algérie Instruction 04-2026 (30 April 2026) fixes the KYC procedure for banks, financial institutions and Algérie Poste's financial services; described as a four-level control system; a study day followed. — [Algérie Eco, 4 May 2026](https://algerie-eco.com/2026/05/04/la-banque-dalgerie-publie-linstruction-fixant-la-procedure-kyc-applicable-aux-banques-etablissements-financiers-et-algerie-poste/); [Radio Algérie](https://news.radioalgerie.dz/fr/node/85371); [Algérie360](https://www.algerie360.com/algerie-la-banque-dalgerie-serre-la-vis-nouvelles-regles-kyc-pour-tous/)
- Algeria was removed from the FATF grey list at the June 2026 plenary (decision dated 19 June 2026), after listing in October 2024. — [bne IntelliNews](https://www.intellinews.com/algeria-and-namibia-exit-fatf-grey-list-six-african-states-remain-under-enhanced-monitoring-450317/); [Financial Afrik, 20 June 2026](https://financialafrik.com/en/2026/06/20/algeria-removed-from-the-fatf-grey-list-a-major-turning-point-for-the-countrys-financial-credibility/)
- Seven public banks (BEA, BNA, BADR, BDL, CPA, CNEP-Banque, BNH) hold about 86% of banking assets (commentary). — [The Fintech Times](https://thefintechtimes.com/algerias-fintech-ecosystem-in-2026-by-building-momentum/)

Open-source substitutes
- Marble (checkmarble): fraud and AML decision engine with real-time or post-trade transaction monitoring, sanctions/PEP screening, case manager; free self-hosted option plus licensed enterprise tier; 624 GitHub stars at fetch (16 November 2026). — [GitHub](https://github.com/checkmarble/marble)
- A directory states Marble is under Elastic License 2.0 (source-available, not OSI open source); GitHub metadata lists the licence as "other". — [awesome.ecosyste.ms](https://awesome.ecosyste.ms/projects/github.com%2Fcheckmarble%2Fmarble)
- Marble and OpenSanctions market a fully self-hosted screening plus monitoring stack (21 July 2026). — [OpenSanctions](https://www.opensanctions.org/articles/2026-07-21-marble/)
- Tazama: open-source real-time transaction monitoring for fraud and AML typologies (rules, typology and decision processors). — [GitHub tazama-lf/docs](https://github.com/tazama-lf/docs)

### Inferences
- The addressable competition for real-time transaction fraud scoring inside banks is mostly "module of the incumbent platform" (BPC SmartVista at switch level; Temenos FCM, SBS, Finacle, SAB add-ons at bank level) rather than a best-of-breed fraud vendor with a documented Algerian reference. This is an inference from the absence of sourced deployments.
- Foreign-owned banks probably run group-mandated tools (the SGA SironAML example), which makes them harder targets than public banks. SGA is the only sourced instance.
- Public banks hold ~86% of assets and the 2013 BEA tender shows AML tooling is bought by tender, so public procurement rules (see section 7) decide most of the market.
- Vneuron is the most credible regional competitor for KYC 360 and AML: francophone, Tunisian, 200+ clients, on-premise capable. Its Algerian presence is unverified.

### Gaps
- No source names the fraud engine actually running at SATIM, GIE Monétique or Algérie Poste; the BPC case study is gated.
- No sourced Algerian deployment found for: HPS PowerCARD, NICE Actimize, SAS, Oracle FCCM/Mantas, FICO Falcon, Feedzai, Featurespace, Fircosoft/LexisNexis, Siron/IMTF (other than SGA), Path Solutions iMAL, Vneuron, Eastnets SafeWatch. Presence of each is unverified, not disproved.
- Core systems and AML tools of BNA, CPA, AGB, Trust Bank, Gulf Bank Algeria were not found.
- Whether the 2013 BEA tender or the 2015 Vitalis project were delivered is unknown.
- Jube (open-source AML/fraud) was searched but nothing returned.
- No pricing found for any AML/fraud product in Algeria.

## 2. KYC/eKYC and identity verification vendors active in Algeria, the Maghreb and Africa; support for the Algerian biometric CNI, Arabic script and local hosting

### Takeaway
Remote onboarding is only starting in Algeria: the one documented bank deployment is Banxy (Natixis Algérie), reported as AI hosted fully in Algeria and linked by IDnow to its video-identification service, and the one local startup found is CORTIXIA (backed by a partnership with state accelerator Algeria Venture, no disclosed funding). Several global API vendors (Shufti, Didit, ID Analyzer, Innovatrics, Incode) list Algerian documents including the biometric CNI, but none was found with an Algerian client or local hosting.

### Cited Findings

Algerian deployments and local players
- Banxy (Natixis Algérie) offers fully online account opening: KYC form, photos of ID and proof of residence, selfie video; the AI solution is described as hosted entirely in Algeria and covers customer recognition, document authenticity and OCR (article reported as around January 2022). — [Algérie360](https://www.algerie360.com/creation-de-compte-bancaire-la-nouvelle-methode-de-natixis/)
- IDnow states Natixis Algérie is its first African customer for video identity verification (blog date not captured). Whether IDnow is the same locally hosted component is not confirmed. — [IDnow blog](https://idnow.io/blog/first-african-bank-launches-video-identity-verification)
- CORTIXIA, described as a local digital identity and KYC startup, entered a strategic partnership with state-backed Algeria Venture to accelerate market access in government and corporate sectors; sourced to LinkedIn; no investment amount disclosed. — [MENA Startup Digest](https://menastartupdigest.com/?p=44803)
- Algérie Poste ran a mandatory KYC data-update campaign for CCP holders, deadline extended to 31 March 2026; this is a declarative form, not biometric eKYC. — [Algérie360](https://www.algerie360.com/comptes-ccp-algerie-poste-repousse-lecheance-du-kyc-jusqua-cette-date/); [dzair-tube](https://www.dzair-tube.dz/en/algerie-poste-mandates-kyc-data-update-users-risk-access-suspension-after-march-31-algerias-national-postal-service-algerie-poste-has-announced-a-mandatory-update-of-customer-information)
- The Banque d'Algérie's list of authorised banking products (updated 14 May 2026) includes account opening among mobile-banking services. — [Banque d'Algérie](https://www.bank-of-algeria.dz/stoodroa/2026/06/RECUEIL-ACTUALISE-DES-PRODUITS-ET-SERVICES-BANCAIRES-AUTORISES-AU-14-05-2026.pdf)
- Intervalle Technologies (Algiers) is listed in Entrust's partner directory as a cybersecurity, audit, advisory and training consultancy, and in IBM's partner directory as a systems integrator. — [Entrust partner directory](https://www.entrust.com/partner-directory/intervalle-technologies); [IBM PartnerPlus](https://ibm.com/partnerplus/directory/company/5512)

Regulatory frame for eKYC
- Fintech Strategy 2024-2030 is said to set a 2026 target for digital identity verification for bank account opening; the enabling circular was not confirmed as issued (commentary, single source). — [algeriatech.news](https://algeriatech.news/algeria-digital-kyc-esim-banking-onboarding-fintech-2026/)
- Instruction 06-2025 (August 2025) creates the PSP framework with tiered wallets and escalating KYC. — [Launch Base Africa, 19 August 2025](https://launchbaseafrica.com/2025/08/19/algeria-opens-for-fintech-new-psp-rules-create-a-playbook-for-payments-startups/)
- A draft law approved by the Council of Ministers creates a national digital identification framework anchored on the biometric ID card and updates the 2015 e-signature law (date and adoption status not confirmed). — [We Are Tech Africa](https://www.wearetech.africa/fr/fils/actualites/tech/l-algerie-modernise-sa-loi-sur-les-transactions-electroniques-et-l-identite-numerique)
- A vendor page says Executive Decree 26-163 replaced the 2023 rules, extending them to legal arrangements with yearly confirmation (vendor marketing page; unverified). — [Shufti Algeria page](https://shuftipro.com/supported-countries/algeria/)

Foreign vendors that publicly list Algerian document coverage (no Algerian client found for any)
- Shufti: covers the biometric national ID (CNIBE), says it reads the chip over NFC, runs forensic layers and biometric liveness. — [Shufti](https://shuftipro.com/supported-countries/algeria/)
- Didit: lists CNIBE, biometric passport, driving licences and residence permits; describes OCR of the 18-character NIN. — [Didit Algeria](https://didit.me/solutions/countries/algeria/)
- ID Analyzer: lists six Algerian documents (passports, driving licences, ID cards including the 2016 card) with OCR, MRZ, authenticity checks, face match and AML screening. — [ID Analyzer](https://idanalyzer.com/en/supported-documents/algeria)
- Innovatrics: lists the Algerian identity card (2016) as OCR-supported. — [Innovatrics docs](https://developers.innovatrics.com/digital-onboarding/docs/functionalities/document/supported-documents/)
- Incode: has an Algeria (DZA) section in its Africa supported-IDs table (rows not seen). — [Incode docs](https://developer.incode.com/general-reference/supported-ids-africa.md)
- Sumsub publishes a supported-identity-documents list; Algeria coverage was not confirmed from the summary. — [Sumsub docs](https://docs.sumsub.com/docs/qes-supported-identity-documents)
- The biometric card was introduced in 2016 and carries a chip. — [Wikipedia](https://en.wikipedia.org/wiki/National_identity_card_(Algeria))

Maghreb and regional players
- Thinkneo (Tunisia, founded 2024 by Leith Mokaddem and Sarah Ksibi): Avatar-ID combines document recognition, OCR, face biometrics and Arabic–Latin transliteration; clients include Ooredoo and Tunisian banks; founders say they are prospecting Algeria and Libya (Managers.tn 27 February 2026; Forbes Afrique). — [Forbes Afrique](https://forbesafrique.com/face-aux-deepfakes-thinkneo-parie-sur-le-jumeau-numerique/); [Managers.tn](https://managers.tn/2026/02/27/thinkneo-lidentite-numerique-tunisienne-face-a-la-fraude/); [We Are Tech Africa](https://www.wearetech.africa/fr/fils/solutions/tunisie-avatar-id-automatise-la-verification-des-clients-a-distance)
- VOVE ID (Morocco, founded 2024): KYC/KYB platform; undisclosed seed from The Baobab Network (April 2025) to expand across MENA and Africa; publishes Algeria KYC/KYB/AML compliance guides, which signals marketing aimed at Algeria. — [Wamda](https://www.wamda.com/2025/04/moroccos-vove-id-secures-fresh-funds-support-expansion-ambitions); [VOVE ID Algeria guide](https://blog.voveid.com/kyc-compliance-in-algeria-2025-guide-to-identity-verification-aml)
- Digified (Egypt) obtained FRA approval for digital identity/eKYC; Valify (Egypt) offers a document SDK; neither shows Algeria activity. — [Daba Finance](https://dabafinance.com/fr/nouvelles/digified-fra-approbation-identit--num-rique-ekyc-egypte); [Valify docs](https://valify.gitbook.io/valify-ios-sdk-documentation/dockit/overview)
- Vneuron (see section 1) also sells KYC/CDD.

Pricing signals (per-check SaaS)
- Sumsub: about US$1.35 per verification (Basic, US$149/month minimum) and US$1.85 (Compliance, US$299/month minimum); AML monitoring add-on US$0.08 per check. Onfido (Entrust): unpublished, estimated US$2–3 per check. Veriff: from US$0.80. Jumio: estimated US$3–5. Third-party comparison sites, mid-2026. — [Tech Insider](https://tech-insider.org/igt-smoke-onfido-vs-sumsub-resume-2026/); [Tech Insider, 4-way](https://tech-insider.org/igt-sumsub-vs-onfido-vs-jumio-vs-veriff-for-igaming-kyc-202-en-d169/); [CostBench](https://costbench.com/software/kyc-aml/sumsub/hidden-costs/)

### Inferences
- Foreign eKYC APIs are SaaS hosted abroad and billed in foreign currency per check. Under Law 18-07 transfer rules and the services-import authorisation regime (section 7), they are structurally hard for Algerian banks to buy, which is why the Banxy article stresses in-country hosting.
- Chip (NFC) reading of the CNIBE is claimed by Shufti only. Whether third parties can actually access the Algerian card's chip data groups without state keys is not established by any source seen.
- CORTIXIA is the closest like-for-like local competitor to KYC 360 and SDR and has state-accelerator sponsorship into government accounts.

### Gaps
- No Algeria-specific evidence found for Smile ID, uqudo, Onfido/Entrust, Regula, Sumsub or Jumio (clients, document lists, or local partners). Entrust's link to Onfido plus the Intervalle partnership is an unverified possible channel.
- CORTIXIA's founders, founding year, product details, hosting model and clients were not retrievable (page blocked).
- No evidence of telecom SIM-registration eKYC vendors (Djezzy, Mobilis, Ooredoo Algeria) or of an Algérie Poste biometric onboarding project.
- No source confirms any vendor's handling of Arabic-script fields on Algerian documents specifically, other than vendor marketing claims.
- Date and current status of the Banxy/IDnow arrangement not verified.

## 3. ID document OCR: commercial SDKs, open-source options, and Algerian or Maghreb OCR / Arabic-document startups

### Takeaway
No Algerian startup dedicated to ID-document OCR was found; the competition is (a) global SDKs sold on annual licences sized by verification volume, a handful of which list Algerian documents, and (b) free open-source OCR, notably PaddleOCR (Apache-2.0, Arabic supported). The local differentiator available is on-premise deployment plus tuning for Algerian document layouts, since cloud OCR APIs imply cross-border data transfer.

### Cited Findings
- Regula Document Reader SDK: licence types are Mobile, Online and Software; pricing is an annual licence driven mainly by the number of document and face verifications in the package; with third-party readers only an annually updated fixed-cost licence is offered. No public Algerian document list was found. — [Regula licensing docs](https://docs.regulaforensics.com/develop/doc-reader-sdk/overview/licensing/); [Regula pricing models](https://support.regulaforensics.com/hc/en-us/articles/360036943712-Pricing-SDK-Licensing-Models); [Regula ID verification](https://regulaforensics.com/id-verification)
- A Regula comparison blog cites 915 supported documents for Microblink BlinkID and 944 for BlinkID Verify (competitor-authored; Algeria coverage not stated). — [Regula vs Microblink](https://regulaforensics.com/blog/regula-vs-microblink/)
- OCR Studio expanded web-based ID scanning to Arabic identity documents (October 2025). — [Biometric Update](https://www.biometricupdate.com/202510/ocr-studio-expands-web-based-id-scanning-to-arabic-identity-documents)
- Vendors listing Algerian ID OCR: Innovatrics (ID card 2016), ID Analyzer (six documents), Didit (CNIBE, 18-character NIN), PixLab DOCSCAN (Algeria ID entry). — [Innovatrics](https://developers.innovatrics.com/digital-onboarding/docs/functionalities/document/supported-documents/); [ID Analyzer](https://idanalyzer.com/en/supported-documents/algeria); [Didit](https://didit.me/solutions/countries/algeria/); [PixLab](https://pixlab.io/id-scan-api/docscan)
- Smart Engines publishes a supported countries and documents list (Algeria entry not confirmed). — [Smart Engines](https://smartengines.com/supported-countries-documents)
- PaddleOCR: Apache-2.0, 92.8k GitHub stars, 100+ languages, Arabic added in the PP-OCRv5 multilingual update, version 3.7.0 released 11 June 2026 (fetched 16 November 2026). — [GitHub PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
- A comparison notes some OCR tools do not handle non-Latin alphabets such as Arabic. — [Klippa](https://www.klippa.com/fr/blog/informations/meilleurs-logiciels-ocr-france/)
- Tunisian Thinkneo's Avatar-ID includes OCR with Arabic–Latin transliteration and is prospecting Algeria. — [We Are Tech Africa](https://www.wearetech.africa/fr/fils/solutions/tunisie-avatar-id-automatise-la-verification-des-clients-a-distance)
- Banxy's onboarding stack includes OCR and is described as hosted entirely in Algeria. — [Algérie360](https://www.algerie360.com/creation-de-compte-bancaire-la-nouvelle-methode-de-natixis/)
- No major hyperscaler (AWS, Azure, Google Cloud) operates a data-centre region in Algeria as of 2026 (commentary, single source). — [algeriatech.news](https://algeriatech.news/?p=25799)

### Inferences
- Google Document AI and Azure Document Intelligence would process Algerian ID images outside Algeria (no in-country region), triggering the ANPDP transfer-authorisation requirement in section 7. This makes them weak substitutes for regulated buyers, strong ones for unregulated buyers.
- The realistic substitute for a paid local OCR product is an in-house build on PaddleOCR or similar by a bank IT team or integrator. The moat is accuracy on Algerian CNIBE, passport and driving-licence layouts and bilingual Arabic/Latin fields, not the OCR engine.

### Gaps
- Not researched to source level: ABBYY, Anyline, Mindee, Google Document AI, Azure Document Intelligence pricing and Algerian coverage; Tesseract, docTR and open-source MRZ readers (PassportEye and similar). These exist but no citation was collected here.
- Microblink's actual Algerian document list and pricing not found.
- No accuracy benchmarks on Algerian documents from any vendor.
- No Algerian or Maghreb startup focused purely on Arabic document OCR was found.

## 4. Sovereign / self-hosted conversational AI: open-source platforms, commercial private-AI offers, Algerian / Maghreb / Arab vendors and telco or cloud offers; trademark risk on the name "TeamPilot"

### Takeaway
The strongest substitutes are free, mature open-source stacks (Open WebUI, Dify, AnythingLLM, LibreChat, Onyx) that already ship agents, RAG and MCP, plus Mistral's self-hostable Le Chat Enterprise; in Algeria the visible activity is infrastructure and models (Djezzy/Taubyte/Algeria Venture's AventureCloudz, Algérie Télécom's Oran AI data centre, Fentech's Hadretna LLM, Nojoom.ai's SaaS assistants), not a packaged self-hosted enterprise assistant. There is an existing German product "Teampilot AI" (teampilot.ai) in the same category, which is a real naming-confusion risk.

### Cited Findings

Name collision
- Teampilot AI (teampilot.ai): described as a ChatGPT-like all-in-one AI platform for companies and teams (team collaboration, AI writing, workflow automation, image generation, web crawling); Germany-based, English and German; listed company Techstack GmbH, founded 2023; subscription listed at US$15–50 per month with a limited free version. — [AlternativeTo](https://alternativeto.net/software/teampilot-ai/about); [SoftwareWorld](https://www.softwareworld.co/software/teampilot-ai-reviews/)
- Adjacent names in the same category: TeamCopilot, TeamAI, PilottAI. — [G2 TeamCopilot](https://www.g2.com/products/teamcopilot/reviews); [TeamAI](https://platform.teamai.com/pricing/); [G2 PilottAI](https://www.g2.com/products/pilottai/reviews)

Open-source substitutes (GitHub pages fetched 16 November 2026)
- Open WebUI: 158.8k stars; ships under the "Open WebUI License", which requires preserving Open WebUI branding. — [GitHub](https://github.com/open-webui/open-webui)
- Dify: 161.3k stars; Dify Open Source License (Apache 2.0 with additional conditions); visual workflows, RAG pipeline, agents with MCP servers, many LLM providers including self-hosted. — [GitHub](https://github.com/langgenius/dify)
- AnythingLLM: 68.3k stars; MIT; RAG document chat, no-code agents, MCP compatibility, multi-user in the Docker version. — [GitHub](https://github.com/Mintplex-Labs/anything-llm)
- LibreChat: 47.2k stars; MIT; MCP, agents, RAG via a separate RAG API, OAuth2/OpenID login. — [GitHub](https://github.com/danny-avila/LibreChat)
- Onyx (ex-Danswer): 33.4k stars; MIT community edition plus paid enterprise edition; agentic RAG, deep research, custom agents, MCP. — [GitHub](https://github.com/onyx-dot-app/onyx)

Commercial private-AI offers
- Mistral Le Chat Enterprise has three deployment models: Serverless, Cloud (dedicated VPC) and Self-Hosted running entirely in the customer's environment. — [Mistral help center](https://help.mistral.ai/en/articles/347541-is-le-chat-enterprise-only-saas-or-can-i-deploy-it-on-my-own-infrastructure); [Mistral announcement](https://mistral.ai/news/le-chat-enterprise)
- Mistral does not publish enterprise pricing; third-party sites list Pro at US$14.99/month and Team at US$24.99/month (unverified). — [CostBench](https://www.costbench.com/software/ai-chatbots/le-chat-mistral/)
- Microsoft 365 Copilot: US$30 per user per month (enterprise add-on, annual); Copilot Business US$21, promotional US$18 through 31 December 2026; Microsoft 365 E7 at US$99 per user per month from 1 May 2026 (third-party sources). — [IntuitionLabs](https://intuitionlabs.ai/articles/microsoft-copilot-pricing-licensing); [SoftwareOne, 26 May 2026](https://www.softwareone.com/en/channel-partner/articles/2026/05/26/lower-copilot-prices-bigger-partner-opportunity)

Algerian infrastructure, models and vendors
- AventureCloudz: announced 29 April 2026 by Djezzy, Algeria Venture and Taubyte; full-stack AI development cloud for developers, startups and enterprises, hosted in Algeria on Djezzy's cloud, built on Taubyte's open-source Git-native technology. No pricing or model stack published. — [Developing Telecoms](https://developingtelecoms.com/telecom-technology/enterprise-ecosystems/20197-djezzy-taubyte-and-algeria-venture-launch-ai-development-platform.html); [TechAfrica News, 30 April 2026](https://techafricanews.com/2026/04/30/djezzy-unveils-ai-cloud-platform-in-landmark-partnership-with-algeria-venture-and-taubyte/); [allAfrica](https://fr.allafrica.com/stories/202604300542.html)
- Djezzy signed a sovereign-cloud partnership with Armonika (domestic virtualisation and orchestration software) under Algeria Venture (24 August 2026); Djezzy says it already operates its own sovereign cloud. — [Algérie Eco](https://algerie-eco.com/2026/08/24/developpement-du-cloud-souverain-en-algerie-partenariat-entre-djezzy-et-armonika-sous-legide-de-algeria-venture/)
- Algérie Télécom launched construction of an AI-dedicated data centre in Oran on 16 March 2025, presented as the country's first GPU compute centre; the minister asked for it to host AI startups. — [Algérie Eco, 17 March 2025](https://algerie-eco.com/2025/03/17/algerie-un-premier-centre-de-calcul-pour-lintelligence-artificielle-dote-de-gpu/); [TSA](https://www.tsa-algerie.com/lalgerie-lance-son-premier-data-center-dedie-a-lia/)
- Algérie Télécom committed a DZD 1.5bn (about US$11m) fund for AI, cybersecurity and robotics startups. — [Techsoma](https://techsoma.africa/algeria-invests-11m-in-ai-startups-to-drive-digital-innovation/)
- Hadretna: LLM project by Algerian-French startup Fentech with Prof. Merouane Debbah, pre-trained on 2 billion tokens of Darija and Tamazight, with public crowdsourcing at hadretna.ai; company page lists founding in 2024. — [Algérie360](https://www.algerie360.com/hadretna-lintelligence-artificielle-au-service-des-dialectes-algeriens/); [Middle East AI News](https://www.middleeastainews.com/p/north-african-ai-large-language-model-data)
- Nojoom.ai: enterprise SaaS with Thuraya (Arabic enterprise search), Suhail (document analysis) and Nitaq (contextual assistant for enterprise workflows), reported as built on Gemini 1.5 Pro (commentary, single source). — [algeriatech.news tag page](https://algeriatech.news/tag/nojoom/); [algeriatech.news](https://algeriatech.news/?p=27871)
- PACAH: "sovereign augmented intelligence" decision-support concept presented in Algiers on 6 April 2026 (Builders Confluence forum) by Kacem Aityalla; positioned as human-centred decision aid rather than generative AI; no technical documentation found. — [CIO Mag](https://cio-mag.com/pacah-presentation-a-alger-dune-nouvelle-generation-dintelligence-augmentee-souveraine/); [Maghreb Emergent](https://maghrebemergent.news/fr/pacah-lalternative-humanocentree-face-a-la-course-folle-vers-lia-generative/)
- Policy: inter-ministerial AI roadmap focused on sovereign open-source models, compute, national data storage and safeguards for government use (13 August 2026); government reviewed the draft national AI strategy (May 2026); first AI and cybersecurity startup cluster inaugurated 20 April 2026 at Sidi Abdellah. — [MEA Tech Watch](https://meatechwatch.com/2026/08/13/algeria-adopts-inter-ministerial-ai-roadmap-focused-on-sovereign-models-compute-and-public-services/); [Radio Algérie](https://news.radioalgerie.dz/fr/node/86941); [Capmad](https://www.capmad.com/article/algerie-un-premier-cluster-ia-et-cybersecurite-pour-structurer-lecosysteme-startup)
- Algeria is said to be mobilising 52 universities, research centres and startups for models in Arabic, Darija and Tamazight; a suggested RFP clause set is data residency in Algeria, Arabic/Tamazight benchmarks and alignment documentation (commentary, single source, 2026). — [algeriatech.news](https://algeriatech.news/sovereign-ai-models-algerian-values-culture-2026/)
- A public-service AI launch by the Algerian state was reported (headline only). — [ITWeb Africa](https://itweb.africa/article/algeria-launches-public-service-ai/lwrKxv3Y1oyMmg1o)

Maghreb and Gulf
- Morocco and Mistral AI: MoU in September 2025; first open-source Darija tools (dialect identification classifier and a Voxtral-based speech recognition model) announced 29 September 2026. — [Morocco World News](https://www.moroccoworldnews.com/2026/09/340193/morocco-mistral-ai-release-first-open-source-darija-ai-tools/); [TelQuel](https://telquel.ma/instant-t/2026/09/29/le-maroc-et-mistral-developpent-des-modeles-dia-adaptes-a-la-darija_2010453/)
- Morocco's 2027 Finance Bill names national models GemMaroc (language) and IsMa (transcription) and a sovereign national cloud for citizens' data (5 November 2026). — [TelQuel](https://telquel.ma/2026/11/05/morocco-bets-big-on-artificial-intelligence-in-its-2027-finance-bill_2016335)
- A first Libyan national LLM was launched. — [Middle East AI News](https://www.middleeastainews.com/p/first-libyan-national-large-language)
- Gulf Arabic models: ALLaM distributed via IBM watsonx, Microsoft Azure and Hugging Face with HUMAIN enterprise APIs; Jais 30B (Apache 2.0) and Falcon Arabic 7B can run locally with Ollama or vLLM; Falcon-H1 Arabic reported top of the Open Arabic LLM Leaderboard; Fanar 3.0 reported for December 2026 (secondary guide sites, low reliability). — [Arabic agentic AI guide](https://arabicagenticai.pages.dev/comparisons/jais-vs-allam-vs-falcon/); [PromptQuorum](https://www.promptquorum.com/local-llms/best-arabic-local-llms-2026); [Middle East AI News](https://www.middleeastainews.com/p/falcon-h1-tops-new-global-sovereign)
- HUMAIN launched an Arabic-native chatbot built on ALLaM. — [CXO Digital Pulse](https://www.cxodigitalpulse.com/saudi-ai-firm-humain-launches-arabic-native-chatbot-built-on-allam-llm/)

### Inferences
- The competitive threat to a self-hosted assistant in Algeria is an integrator or internal IT team installing Open WebUI, Dify or AnythingLLM with open-weight models at zero licence cost. A paid local platform has to win on packaging: Arabic/French/Darija quality, connectors to local systems, support, compliance paperwork and local invoicing in dinars.
- Open WebUI's branding-preservation licence and Dify's extra conditions limit white-label resale by competitors; MIT-licensed LibreChat, AnythingLLM and Onyx CE do not. A local rival could legally rebrand the MIT ones.
- Local GPU capacity is emerging (AT Oran, Djezzy cloud) but no sourced, priced GPU-as-a-service offer was found, so on-premise hardware remains the practical route for sovereign LLM deployments in 2026.
- Microsoft Copilot and Mistral cloud are paid in foreign currency and process data abroad; both collide with section 7 constraints for public-sector and bank buyers.
- "TeamPilot" versus "Teampilot AI": same product class (team AI assistant), same word, EU-based prior user since about 2023. Risk is highest if the Algerian product is marketed in the EU or online globally. This is a factual similarity note, not a legal opinion; no trademark-register search was done.

### Gaps
- No trademark database search (EUIPO, WIPO, INAPI Algeria) was performed for "TeamPilot"/"Teampilot".
- Not researched to source level: LightOn Paradigm, Aleph Alpha, Glean, Dust, LobeChat; no pricing collected for them.
- No AI/LLM offers found for Mobilis, Ooredoo Algeria, Icosnet, ISSAL or Ayrade (searches returned nothing).
- Whether Microsoft 365 Copilot or ChatGPT Enterprise are commercially purchasable in Algeria was not confirmed.
- No Tunisian sovereign LLM or sovereign AI cloud source was found.
- GPU capacity, operator terms and pricing of the Oran AI data centre and of AventureCloudz are unpublished.
- No sourced named customer for Nojoom.ai, Fentech or PACAH.

## 5. Digital forensics platforms: use or resellers in Algeria and the Maghreb, export-control or procurement constraints, local alternatives

### Takeaway
No public evidence ties any of the major forensic suites (Cellebrite, Magnet, MSAB, OpenText EnCase, Exterro FTK, Belkasoft, Oxygen, X-Ways) to Algerian agencies; the only Algerian channel found is a Paraben reseller in Algiers, and capability building is running through state-to-state cooperation (UK, South Korea, Russia). Cellebrite is Israeli and Algeria has no relations with Israel, the tools are subject to vendor and exporter end-user controls, and no local commercial alternative was found, so this is the segment with the least visible competition and the most procurement opacity.

### Cited Findings

Algeria
- Paraben's channel-partner page lists Transmission-dz, Hydra, Algiers (contact@transmission-dz.com) as a reseller. — [Paraben channel partners](https://paraben.com/?p=1530)
- Algeria's DGSN signed an MoU with the UK Home Office covering digital forensics ("empreintes électroniques") and biometrics for criminal investigations (November 2025). — [Biometric Update](https://www.biometricupdate.com/202511/algeria-to-get-uk-support-on-digital-forensics-biometrics-for-policing); [We Are Tech Africa](https://www.wearetech.africa/fr/fils/actualites/tech/l-algerie-signe-un-accord-avec-le-royaume-uni-sur-l-analyse-des-empreintes-electroniques)
- DGSN and South Korea's National Forensic Service signed a forensic cooperation memorandum in Algiers (17 July 2025). — [dzair-tube](https://www.dzair-tube.dz/en/algeria-south-korea-seal-forensic-cooperation-pact-a-new-era-in-scientific-policing)
- Algeria signed a cybersecurity cooperation protocol with Russia (reported June 2025); forensics not specified. — [We Are Tech Africa](https://www.wearetech.africa/fr/fils/actualites/tech/cybersecurite-l-algerie-s-allie-a-la-russie-pour-renforcer-sa-defense-numerique)
- Algeria recorded 13,204 cybercrime cases involving 7,815 individuals in 2025. — [We Are Tech Africa](https://www.wearetech.africa/fr/fils/actualites/tech/algerie-la-cybercriminalite-en-forte-hausse-plus-de-13-000-affaires-recensees-en-2025)
- Algeria adopted a national cybersecurity strategy 2025-2029. — [Digital Business Africa](https://www.digitalbusiness.africa/algerie-une-strategie-nationale-2025-2029-pour-renforcer-la-cybersecurite-et-proteger-la-souverainete-numerique/)
- Local research exists: a CERIST national research programme document on automatic extraction of evidence data for cybercrime, and an Algerian thesis on electromagnetic shielding enclosures for forensic examination. — [CERIST PNR](https://www.cerist.dz/doc/PNR/tic/Automatic_extraction_evidence_data_cybercrime.pdf); [Thèses-Algérie](https://theses-algerie.com/2964391094266550/article/nan/analysis-of-electromagnetic-shielding-enclosure-for-digital-forensics-examination)
- Lists of police agencies reported as Cellebrite buyers (Canada, Germany, Seychelles, Tanzania, Turkey, UK and others) do not include Algeria. — [Cellebrite Wikipedia mirror](https://en.wikipedia.com/wiki/Cellebrite); [AFSC Investigate](https://investigate.afsc.org/node/2273)

Constraints on foreign vendors
- Cellebrite is an Israeli company (AFSC profile; Jerusalem Post coverage). — [AFSC Investigate](https://investigate.afsc.org/node/2273); [Jerusalem Post](https://www.jpost.com/middle-east/article-884281)
- Algerian lawmakers submitted a draft law in November 2024 to bar economic dealings between Algerian companies and foreign firms with ties to Israel; report notes no Israeli companies operate in Algeria; enactment status not confirmed. — [The New Arab](https://www.newarab.com/news/algeria-may-pass-law-ban-foreign-firms-links-israel?amp=1); [African Manager](https://africanmanager.com/algerie-un-projet-de-loi-pour-criminaliser-tout-lien-economique-avec-israel/)
- Cellebrite cut off Serbian police from its technology after misuse reports, showing vendor-side end-user restrictions. — [Next](https://next.ink/brief_article/cellebrite-interdit-a-la-police-serbe-dutiliser-sa-technologie/)
- In France, a commission refused private experts authorisation to hold Cellebrite UFED Premium and MSAB XRY PinPoint, reserving them for state services (National Assembly written question 11810), showing that advanced unlock tiers are sold to governments only. — [Assemblée nationale](https://www.assemblee-nationale.fr/dyn/16/questions/QANR5L16QE11810.pdf)

Maghreb comparators
- The EU financed phone-extraction software and training for Moroccan police; MSAB (XRY) and Oxygen Forensics were named suppliers (25 July 2022). — [Disclose](https://disclose.ngo/en/article/how-the-eu-supplied-morocco-with-phone-hacking-spyware)
- Moroccan security services were reported to have used Cellebrite to unlock a detainee's phone; Cellebrite staff pitched in Morocco in 2019. — [Forbidden Stories](https://forbiddenstories.org/how-did-morocco-become-addicted-to-tracking-down-its-opponents-with-spyware/); [Business & Human Rights Resource Centre](https://business-humanrights.org/en/latest-news/cellebrite-products-allegedly-used-to-spy-on-asylum-seekers-in-morocco)

Pricing signals (public procurement records, mostly US)
- Cellebrite: UFED 4PC Ultimate subscription near US$6,900; Inseyets or Premium with unlocks US$15,000–30,000 per year; one city's Premium renewal US$19,770 for one year. — [CivicIQ](https://civiciq.com/blog/how-much-does-cellebrite-cost)
- Magnet AXIOM: US$7,020 for AXIOM Premier (Warren, Ohio, 2025) and US$6,720 for AXIOM Advanced (York County, 2025); GrayKey locked-device access sold separately. — [CivicIQ](https://civiciq.com/blog/cellebrite-vs-magnet-forensics)
- Oxygen Forensic Detective: a European reseller listed €9,861.08 excluding VAT with 12 months of updates (date unclear); vendor highlights a perpetual licensing model. — [Moonsoft](https://moonsoft.net/products/000910.html); [Oxygen Forensics](https://www.oxygenforensics.com/en/products/oxygen-forensic-detective/)

Open-source substitute
- Autopsy: open-source digital forensics platform and GUI for The Sleuth Kit, Apache 2.0, 3.5k GitHub stars (fetched 16 November 2026). — [GitHub](https://github.com/sleuthkit/autopsy)

### Inferences
- Algerian state forensic labs (DGSN, Gendarmerie's INCC, military) almost certainly use some commercial extraction tools, but procurement is not published; any statement about which ones would be speculation.
- Cellebrite, the global leader in mobile extraction, is very likely politically unbuyable for Algerian state bodies, which removes the strongest incumbent and leaves European (MSAB, X-Ways), North American (Magnet, OpenText, Exterro, Paraben), Russian-origin (Oxygen, Belkasoft, Elcomsoft) and Chinese suppliers. This is an inference from the Israeli origin and the absence of relations.
- A local platform competes less on extraction exploits (where the foreign vendors' R&D is hard to match) and more on case management, analysis, Arabic/Darija content analytics, air-gapped deployment and sovereignty over evidence data.
- Typical price anchors are US$7k–30k per examiner seat per year for foreign suites, plus hardware; import of such licences needs the services-import authorisation in section 7.

### Gaps
- No tender, contract or press source identifies the tools used by DGSN, Gendarmerie Nationale (INCC Bouchaoui), customs, or the judiciary.
- No authorised Algerian reseller found for Magnet, MSAB, OpenText EnCase, Exterro FTK, Belkasoft, Oxygen or X-Ways.
- No source on specific export-licence denials or Wassenaar dual-use licensing outcomes for Algeria; no BIS country-group information for Algeria was retrieved.
- No Tunisian forensic-tool procurement source found.
- No Algerian commercial forensic product (other than the vendor being profiled) was found.

## 6. Local Algerian AI / data / fintech companies and integrators competing for the same budgets

### Takeaway
The local field is thin and mostly adjacent rather than head-on: one KYC startup (CORTIXIA), LLM/assistant players (Fentech/Hadretna, Nojoom.ai), sovereign-cloud actors (Djezzy, Armonika, Algeria Venture with Taubyte), and security integrators holding foreign vendor partnerships (Intervalle Technologies, Transmission-dz). Funding data for these companies is almost entirely undisclosed; the largest disclosed Algerian tech rounds (Yassir, VOLZ) are outside these five segments.

### Cited Findings
- CORTIXIA: digital identity and KYC startup; strategic partnership with Algeria Venture for access to government and corporate buyers; funding undisclosed. — [MENA Startup Digest](https://menastartupdigest.com/?p=44803)
- Fentech: Algerian-French startup behind the Hadretna Darija/Tamazight LLM with Prof. Merouane Debbah; Hadretna entity listed as founded 2024. — [Algérie360](https://www.algerie360.com/hadretna-lintelligence-artificielle-au-service-des-dialectes-algeriens/); [LinkedIn](https://linkedin.com/company/hadretna)
- Nojoom.ai: enterprise SaaS (Thuraya, Suhail, Nitaq) for Arabic search, document analysis and workflow assistance (commentary, single source). — [algeriatech.news](https://algeriatech.news/tag/nojoom/)
- Intervalle Technologies (Algiers): cybersecurity, GRC, audit, training; Entrust and IBM partner; an unverified aggregator gives founding 2005, 21–50 staff, CEO Tahar Malaoui. — [Entrust](https://www.entrust.com/partner-directory/intervalle-technologies); [IBM](https://ibm.com/partnerplus/directory/company/5512); [Prospeo](https://prospeo.io/c/intervalle-technologies)
- Transmission-dz (Hydra, Algiers): listed Paraben forensic-tools reseller. — [Paraben](https://paraben.com/?p=1530)
- Armonika: domestic sovereign-cloud software (virtualisation, orchestration), partner of Djezzy (24 August 2026). — [Algérie Eco](https://algerie-eco.com/2026/08/24/developpement-du-cloud-souverain-en-algerie-partenariat-entre-djezzy-et-armonika-sous-legide-de-algeria-venture/)
- Algeria Venture: public accelerator; behind AventureCloudz and the CORTIXIA partnership; a database lists only two equity investments, the latest in January 2023. — [allAfrica](https://fr.allafrica.com/stories/202604300542.html); [CB Insights](https://www.cbinsights.com/company/algeria-venture/financials)
- Algeria Startup Fund has funded over 100 startups across 20 sectors; about 2,300 companies hold the Startup Label out of about 7,800 registered; an estimated 50–60 AI startups, with fintech and payments the largest and best-funded cluster (commentary, single source). — [algeriatech.news](https://algeriatech.news/algeria-10-startups-to-watch-2026-sectors-profiles/)
- Another source puts the ecosystem at over 2,000 certified companies, 7% in fintech. — [The Fintech Times](https://thefintechtimes.com/algerias-fintech-ecosystem-in-2026-by-building-momentum/)
- Finlab (Algeria fintech fund/lab) targets startups serving banks and insurers. — [N'TIC](https://www.nticweb.com/web/10340-fintech-algeria-finlab-s-interesse-aux-startups-specialisees-dans-les-banques-et-assurances.html)
- Banks buying from startups ("venture clienting") is described as an emerging model, with BDL cited as already deploying third-party solutions (commentary, single source). — [algeriatech.news](https://algeriatech.news/fintech-open-innovation-venture-clienting-algeria/)
- Largest disclosed rounds for scale reference: VOLZ raised US$5m Series A, the largest Algerian round in local currency (16 December 2025); Yassir raised a US$150m Series B in November 2022. — [TechCabal](https://techcabal.com/2025/12/16/volz-raises-5-million/); [algeriatech.news](https://algeriatech.news/?p=26929)
- Other names in rankings: Legal Doctrine (legal data), Algeria FinTech Hub. — [StartupHub.ai](https://www.startuphub.ai/lists/top-startups-in-algeria-2026)
- Mytpe: Algerian digital payments builder. — [Mytpe](https://mytpe.app/en/about)
- Algérie Télécom's DZD 1.5bn startup fund for AI, cybersecurity and robotics makes the incumbent telco both a financier of potential rivals and a prospective channel. — [Techsoma](https://techsoma.africa/algeria-invests-11m-in-ai-startups-to-drive-digital-innovation/)

### Inferences
- The scarcest thing in this market is a referenceable bank or ministry deployment; none of the local AI names above has a publicly sourced one in fraud, AML, forensics or enterprise assistants.
- Integrators with foreign vendor badges (Entrust, IBM, Paraben) are the likely route by which global products reach Algerian banks and agencies, so they are competitors in tenders and also potential resale partners.
- State-linked sponsorship (Algeria Venture, Algérie Télécom fund, AI cluster at Sidi Abdellah) is a competitive asset in itself for whoever holds it, because public banks and ministries are the main buyers.

### Gaps
- No verified founding years, headcount, funding or clients for CORTIXIA, Nojoom.ai, Armonika or Transmission-dz.
- Nothing found for other plausible local competitors (Icosnet, ISSAL, Ayrade, ADEX Technology, Big Informatique, Beyn, university spin-offs, CERIST); they may still be active.
- No Algerian startup found in fraud scoring, AML monitoring, or forensic software.
- Crunchbase, Tracxn and Magnitt profiles could not be opened; aggregator funding figures for Algeria are unreliable (one reports US$0 tracked).

## 7. Structural factors: FX and payment restrictions, data-localisation rules, procurement preference for local and startup vendors, sanctions and export licensing; typical pricing models and public price points

### Takeaway
Three rules tilt the field toward a local, dinar-invoicing, on-premise vendor: since July 2025 every import of services, including software licences and renewals, needs prior ministerial authorisation before bank domiciliation; cross-border transfers of personal data need prior ANPDP authorisation, and digital banks and PSPs must host platforms in Algeria; and public procurement carries a 25% national preference margin plus reported reservations for labelled startups. Foreign pricing is per check (about US$0.8–5 for IDV), per seat (US$18–30 per user per month for Copilot) or annual licence (US$7k–30k per forensic seat), all in foreign currency.

### Cited Findings

FX and import of services
- Since July 2025, per an ABEF note, every import of services requires a prior authorisation from the relevant ministry, and banks must require it before domiciliation. — [L'Economiste Maghrébin, 10 July 2025](https://www.leconomistemaghrebin.com/2025/07/10/algerie-importations-services/); [Algérie360](https://www.algerie360.com/lalgerie-durcit-les-conditions-dimportation-des-services-voici-ce-qui-change/)
- The list of services subject to the forecast import programme (PPI) includes licence renewals and software acquisition and updates. — [TSA](https://www.tsa-algerie.com/importations-de-services-lalgerie-fixe-la-liste-des-prestations-soumises-au-ppi/)
- Banque d'Algérie Regulation 26-02 governs foreign-currency accounts and repatriation of export receipts within 120 days. — [Upgrowth](https://www.upgrowth.dz/journal-officiel/reglement-26-02-comptes-devises-rapatriement-exportations)
- A Banque d'Algérie note of 14 May 2026 and Instruction 05-2026 tightened import domiciliation (goods). — [Algérie360](https://www.algerie360.com/la-banque-dalgerie-fixe-de-nouvelles-regles-pour-les-importations/); [Echorouk](https://www.echoroukonline.com/mandatory-new-rules-for-importers-of-goods-intended-for-resale)
- Tunisian press summarises a general Algerian tightening on imports and foreign-currency outflows. — [Tunisie Numérique](https://www.tunisienumerique.com/algerie-coup-de-vis-sur-les-importations-et-les-flux-de-devises/)

Data protection and localisation
- Law 18-07 (JO n°34, 10 June 2018) applies to all public and private operators; processing requires prior declaration to or authorisation from ANPDP. — [Upgrowth](https://www.upgrowth.dz/journal-officiel/loi-18-07-protection-donnees-personnelles); [Zoom Algérie](https://zoomalgerie.com/loi-18-07-protection-donnees-algerie/)
- Transfers outside Algeria need prior ANPDP authorisation; a law-firm alert noted the transfer authorisation forms were not yet available (July 2023). — [Gide](https://www.gide.com/sites/default/files/2023-07gide_alerteclient_anpdp_fr_7.pdf)
- Penalties reach five years' imprisonment and DZD 500,000 fines; ANPDP treats online publication on foreign-hosted platforms as an international transfer. — [TSA](https://www.tsa-algerie.com/donnees-personnelles-lalgerie-modifie-sa-legislation-ce-qui-va-changer/); [We Are Tech Africa](https://www.wearetech.africa/fr/fils/actualites/tech/lalgerie-durcit-les-regles-de-publication-des-images-sur-les-plateformes-numeriques)
- A "Law 25-11" is reported to change cross-border data-flow rules, with 2026 described as the year enforcement bites (commentary, single source; text not verified). — [algeriatech.news](https://algeriatech.news/?p=26670)
- Critical view: enforcement described as more symbolic than real. — [APA News](https://fr.apanews.net/society/algerie-protection-des-donnees-personnelles-un-encadrement-plus-symbolique-que-reel/)
- Banque d'Algérie Regulation 24-04 on digital banks requires the operational platform and its redundancies to be hosted in Algeria. — [Radio Algérie](https://news.radioalgerie.dz/fr/node/55583); [algeriatech.news](https://algeriatech.news/?p=24399)
- Regulation 25-02 (April 2025) on payment service providers contains a provision on the payment platform and redundancies being on national territory (fragment; verify in text). — [Banque d'Algérie PDF](https://www.bank-of-algeria.dz/stoodroa/2025/05/REG.N%C2%B025-02.FR_.pdf)

Public procurement preference
- National preference margin raised from 15% to 25%, applying to products of Algerian origin and/or companies under Algerian law (2011 implementing order); the 2015 code (art. 60) grants it to Algerian-origin products and/or Algerian-law companies majority-owned by resident nationals. — [CMS law flash](https://cms.law/fr/fra/publication/flash-info-algerie-marches-publics-precisions-sur-l-application-de-la-marge-de-preference-nationale); [Algérie360](https://www.algerie360.com/reglementation-des-marches-publicsla-marge-de-preference-nationale-passe-a-25/)
- Law 23-12 of 5 August 2023 sets the general public procurement rules. — [Algérie Eco, 10 August 2023](https://algerie-eco.com/2023/08/10/la-loi-sur-les-marches-publics-publiee-au-journal-officiel/); [FAOLEX text](https://faolex.fao.org/docs/pdf/alg220656.pdf)
- Algeria limits recourse to foreign firms in public contracts. — [TSA](https://www.tsa-algerie.com/marches-publics-lalgerie-limite-le-recours-aux-etrangers/)
- Reported, not verified against the official text: contracting services must reserve some contracts for small and very small enterprises and labelled startups, within 20% of public orders (November 2026 article). — [Zoom Algérie](https://zoomalgerie.com/?p=17251)
- Reported, not verified: public entities and state enterprises may contract startups by direct agreement (gré à gré) (commentary, single source). — [algeriatech.news](https://algeriatech.news/?p=28321)
- Executive Decree 25-311 (1 December 2025, JO n°81 of 7 December 2025) amends Decree 20-254 and adds a Scale-up label; the Start-up label lasts four years, renewable once, and gives access to state support measures. — [Upgrowth](https://www.upgrowth.dz/journal-officiel/decret-25-311-label-scale-up-start-up-incubateur); [TSA](https://www.tsa-algerie.com/du-nouveau-pour-les-startups-en-algerie-ce-qui-change/)
- A new implementing decree for public procurement was under preparation (19 March 2026). — [Financial Afrik](https://www.financialafrik.com/2026/03/19/algerie-un-nouveau-decret-en-preparation-pour-moderniser-les-marches-publics/)

Sanctions, export controls and political constraints
- January 2026 US BIS rule on advanced computing chips targets Country Group D:5 and Macau; nothing found placing Algeria under those restrictions. — [Covington](https://www.cov.com/news-and-insights/insights/2026/01/us-commerce-department-revises-license-review-policy-for-exports-of-certain-advanced-computing-commodities-to-china-and-macau)
- Israeli-origin technology faces a political barrier (2024 draft law; no Israeli firms operate in Algeria). — [The New Arab](https://www.newarab.com/news/algeria-may-pass-law-ban-foreign-firms-links-israel?amp=1)
- FATF grey-list exit (19 June 2026) lowers correspondent-banking friction for Algerian banks. — [bne IntelliNews](https://www.intellinews.com/algeria-and-namibia-exit-fatf-grey-list-six-african-states-remain-under-enhanced-monitoring-450317/)

Pricing models and public price points (all foreign, for anchoring)
- Identity verification, per check: Sumsub US$1.35–1.85 with US$149–299 monthly minimums; Veriff from US$0.80; Onfido about US$2–3; Jumio about US$3–5. — [Tech Insider](https://tech-insider.org/igt-sumsub-vs-onfido-vs-jumio-vs-veriff-for-igaming-kyc-202-en-d169/)
- ID OCR SDK: annual licence sized by verification volume (Regula). — [Regula](https://regulaforensics.com/id-verification)
- Enterprise AI assistant, per seat: Microsoft 365 Copilot US$30 per user per month, Copilot Business US$18–21; Mistral Le Chat Pro US$14.99 and Team US$24.99 (third-party), enterprise and self-hosted on quote; Teampilot AI US$15–50 per month. — [IntuitionLabs](https://intuitionlabs.ai/articles/microsoft-copilot-pricing-licensing); [CostBench](https://www.costbench.com/software/ai-chatbots/le-chat-mistral/); [AlternativeTo](https://alternativeto.net/software/teampilot-ai/about)
- Open-source assistants: zero licence fee (MIT or modified Apache), cost is hardware and integration. — [AnythingLLM GitHub](https://github.com/Mintplex-Labs/anything-llm)
- Forensics, per examiner seat per year: Cellebrite US$6.9k–30k; Magnet AXIOM about US$6.7k–7k; Oxygen about €9.9k perpetual with 12 months of updates. — [CivicIQ](https://civiciq.com/blog/how-much-does-cellebrite-cost); [Moonsoft](https://moonsoft.net/products/000910.html)
- Payment-platform contracts can run very long: SATIM's BPC contract reportedly included a 14-year maintenance commitment. — [Maghreb Emergent](https://maghrebemergent.news/fr/monetique-comment-la-satim-a-marie-bpc-aux-kouninef/)

### Inferences
- For a public bank or ministry, buying a foreign SaaS product in 2026 means a ministerial import authorisation, a PPI line, bank domiciliation in foreign currency and an ANPDP transfer authorisation. A local vendor invoicing in dinars with on-premise delivery skips all four. This is the main structural advantage and it is stronger for subscription/SaaS products than for one-off perpetual licences.
- The same rules protect entrenched foreign platforms already installed on-premise under long maintenance contracts (BPC, Temenos, SBS, Finacle); their add-on modules avoid a new vendor onboarding even if they still need import authorisation.
- The 25% preference margin and startup reservations matter only if the vendor qualifies as Algerian-law and majority resident-owned and, for the reservation, holds a current Start-up or Scale-up label (four years, renewable once).
- Local per-transaction or per-check pricing has to sit below the foreign anchors (roughly US$1–3 per identity check) in dinar terms; for banks, licence plus annual maintenance is the model the incumbents have normalised.
- Hardware is the residual foreign-dependency risk for sovereign AI: GPUs still have to be imported under the same domiciliation rules, and US chip export rules could change.

### Gaps
- The exact articles of Law 23-12 on national preference and startup reservations, and whether the 25% rate carries over unchanged, were not verified in the official text.
- No authoritative source on whether direct award (gré à gré) to labelled startups is legally available.
- No Banque d'Algérie text was found that generally requires banks (as opposed to digital banks and PSPs) to host data in Algeria or restricts cloud outsourcing.
- Algeria's position on the EU high-risk third-country list after the FATF exit was not checked.
- No Algeria-specific information on US EAR country grouping, Wassenaar licensing practice, or actual licence denials for forensic or AI hardware.
- No public price points in dinars for any competing product in Algeria; no local tender award values found.
