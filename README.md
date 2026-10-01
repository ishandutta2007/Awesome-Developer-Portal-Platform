# Awesome-Developer-Portal-Platform

# Top Developer Portal Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Internal Developer Portals, Service Catalogs & Platform Engineering*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer Portals**. These tools provide a unified interface for developers to discover services, access documentation, scaffold new projects, and perform self-service actions — reducing cognitive load and accelerating delivery.

**Examples** include Backstage, Port, OpsLevel, Cortex, Roadie, Harness IDP, Spotify Portal, Humanitec, Atlassian Compass, and Mia-Platform (the category leaders).

**Open-source emphasis**: Developer portals are one of the strongest open-source domains in platform engineering. **Backstage** (CNCF) holds roughly 89% market share among organizations that have committed to a portal , while **Kratix**, **OpenChoreo**, and **Torii** provide production-grade alternatives. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Port](https://www.port.io/)**  
  Managed, API-first internal developer portal with flexible blueprints for modeling any entity (services, environments, clusters, teams). Self-service actions trigger GitHub Actions, Terraform, or webhooks without custom code. Real-time sync from Kubernetes, cloud providers, and Git keeps the catalog current. Best for teams wanting a production portal in days without dedicating engineers to maintenance . Free tier up to 15 seats .

- **[Cortex](https://www.cortex.io/)**  
  Service catalog and engineering intelligence platform with the deepest scorecard engine in the category. Define multi-dimensional quality standards (production readiness, security, documentation, operational maturity) and drive organization-wide improvement initiatives. AI engine (Magellan) assists catalog auditing. Best for leadership-driven standards enforcement across many services . Pricing approximately $65–69 per user/month .

- **[OpsLevel](https://www.opslevel.com/)**  
  Managed service catalog with automated service discovery from repos and infrastructure. Reputation for faster setup and simpler data model than Port's blueprint system. Scorecards, ownership tracking, and maturity rubrics with delivery lifecycle focus. Best for teams wanting a working catalog in days with minimal data modeling .

- **[Roadie](https://roadie.io/)**  
  Fully managed, hosted Backstage. Handles upgrades, hosting, and GitHub rate-limit issues that burden self-hosters. Includes Backstage catalog, TechDocs, API specs, self-service templates, 75+ plugins, SSO, RAG-based AI search, and MCP server. Teams plan at $24 per developer/month for 50–150 developers. Best for teams wanting Backstage's ecosystem without operating it .

- **[Spotify Portal](https://backstage.spotify.com/)**  
  No-code SaaS version of Backstage from the team that built it. Setup wizard connects to GitHub and auto-imports services. Ships with Soundcheck (Spotify's scorecard plugin) and a UI-based plugin installer. GA since October 2025. Customers include Capital One, PagerDuty, 2K Games, and Linux Foundation. Best for teams trusting the Backstage roadmap with minimal setup friction .

- **[Atlassian Compass](https://www.atlassian.com/software/compass)**  
  Software component catalog with health scorecards, deeply integrated into Jira, Confluence, and Bitbucket. Component catalog, scorecards, and operations management wired into existing Atlassian workflows. Free for up to 3 users; Standard $7.67/user/month; Premium $23.96/user/month. Best for Atlassian-native organizations wanting a catalog without five-figure spend .

- **[Harness IDP](https://www.harness.io/)**  
  Internal developer portal integrated with Harness's broader software delivery platform.

- **[Humanitec](https://humanitec.com/)**  
  Platform orchestrator centered on the open-source **Score** workload specification. Dynamic configuration management without static manifests per environment. Platform Orchestrator resolves resource dependencies automatically. Best for teams whose pain is environment drift and provisioning, not service cataloging .

- **[Mia-Platform](https://mia-platform.eu/)**  
  Platform engineering suite with developer portal capabilities for cloud-native application development.

## Open-Source GitHub Projects

- **[Backstage](https://github.com/backstage/backstage)**  
  The de facto standard open-source developer portal, built at Spotify and now a CNCF incubating project. Software catalog as single source of truth, TechDocs for documentation-as-code, Scaffolder for templated service creation, and 200+ community plugins for CI/CD, monitoring, cloud resources, and cost . **Trade-off**: It is a framework, not a product. 2–4 months to first meaningful value, requiring React/TypeScript expertise and 1–2 FTE for ongoing maintenance . Plugin quality varies from production-ready to abandoned. Best for organizations with 100+ developers and a dedicated platform team .

- **[Kratix](https://github.com/syntasso/kratix)**  
  Kubernetes-native platform-as-a-product framework with 705+ stars and Apache-2.0 license . Instead of a portal, Kratix extends the Kubernetes API with **Promises** — platform APIs developers consume via kubectl or GitOps. Composable Promises combine Crossplane, Terraform, and Helm. Multi-cluster by design, GitOps-friendly with everything as Kubernetes resources. **No built-in UI** — pair with Backstage or Port for the portal layer. Best for Kubernetes-heavy organizations wanting platform APIs, not portals .

- **[OpenChoreo](https://github.com/openchoreo/openchoreo)**  
  Complete, modular, open-source internal developer platform with 583+ stars and active weekly updates . Provides a full IDP stack beyond cataloging, including deployment workflows and environment management.

- **[Torii](https://github.com/Qovery/Torii)**  
  Simple, powerful, and extensible open-source internal developer portal from Qovery with 178+ stars . Lightweight alternative for teams wanting a portal foundation without Backstage's weight. Note: last pushed over a year ago — evaluate maintenance status before adoption .

- **[Hatica](https://github.com/haticahq/hatica)**  
  Open-source internal developer portal described as modern, powerful, and customizable . Active development signal.

- **[Meshery](https://github.com/meshery/meshery)**  
  CNCF project for standardizing and routinizing Kubernetes patterns. Meshery Catalog functions more like a cloud marketplace than a traditional software catalog — discover and deploy Kubernetes-based infrastructure and tools, share configurations and best practices. Best for orchestrating infrastructure needs and sharing platform patterns across teams .

- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  
  Open-source unified data platform creating a central metadata repository for observability, governance, and data discovery. Five components: UI, search engine, API catalog, entity store, and ingestion framework. More similar to an internal developer portal than a standard service catalog. JSON-based entity definitions support multiple languages .

- **[Backline](https://github.com/iamgoroot/backline)**  
  IDP inspired by Backstage, written in Go and HTMX . Lighter-weight alternative for teams preferring Go over React/TypeScript.

- **[x-port](https://github.com/tang95/x-port)**  
  Out-of-the-box internal developer portal based on platform engineering philosophy, aimed at improving developer experience and efficiency .

### Additional Strong Open-Source Options

- **Backstage Helm Charts** — Helm charts for deploying Backstage on Kubernetes .
- **backstage-plugin-common-tools** — Most commonly used developer tools within Backstage .
- **Platform Engineering Awesome Lists** — Curated collections of platform engineering tools including `awesome-platform-engineering` and `awesome-platform-engineering-tools` .
- **BACK Stack** — Ready-made environment combining Backstage, Crossplane, and ArgoCD with GitOps practices .
- **Rely.io Galaxy OSS** — Python framework for connecting to third-party APIs and mapping data into Rely's data model .

**Frameworks for building custom developer portal solutions**: Choose based on team capacity and requirements. **Backstage** for maximum extensibility and full control when you have 1–2 FTE to dedicate to maintenance . **Port** for production-grade catalog and self-service in days, with no operational burden . **Cortex** when leadership needs initiative tracking and compliance dashboards across 200+ services . **Kratix** for Kubernetes-native platform APIs, paired with a portal for the UI layer . **Meshery** for infrastructure orchestration and pattern sharing across Kubernetes environments . For most mid-market teams (30–200 devs), commercial portals offer faster time-to-value than self-hosted Backstage — the free tiers of Port make evaluation straightforward .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Developer portals integrate with source control, CI/CD, cloud infrastructure, and monitoring systems. Self-hosted solutions require proper security hardening, access controls, and ongoing maintenance.
- Backstage is a framework requiring significant engineering investment — treat it as a product, not a side project . Evaluate total cost of ownership (engineering headcount typically $200K–$500K/year for a platform team) before choosing self-hosted over commercial alternatives .
- The open-source ecosystem provides strong catalog, documentation, and scaffolding foundations, but managed operations, vendor support, and enterprise SLAs remain primarily commercial offerings.

---

**Made for platform engineers, DevOps leads, developer experience teams, and engineering leaders.**  
Let's make developer portals more open, transparent, and developer-centric.
