# Huginn (huginn)
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
