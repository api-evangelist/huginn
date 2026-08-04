# Huginn (huginn)

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

Huginn is an open-source system for building agents that perform automated tasks online. Self-hosted agents can monitor the web, send and receive events, and trigger workflows. Each Huginn instance exposes a JSON-based HTTP interface (the Web Requests API) that lets external systems trigger scenarios and post events into the platform.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/huginn/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Self-Hosted
- **Access:** Open Source

## Tags:

 - Agents, Automation, Workflow Automation, Self-Hosted, Open Source

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-28

## APIs

### Huginn Platform
The Huginn platform is a self-hosted Ruby on Rails application that orchestrates agents, scenarios, and events. Operators install and run their own instance and configure agents to consume and produce events across the web.

**Human URL:** [https://github.com/huginn/huginn](https://github.com/huginn/huginn)

#### Tags:

 - Agents, Self-Hosted, Workflow Automation

#### Properties

- [Documentation](https://github.com/huginn/huginn/wiki)
- [GitHub Repository](https://github.com/huginn/huginn)
- [Installation Guide](https://github.com/huginn/huginn/blob/master/doc/manual/installation.md)
- [Docker](https://hub.docker.com/r/huginn/huginn)

### Huginn Web Requests API
Each Huginn instance exposes a Web Requests endpoint that lets external systems POST or GET events into a configured Webhook Agent. The endpoint lives at `/users/{user_id}/web_requests/{agent_id}/{secret}` on the operator's installed instance and is the primary inbound integration surface for Huginn.

**Human URL:** [https://github.com/huginn/huginn/wiki](https://github.com/huginn/huginn/wiki)

#### Tags:

 - Agents, Webhooks

#### Properties

- [Documentation](https://github.com/huginn/huginn/wiki)
- [Webhook Agent](https://github.com/huginn/huginn/blob/master/app/models/agents/webhook_agent.rb)

## Common Properties

- [Website](https://github.com/huginn/huginn)
- [Documentation](https://github.com/huginn/huginn/wiki)
- [GitHub Repository](https://github.com/huginn/huginn)
- [License](https://github.com/huginn/huginn/blob/master/LICENSE)
- [Issues](https://github.com/huginn/huginn/issues)
- [Rules](https://raw.githubusercontent.com/api-evangelist/huginn/refs/heads/main/huginn-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
