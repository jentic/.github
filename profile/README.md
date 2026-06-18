<h3 align="center">
  <picture>
    <img alt="Jentic logo" src="https://raw.githubusercontent.com/jentic/.github/refs/heads/main/assets/jenticBanner.png">
  </picture>
</h3>
<h3 align="center">
  <p><strong>The sovereign operating layer for enterprise AI agents</strong></p>
  <p>The world runs on APIs. One platform for all agent capabilities. Open, secure, and reliable.</p>
</h3>
<p align="center">
  Plug your AI agents into a vast open repository of API operations and workflows with a single turn-key integration.<br>
  Score your OpenAPI documents for AI-readiness. Build, validate, and run Arazzo workflows.<br>
  All the capability, without the complexity. Open, secure, and reliable.
</p>

<p align="center">
  <a href="https://docs.jentic.com" target="_blank">Documentation</a> •
  <a href="https://docs.jentic.com/getting-started/quickstart" target="_blank">Quickstart</a> •
  <a href="https://jentic.com" target="_blank">Website</a>
</p>

---

## 🤖 Agent Platform

- **[`Jentic SDK (Python)`](https://github.com/jentic/jentic-sdks)** – Official Python SDK for discovering and executing APIs and workflows in your agents
  - Perfect for: Python developers, agent builders, tool integrators

- **[`Jentic Tools`](https://github.com/jentic/jentic-sdks)** – MCP server for connecting any MCP-compatible agent to Jentic
  - Perfect for: Claude Desktop, Cursor, Windsurf, ChatGPT, VS Code MCP users

- **[`Jentic Mini`](https://github.com/jentic/jentic-mini)** – _(⚠️ Early Access)_ Open-source, self-hosted Jentic API execution layer; gives agents access to 6,000+ APIs without ever exposing credentials
  - Search, execute, observe, and manage API access with a local credentials vault and scoped toolkit keys per agent
  - Fully API-compatible with the hosted and VPC Jentic editions
  - Perfect for: self-hosters, privacy-conscious teams, local agent development

- **[`Jentic Skills`](https://github.com/jentic/jentic-skills)** – Agent skills for the Jentic platform
  - **[`jentic`](https://github.com/jentic/jentic-skills/tree/main/skills/jentic)** – Core Jentic skill for self-hosted Jentic Mini
  - **[`jentic-v1`](https://github.com/jentic/jentic-skills/tree/main/skills/jentic-v1)** – Skill for hosted Jentic (jentic.com)
  - **[`jentic-workflows`](https://github.com/jentic/jentic-skills/tree/main/skills/jentic-workflows)** – Generates Arazzo workflow YAML from a natural-language goal or agent tool trace
  - Perfect for: OpenClaw users, agent workflow automation

- **[`Standard Agent`](https://github.com/jentic/standard-agent)** – Composable Python agent library with Jentic tools built in
  - ![Good First Issues](https://img.shields.io/github/issues/jentic/standard-agent/good%20first%20issue?color=7057ff&label=Good%20First%20Issues)
  - Perfect for: Python developers building reasoning agents

- **[`Jentic Public APIs`](https://github.com/jentic/jentic-public-apis)** – Open catalog of 6,000+ AI-ready API specs and 2,000+ Arazzo workflows
  - Perfect for: API documentation writers, knowledge contributors

---

## 📊 Get Your APIs AI-Ready

- **[`API AI-Readiness Framework (JAIRF)`](https://github.com/jentic/api-ai-readiness-framework)** – Open specification for evaluating how well an API supports AI agents and LLMs across six scored dimensions
  - Perfect for: API designers, platform architects, governance teams

- **[`Jentic API Scorecard`](https://github.com/jentic/jentic-api-scorecard)** – Score any OpenAPI document against JAIRF and get a single grade with prioritised recommendations
  - **CLI** – `npx @jentic/api-scorecard-cli score ./openapi.yaml` — runs locally in Docker, spec never leaves your machine
  - **GitHub Action** – gate PRs on AI-readiness score, upload SARIF findings to the Security tab
  - **Agent Skill** – install into Claude Code, Vercel skills CLI, or TanStack Intent
  - **Web UI** – paste a URL or drop a file at [jentic.com/scorecard](https://jentic.com/scorecard)
  - Perfect for: API developers, platform teams, CI/CD pipelines

---

## 🔧 Open Standards Libraries

Give your agents well-formed workflows and API specs to work with. These libraries cover the full lifecycle — parse, resolve, validate, run, and render.

- **[`Arazzo Engine`](https://github.com/jentic/arazzo-engine)** – Python toolkit for executing and generating [Arazzo](https://github.com/OAI/Arazzo) workflow specifications
  - **[Arazzo Runner](https://github.com/jentic/arazzo-engine/tree/main/runner)** – Executes Arazzo workflows end-to-end from the CLI or Python
  - **[Arazzo Generator](https://github.com/jentic/arazzo-engine/tree/main/generator)** – Generates Arazzo workflows from OpenAPI Descriptions using AI
  - Perfect for: Python developers, workflow automation, CI pipelines

- **[`Jentic Arazzo Tools`](https://github.com/jentic/jentic-arazzo-tools)** – TypeScript/JavaScript monorepo for parsing, resolving, validating, running, and rendering Arazzo documents
  - **[`@jentic/arazzo-parser`](https://github.com/jentic/jentic-arazzo-tools/tree/main/packages/jentic-arazzo-parser)** – Parses Arazzo documents into an ApiDOM data model
  - **[`@jentic/arazzo-resolver`](https://github.com/jentic/jentic-arazzo-tools/tree/main/packages/jentic-arazzo-resolver)** – Dereferences Arazzo and OpenAPI documents
  - **[`@jentic/arazzo-validator`](https://github.com/jentic/jentic-arazzo-tools/tree/main/packages/jentic-arazzo-validator)** – Validates and lints Arazzo documents via CLI or API
  - **[`@jentic/arazzo-runner`](https://github.com/jentic/jentic-arazzo-tools/tree/main/packages/jentic-arazzo-runner)** – Executes Arazzo workflows in TypeScript/JavaScript environments
  - **[`@jentic/arazzo-ui`](https://github.com/jentic/jentic-arazzo-tools/tree/main/packages/jentic-arazzo-ui)** – UI components for rendering Arazzo workflows
  - Perfect for: TypeScript/JavaScript developers, tooling and UI builders

- **[`Jentic OpenAPI Tools`](https://github.com/jentic/jentic-openapi-tools)** – Python toolkit for working with OpenAPI documents
  - Perfect for: Python developers, API tooling builders

- **[`API Problem Details`](https://github.com/jentic/api-problem-details)** – Reusable [RFC 9457](https://www.rfc-editor.org/rfc/rfc9457.html) Problem Details components for consistent, machine-readable error responses across all Jentic APIs
  - **OpenAPI schemas** — reference-ready response definitions for all standard error codes
  - **[`jentic-problem-details`](https://github.com/jentic/api-problem-details)** – Python package with Pydantic models and FastAPI utilities
  - **[`@jentic/problem-details`](https://github.com/jentic/api-problem-details)** – TypeScript type definitions and utilities
  - Perfect for: API developers building agent-consumable error responses, FastAPI and TypeScript projects

---

## 🧪 Sample Projects & Demos


- **[`Jentic on YouTube`](https://www.youtube.com/@JenticAI)** – Walkthroughs, demos, and agent builder tutorials

---

## 🤝 Contributing to Jentic

We welcome contributors of all backgrounds and experience levels!

### 🌟 New to Open Source?
- Start with issues labeled `good first issue` in any of our repositories
- Check out [Standard Agent's contribution guide](https://github.com/jentic/standard-agent/blob/main/good_first_issue.md)
- Join our Discord for friendly help and guidance

### 🔥 Experienced Developer?
- Look for `enhancement` and `feature` labeled issues
- Propose new features or architectural improvements
- Help review pull requests from new contributors

### 📝 Love Documentation?
- Improve API documentation and examples
- Create tutorials and guides
- Fix typos and clarify explanations

### 🎨 Designer or UX Expert?
- Help improve our documentation design
- Create diagrams and visual aids
- Enhance user experience across our tools

### Ways to Contribute Across Jentic

| Type | Examples | Repositories |
|------|----------|--------------|
| **Documentation** | API docs, tutorials, examples | All repositories |
| **Testing** | Unit tests, integration tests, test coverage | Standard Agent, Arazzo Engine, Arazzo Tools |
| **Features** | New reasoners, tool integrations, workflow capabilities | Standard Agent, Arazzo Engine |
| **Examples** | Platform bots, use cases, demos | Standard Agent, SDKs |
| **API Specs** | OpenAPI documents, Arazzo workflows | Jentic Public APIs |
| **Infrastructure** | CI/CD, automation, tooling | All repositories |
| **Community** | Discord moderation, issue triage, newcomer support | Organization-wide |

---

## 🌍 Join the Community

Connect with agent builders, API developers, and workflow automation experts:

<div align="center">
  <p>
    <a href="https://discord.gg/TdbWXZsUSm">
      <img src="https://img.shields.io/badge/Join%20our%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
    </a>
    <a href="https://x.com/JenticAI">
      <img src="https://img.shields.io/badge/Follow%20on%20X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)" />
    </a>
    <a href="https://www.linkedin.com/company/jentic">
      <img src="https://img.shields.io/badge/Follow%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
  </p>
</div>

### Community Highlights
- **Weekly Ask Me Anything**: Join our Discord for live Q&A sessions
- **Contributor Spotlights**: We feature outstanding contributors monthly
- **Agent Builder Meetups**: Connect with other developers building AI agents
- **API Workshop Series**: Learn about integrating APIs with AI agents

---

## 🏆 Recognition & Rewards

We believe in recognizing our contributors:

- **Contributor Hall of Fame** in our documentation
- **Special Discord roles** for active contributors
- **Early access** to new features and tools
- **Jentic swag** for significant contributions
- **Speaking opportunities** at our community events

---

> 🧩 Jentic is built for developers who want to move fast, skip boilerplate, and give their agents real-world capabilities without complexity.

**Ready to contribute?** Start by exploring our repositories above, joining our Discord, and finding your first issue to tackle!
