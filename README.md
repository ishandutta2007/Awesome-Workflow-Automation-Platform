# Awesome-Workflow-Automation-Platform

## Top Workflow Automation Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on No-Code Workflow Automation, iPaaS & Self-Hosted Integration Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Workflow Automation Platforms**. These tools enable organizations to connect applications, automate business processes, and orchestrate data flows between systems—reducing manual work and eliminating point-to-point integration sprawl.



**Examples** include Shopify Flow, Zapier, Make, Workato, Tray.io, Alloy Automation, n8n, Pipedream, Celigo, and MuleSoft Composer (the category leaders).



**Open-source emphasis**: Workflow Automation is a domain where open-source tooling is **mature and production-proven**. The strongest active projects are **n8n** (self-hostable platform with 1500+ integrations and AI agent capabilities)  and **Pipedream** (source-available platform processing billions of events) . Other notable options include **ByteChef** and **PneumaticWorkflow**. No single open-source platform matches the full enterprise governance and embedded iPaaS capabilities of Workato or Celigo, but n8n provides a compelling self-hosted alternative for most automation needs.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Pricing (Starting Tier) | Free Tier Limits / Free Trial | Description |
| :--- | :--- | :--- | :--- |
| **[Shopify Flow](https://www.shopify.com/)** | **Included free with Shopify plans** (Shopify store plans start at $39/mo or $29/mo billed annually for Basic) | **Free forever with Shopify store plan**: up to 1,000 active/inactive workflows, rate limits scale with store API quota (2 req/sec standard), max 100 objects per data-fetch action; Shopify offers a 3-day free trial (no credit card required) | E-commerce automation platform built natively into Shopify; enables merchants to automate tasks like high-risk order review, inventory management, and customer segmentation without code. |
| **[Zapier](https://zapier.com/)** | **$19.99/mo** (billed annually at $239.88/yr) or $29.99/mo (billed monthly) for Professional plan (750 tasks/mo) | **Free Forever plan**: 100 tasks/month, 2-step Zaps (1 trigger + 1 action), unlimited Zaps/tables/forms, 15-minute polling interval; 14-day free trial of Professional tier | Market-leading no-code automation platform with 9,000+ app integrations; trigger-and-action workflows (Zaps) for connecting SaaS tools without engineering effort; includes AI steps, MCP support, and enterprise governance controls. |
| **[Make](https://www.make.com/)** | **$9.00/mo** (billed annually) or $10.59/mo (billed monthly) for Core plan (10,000 credits/mo) | **Free Forever plan**: 1,000 credits/month, 2 active scenarios, 15-minute minimum schedule interval, 5 MB file size limit, 5-minute execution timeout | Visual automation platform (formerly Integromat) with 3,000+ pre-built apps; features a visual Scenario Builder, If-Else and Merge modules, scenario run replay, and Maia AI assistant for natural-language workflow generation. |
| **[Workato](https://www.workato.com/)** | **Starts at ~$60,000/yr (~$5,000/mo)** for entry-level Base Platform tier (annual contract, custom sales quote) | **No public free tier or self-serve trial**; guided proof-of-concept (POC) sandbox available upon request via enterprise sales demo | Enterprise automation platform with AI-powered recipe building, low-code connectors, and comprehensive security compliance (PCI-DSS, ISO 27001, SOC 2, HIPAA); cloud-native architecture for scalability. |
| **[Tray.io](https://tray.ai/)** | **Starts at ~$500–$600/mo** (~$6,000–$7,000/yr billed annually) for Pro tier (annual contract) | **30-day free trial** with full connector library, workspace features, and up to 1,000,000 test tasks (no credit card required; no permanent free tier) | Low-code automation platform with powerful data transformation capabilities; features workspaces, projects, and services for organizing complex workflows; hundreds of pre-built connectors plus custom connector builder. |
| **[Alloy Automation](https://runalloy.com/)** | **Starts at ~$50/connection/mo** for Unified API (custom embedded/enterprise annual contracts benchmark ~$7,500–$10,000/yr) | **Free tier for Unified API**: up to 10 active connections/month; enterprise evaluation via sales-guided demo/sandbox (no public self-serve free trial) | Integration platform designed for SaaS and AI; offers three approaches: Connectivity API for embedding native integrations, Embedded drag-and-drop orchestration, and MCP for AI agent access to 1000+ tools. |
| **[Pipedream](https://pipedream.com/)** | **$29/mo** (billed annually) or $45/mo (billed monthly) for Basic tier (2,000 compute credits/mo, 10 active workflows) | **Free Forever tier**: ~100 compute credits/day, 3 active workflows, 3 connected accounts, 1M AI tokens (development environment); 1 credit ≈ 30s execution time | Developer-focused automation platform with SDKs for 3,000+ APIs, source-available component registry, and support for AI agents, workflow builders, and API orchestration; processes billions of events at scale. |
| **[Celigo](https://www.celigo.com/)** | **Starts at ~$500–$600/mo** (~$10,000/yr entry contract for Standard edition) | **30-day free trial** with full access to endpoints and workflows; automatically downgrades to limited Free Edition (1 active flow, restricted endpoints) if not upgraded | Cloud-native iPaaS with flow builder, prebuilt connectors, and integration apps; embeds AI throughout for summaries, field mapping suggestions, and error categorization with auto-retry. |
| **[MuleSoft Composer](https://www.mulesoft.com/)** | **Starts at ~$20,000–$25,000/yr** (~$1,666–$2,083/mo equivalent, annual contract via Salesforce) | **No public self-serve free tier or trial**; POC / trial sandbox org available upon request via Salesforce/MuleSoft Account Executive | Salesforce-native automation tool for connecting apps and data with clicks, not code; designed for business teams to build event-driven automations with IT governance. |

## Open-Source GitHub Projects



- **[n8n](https://github.com/n8n-io/n8n)**  

  The leading open-source workflow automation platform (Sustainable Use License, 47,810+ GitHub stars) ; combines a visual canvas with custom code (JavaScript/Python); 1500+ integrations and 9,000+ workflow templates; AI-native capabilities for building multi-step agents with model flexibility (OpenAI, Anthropic, Google, open-source models); self-hostable with enterprise features including RBAC and audit trails .



- **[Pipedream](https://github.com/PipedreamHQ/pipedream)**  

  Source-available automation platform with a component registry on GitHub; provides triggers and actions for thousands of integrated apps; developers can use components as no-code building blocks or scaffold code for customization; trusted by 1 million+ developers .



- **[ByteChef](https://github.com/bytechefhq/bytechef)**  

  Open-source, low-code, extendable API integration and workflow automation platform; designed for integrating organizations or SaaS products with any third-party API; Java-based with active development .



- **[PneumaticWorkflow](https://github.com/pneumaticapp/pneumaticworkflow)**  

  Free and source-available lightweight workflow automation tool (Apache 2.0); Python-based with 221 GitHub stars and active development (pushed within hours as of listing) .



### Additional Strong Open-Source Options



- **µTask (ovh/utask)** — Automation engine that models and executes business processes declared in YAML; useful for structured, version-controlled workflow definitions .

- **Flowpipe (turbot)** — Cloud scripting engine for automation and workflow orchestration connecting cloud services to systems and data .

- **RuleGo** — Lightweight, high-performance, embedded component orchestration rule engine framework for Go .



**Frameworks for building custom systems**: Combine **n8n** for comprehensive workflow automation with AI agents and 1500+ integrations, **Pipedream** for developer-centric API orchestration with source-available components, and **ByteChef** for Java-based enterprise integrations in a self-hosted workflow automation stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow automation platforms handling business data and credentials must comply with applicable privacy regulations and organizational security policies; API keys and OAuth tokens require secure storage and rotation.

- **Open-source workflow automation is mature**—n8n provides a comprehensive self-hosted platform with AI capabilities, and Pipedream offers source-available components for developers. However, enterprise governance features (advanced RBAC, audit trails, SLA guarantees) and embedded iPaaS capabilities typically require commercial platforms like Workato or Celigo.

- Verify license terms for commercial use; n8n uses the Sustainable Use License (not OSI-approved, with restrictions on resale) , Pipedream is source-available , and PneumaticWorkflow uses Apache 2.0 .



---



**Made for integration engineers, automation developers, IT operations teams, and business process architects.**  

Let's make workflow automation more open, AI-ready, and integration-friendly.
