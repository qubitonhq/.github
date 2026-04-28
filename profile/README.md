# QubitOn

**Real-time validation, enrichment, and risk analytics for business data.**

One API key. 70+ capabilities. 250+ countries. 280M+ golden records. 1,200+ data sources.

[www.qubiton.com](https://www.qubiton.com) · [API Documentation](https://www.qubiton.com/docs) · [Free API Key](https://www.qubiton.com/auth/register)

## What is QubitOn?

QubitOn is an enterprise-grade API platform for cleansing, validating, enriching, and assessing business data. A single integration gives you access to address validation, tax ID verification, bank account checks, sanctions screening, corporate structure analysis, ESG scoring, and more.

## Open Source Connectors & SDKs

### Native Enterprise Connectors

| Connector | Platform | Language | Description |
|-----------|----------|----------|-------------|
| [qubiton-sap](https://github.com/qubitonhq/qubiton-sap) | SAP S/4HANA, ECC, BTP | ABAP | Native ABAP class — no middleware, full audit trail via SLG1 |
| [qubiton-oracle](https://github.com/qubitonhq/qubiton-oracle) | Oracle 11g+, EBS, Fusion | PL/SQL | 3-layer PL/SQL connector with EBS hooks and Fusion Cloud patterns |
| [qubiton-netsuite](https://github.com/qubitonhq/qubiton-netsuite) | All NetSuite editions | SuiteScript 2.1 | SDF-deployable SuiteApp with address correction accept/reject UI |
| [qubiton-servicenow](https://github.com/qubitonhq/qubiton-servicenow) | ServiceNow (Washington DC+) | JavaScript | 41-method Script Include with GlideAjax wrappers and field mapping helpers |

### Developer SDKs

| SDK | Language | Install |
|-----|----------|---------|
| [qubiton-go](https://github.com/qubitonhq/qubiton-go) | Go 1.22+ | `go get github.com/qubitonhq/qubiton-go` |
| [@qubiton/sdk](https://www.npmjs.com/package/@qubiton/sdk) | TypeScript / Node.js 18+ | `npm install @qubiton/sdk` |
| [qubiton-dotnet](https://github.com/qubitonhq/qubiton-dotnet) | C# / .NET (netstandard2.0, net6, net8, net10) | `dotnet add package Qubiton.Sdk` |
| [qubiton-java](https://github.com/qubitonhq/qubiton-java) | Java 11+ | Maven Central: `com.qubiton:qubiton-sdk` |
| Python | Python 3.9+ | Coming soon |

All SDKs share a unified surface: 44+ typed methods, OAuth2 + API key auth, automatic token refresh on 401, exponential backoff with jitter on 408/429/5xx, `Retry-After` honored (delta-seconds and HTTP-date), typed exception hierarchy, and full coverage of validation, compliance, risk, and enrichment endpoints across 250+ countries.

### Automation Platform Nodes

| Node | Platform | Install |
|------|----------|---------|
| [n8n-nodes-qubiton](https://github.com/qubitonhq/n8n-nodes-qubiton) | n8n | `npm install n8n-nodes-qubiton` |

### 30+ Pre-Built Integrations

AI Assistants (ChatGPT, Claude MCP, Copilot, Gemini, Grok) · Workflow Automation (Zapier, Make, n8n, Power Automate) · CRM (Salesforce, HubSpot) · Data Platforms (Snowflake, Databricks, BigQuery) · Middleware (MuleSoft, Boomi, Informatica) · Procurement (Coupa, SAP Ariba, Jaggaer) · Accounting (QuickBooks Online)

Browse all integrations at [www.qubiton.com/integrations](https://www.qubiton.com/integrations).

## API Capabilities

| Category | Examples |
|----------|----------|
| **Validation** | Address (249 countries), Tax ID (60+), Bank Account (180+), Email, Phone, Peppol |
| **Compliance** | Sanctions (OFAC, EU, UN), PEP screening, Disqualified directors, EPA prosecution |
| **Risk & Financial** | Bankruptcy, Credit score, Entity risk, Payment terms, Exchange rates |
| **Corporate Intelligence** | Beneficial ownership, Corporate hierarchy, DUNS lookup, Business registration |
| **Healthcare** | NPI validation, Provider exclusion, MEDPASS |
| **ESG & Cybersecurity** | ESG scores, Domain security, IP quality |

## Getting Started

1. **Sign up free** at [www.qubiton.com](https://www.qubiton.com/auth/register) — 100 API calls/month, no credit card
2. **Get your API key** from Dashboard → API Keys
3. **Pick your integration** — SDK, native connector, or pre-built integration
4. **Start validating** — one API call, instant results

## MCP Protocol Support

QubitOn is available as a native [Model Context Protocol](https://modelcontextprotocol.io/) server with 37+ tools, 20 workflow prompts, and 7 reference data resources for AI agents.

[MCP Manifest](https://mcp.qubiton.com/.well-known/mcp.json)

## About

QubitOn is built by [apexanalytix](https://www.apexanalytix.com), the global leader in P2P process automation, supplier management, and recovery audit services.

All connectors and SDKs are released under the [MIT License](https://opensource.org/licenses/MIT).
