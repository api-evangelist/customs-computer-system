# Customs Computer System (customs-computer-system)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A customs computer system is the national IT platform a customs authority operates to manage the import and export of goods, collect duties, enforce trade restrictions, and exchange information with traders, brokers, carriers, and Partner Government Agencies. Examples include the U.S. ACE, the EU's ICS2 and AES, the UK's CDS, Canada's CARM, Singapore's TradeNet, and Japan's NACCS. These systems are typically accessed via EDI (XML / EDIFACT) rather than public REST APIs.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/customs-computer-system/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** Public
- **x-type:** topic

## Tags

- ACE, CDS, Customs, Customs Computer System, Declarations, EDI, Exports, ICS2, Imports, NACCS, Single Window, TradeNet, WCO Data Model

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

No standalone customs computer system APIs are catalogued here. National customs systems publish EDI message specifications and a small number of utility web services rather than full REST API platforms.

## National Customs Systems

- [U.S. Automated Commercial Environment (ACE)](https://www.cbp.gov/trade/automated)
- [EU Import Control System 2 (ICS2)](https://taxation-customs.ec.europa.eu/customs-4/customs-security/import-control-system-2-ics2_en)
- [EU Automated Export System (AES)](https://taxation-customs.ec.europa.eu/customs-4/customs-procedures-import-and-export-0/what-customs-export_en)
- [UK Customs Declaration Service (CDS)](https://www.gov.uk/government/collections/customs-declaration-service)
- [Canada CARM (CBSA Assessment and Revenue Management)](https://www.cbsa-asfc.gc.ca/services/carm-gcra/menu-eng.html)
- [Singapore TradeNet](https://www.tradenet.gov.sg/)
- [Japan NACCS](https://www.naccs.jp/e/)

## Standards

- [WCO Data Model](https://www.wcoomd.org/en/topics/facilitation/instrument-and-tools/tools/data-model.aspx)
- [WCO SAFE Framework](https://www.wcoomd.org/en/topics/facilitation/instrument-and-tools/frameworks-of-standards/safe_package.aspx)
- [UN/EDIFACT](https://unece.org/trade/uncefact/introducing-unedifact)

## Vocabulary

- **Single Window** — A facility allowing traders to file standardized information once with a single entry point to fulfil all import, export, and transit-related regulatory requirements.
- **WCO Data Model** — The international standard data set for cross-border regulatory data.
- **EDIFACT** — UN/EDIFACT, the international EDI standard widely used by national customs systems.
- **ENS / EXS** — Entry / Exit Summary Declarations under EU customs.
- **MRN** — Movement Reference Number assigned to a customs declaration.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
