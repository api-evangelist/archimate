# ArchiMate (archimate)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

ArchiMate is an open and independent enterprise architecture modeling language developed by The Open Group, supporting description, analysis and visualization of architecture within and across business domains. The current version is ArchiMate 3.2.

**URL:** [https://www.opengroup.org/archimate-forum](https://www.opengroup.org/archimate-forum)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Enterprise Architecture, Architecture Framework, Modeling Language, Business Architecture, Technology Architecture, Standard, Open Group

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### ArchiMate Model Exchange API
API for exchanging ArchiMate models between tools and repositories using the Open Group ArchiMate Model Exchange File Format (AMEFF). Enables interoperability between enterprise architecture tools.

**Human URL:** [https://www.opengroup.org/archimate-forum/archimate-overview](https://www.opengroup.org/archimate-forum/archimate-overview)

#### Tags:

 - Enterprise Architecture, Model Exchange, Interoperability, XML Schema

#### Properties

- [Documentation](https://pubs.opengroup.org/architecture/archimate3-doc/)
- [GettingStarted](https://www.opengroup.org/archimate-forum/archimate-overview)
- [APIReference](https://pubs.opengroup.org/architecture/archimate3-doc/)
- [OpenAPI](openapi/archimate-model-exchange-api.yaml)

### ArchiMate Repository API
RESTful API for accessing and managing ArchiMate models, elements, relationships, and views stored in a central enterprise architecture repository.

**Human URL:** [https://www.opengroup.org/archimate-forum](https://www.opengroup.org/archimate-forum)

#### Tags:

 - Repository Management, Model Management, REST API, Enterprise Architecture

#### Properties

- [Documentation](https://pubs.opengroup.org/architecture/archimate3-doc/)

## Common Properties

- [Portal](https://www.opengroup.org/archimate-forum)
- [Documentation](https://pubs.opengroup.org/architecture/archimate32-doc/)
- [GettingStarted](https://www.opengroup.org/archimate-forum/archimate-overview)
- [Training](https://www.opengroup.org/certifications/archimate)
- [Blog](https://blog.opengroup.org/tag/archimate/)

## Features

| Name | Description |
|------|-------------|
| Enterprise Architecture Modeling | Standardized language for modeling business, application, and technology architecture layers. |
| Model Exchange Format | ArchiMate Model Exchange File Format (AMEFF) for tool interoperability using XML. |
| Three Architecture Layers | Business, Application, and Technology layers for comprehensive EA modeling. |
| Motivation and Strategy | Strategy and motivation aspect elements for stakeholder and driver modeling. |
| Implementation and Migration | Work package and implementation elements for roadmap and migration planning. |
| Tool Ecosystem | Supported by 20+ enterprise architecture tools including Archi, Sparx EA, BiZZdesign, and MEGA. |
| Open Standard | Open Group standard freely available for implementation without licensing fees. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise Architecture Documentation | Document and communicate enterprise architecture across business, application, and technology layers. |
| Architecture Analysis | Analyze dependencies, impacts, and gaps in enterprise architecture using standardized notation. |
| Tool Migration | Migrate ArchiMate models between EA tools using the standardized exchange format. |
| Architecture Governance | Establish governance controls and compliance checking for enterprise architecture standards. |
| IT Portfolio Management | Manage IT application portfolios and rationalize technology investments using ArchiMate models. |

## Integrations

| Name | Description |
|------|-------------|
| Archi | Open source ArchiMate modelling tool with full AMEFF import/export support. |
| Sparx Enterprise Architect | Commercial EA tool with ArchiMate 3 profile and exchange format support. |
| BiZZdesign | Enterprise architecture platform with native ArchiMate support. |
| MEGA HOPEX | Enterprise architecture management platform supporting ArchiMate standard. |
| TOGAF | ArchiMate is the recommended modeling language for TOGAF enterprise architecture framework. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ArchiMate Model Exchange API](openapi/archimate-model-exchange-api.yaml)

### JSON Schema

- [Model](json-schema/archimate-model-exchange-api-model-schema.json)
- [Model Detail](json-schema/archimate-model-exchange-api-model-detail-schema.json)
- [Element](json-schema/archimate-model-exchange-api-element-schema.json)
- [Relationship](json-schema/archimate-model-exchange-api-relationship-schema.json)

### JSON-LD

- [ArchiMate Model Exchange API Context](json-ld/archimate-model-exchange-api-context.jsonld)

## Vocabulary

- [ArchiMate Vocabulary](vocabulary/archimate-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 6 actions, 0 workflows, and 3 personas

## Rules

- [ArchiMate Spectral Rules](rules/archimate-spectral-rules.yml) — 14 rules across 8 categories enforcing ArchiMate API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
