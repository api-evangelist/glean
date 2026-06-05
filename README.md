# Glean (glean)

Glean is an AI-powered work assistant and enterprise search platform that connects to a company's apps and data sources to provide unified search, generative answers, and autonomous agents grounded in enterprise knowledge. Glean exposes a Client API for end-user features (search, chat, agents, answers), an Indexing API for ingesting custom data sources, and Admin and Activity APIs for governance and observability.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/glean/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/glean/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Agents
- AI
- Answers
- Chat
- Connectors
- Enterprise Search
- Generative AI
- Indexing
- Knowledge
- RAG
- Search
- Work Assistant

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Glean Client API

The Glean Client API powers end-user features including search, chat, agents, answers, announcements, collections, documents, insights, summarization, tools, and verification. Calls are made against the customer's Glean instance using a bearer API token.

- **Human URL:** [https://developers.glean.com/api-info/client/getting-started](https://developers.glean.com/api-info/client/getting-started)
- **Base URL:** `https://{instance}-be.glean.com/rest/api/v1`

#### Tags

- Agents
- Answers
- Chat
- Client
- Search
- Summarize

#### Properties

- [Documentation](https://developers.glean.com/api-info/client/getting-started)
- [OpenAPI](https://developers.glean.com/oas/client) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/glean.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glean.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glean Indexing API

The Glean Indexing API ingests documents, people, and permissions from custom data sources into a Glean instance, enabling search and chat over content that does not have a native Glean connector.

- **Human URL:** [https://developers.glean.com/api-info/indexing/getting-started](https://developers.glean.com/api-info/indexing/getting-started)
- **Base URL:** `https://{instance}-be.glean.com/rest/api/v1`

#### Tags

- Connectors
- Datasources
- Documents
- Indexing
- People
- Permissions

#### Properties

- [Documentation](https://developers.glean.com/api-info/indexing/getting-started)
- [OpenAPI](https://developers.glean.com/oas/indexing) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/glean.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glean.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glean Search API

Run unified semantic and keyword search across all connected enterprise content with permission-aware results, filters, and facets.

- **Human URL:** [https://developers.glean.com/api-reference/client-api/search](https://developers.glean.com/api-reference/client-api/search)
- **Base URL:** `https://{instance}-be.glean.com/rest/api/v1`

#### Tags

- Enterprise Search
- Search

#### Properties

- [Documentation](https://developers.glean.com/api-reference/client-api/search)
- [Postman Collection](collections/glean.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glean.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glean Chat API

Multi-turn generative chat over enterprise content with grounded answers, citations, and tool use.

- **Human URL:** [https://developers.glean.com/api-reference/client-api/chat](https://developers.glean.com/api-reference/client-api/chat)
- **Base URL:** `https://{instance}-be.glean.com/rest/api/v1`

#### Tags

- Chat
- Generative AI
- RAG

#### Properties

- [Documentation](https://developers.glean.com/api-reference/client-api/chat)
- [Postman Collection](collections/glean.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glean.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glean Agents API

Build and invoke autonomous agents that reason over enterprise data and perform multi-step workflows on behalf of users.

- **Human URL:** [https://developers.glean.com/api-reference/client-api/agents](https://developers.glean.com/api-reference/client-api/agents)
- **Base URL:** `https://{instance}-be.glean.com/rest/api/v1`

#### Tags

- Agents
- AI
- Workflows

#### Properties

- [Documentation](https://developers.glean.com/api-reference/client-api/agents)
- [Postman Collection](collections/glean.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glean.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glean People API

Look up people in the enterprise knowledge graph including profile, expertise, org chart relationships, and activity.

- **Human URL:** [https://developers.glean.com/api-reference/client-api/people](https://developers.glean.com/api-reference/client-api/people)
- **Base URL:** `https://{instance}-be.glean.com/rest/api/v1`

#### Tags

- Directory
- People

#### Properties

- [Documentation](https://developers.glean.com/api-reference/client-api/people)
- [Postman Collection](collections/glean.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glean.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glean Activity API

Read and submit activity signals (views, clicks, edits) that improve personalization and ranking across the Glean instance.

- **Human URL:** [https://developers.glean.com/api-reference/client-api/activity](https://developers.glean.com/api-reference/client-api/activity)
- **Base URL:** `https://{instance}-be.glean.com/rest/api/v1`

#### Tags

- Activity
- Analytics
- Signals

#### Properties

- [Documentation](https://developers.glean.com/api-reference/client-api/activity)
- [Postman Collection](collections/glean.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glean.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glean Governance API

Administer governance policies, data classification, and access controls across the Glean instance.

- **Human URL:** [https://developers.glean.com/api-reference/client-api/governance](https://developers.glean.com/api-reference/client-api/governance)
- **Base URL:** `https://{instance}-be.glean.com/rest/api/v1`

#### Tags

- Admin
- Governance
- Security

#### Properties

- [Documentation](https://developers.glean.com/api-reference/client-api/governance)
- [Postman Collection](collections/glean.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glean.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.glean.com/)
- [Developer](https://developers.glean.com/)
- [Documentation](https://developers.glean.com/api-info/client/getting-started)
- [SDK](https://developers.glean.com/sdks)
- [Git Hub](https://github.com/gleanwork)
- [Blog](https://www.glean.com/blog)
- [Pricing](https://www.glean.com/pricing)
- [Status Page](https://status.glean.com/)
- [Support](https://help.glean.com/)
- [Privacy Policy](https://www.glean.com/legal/privacy-policy)
- [Terms of Service](https://www.glean.com/legal/customer-terms-of-service)
- [LinkedIn](https://www.linkedin.com/company/glean-technologies/)
- [Changelog](https://developers.glean.com/changelog)
- [Integrations](https://www.glean.com/connectors)
- [L L Ms Txt](https://developers.glean.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
