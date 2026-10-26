# Glean (glean)

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
