# ArchiMate (archimate)
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
