## Shareef Syed

Platform and solutions engineer in Hyderabad, India. I build and run the internal platform that 200+ people at Signant Health use for access requests, workflow automation, enterprise integrations and AI tooling. Finance, supply chain, clinical-operations and IT teams bring me requests, and I build, ship and support the result.

**Open to forward deployed and solutions engineering roles.** · [Portfolio](https://shareefsyeds.github.io) · [LinkedIn](https://www.linkedin.com/in/shareefsyed/) · [Resume](https://shareefsyeds.github.io/Shareef-Syed-Resume.pdf)

### Selected work

| Project | What it shows | Status |
|---|---|---|
| [From custom code to low-code workflows](https://shareefsyeds.github.io/projects/workflow/) | A visual workflow engine with 50 ready steps and Teams approvals. A real flow was built in 15 minutes with no code. | Live |
| [250+ internal API operations as MCP tools](https://github.com/shareefsyeds/case-studies/blob/main/mcp-gateway.md) | 250+ MCP tools generated from OpenAPI specs plus a curated set, with authorization kept in the apps | Live |
| [A reusable app template with 13 integration adapters](https://shareefsyeds.github.io/projects/template/) | Sign-in, roles, audit log and 13 integration adapters for every new app. An invoicing app on it serves 100+ users. | In use |
| [Contractor timesheets with real-time Snowflake sync](https://shareefsyeds.github.io/projects/timesheets/) | Replaced a weekly batch with real-time sync to Snowflake and Certinia, built with two colleagues | Live |
| [A document assistant on Bedrock](https://shareefsyeds.github.io/projects/rag/) | Retrieval-augmented answers over internal documents, in the web app and Microsoft Teams | Pilot |
| [An AI agent team with human approval](https://shareefsyeds.github.io/projects/agents/) | AI plans and drafts code changes. A person approves the plan and merges the result. | In development |

Each project has a full write-up with an interactive diagram in [case-studies](https://github.com/shareefsyeds/case-studies).

### Also on the platform

- **Eight self-service apps** that let staff run routine operations themselves: release automation, environment builds (21 automated steps), self-service database accounts, data provisioning with expiry, multi-tenant account management, email deliverability checks, document delivery and operational dashboards. Every action is audited.
- **Observability, uptime monitoring and credential vault:** metrics, logs, alerting and runbooks, self-hosted uptime checks on an open-source monitor with Teams alerts, plus secrets with KMS envelope encryption, rotation and Azure AD directory sync.
- **Shared packages:** Entra ID sign-in with JWT, API keys and RBAC, and AWS connection management with credential rotation and audit, shared by several internal apps.
- **AWS infrastructure in Terraform:** moved production from a single VM to Amazon EKS with Karpenter, Aurora Serverless v2 and keyless GitHub OIDC deploys.
- **Cost:** traced 91% of an AWS account's CloudWatch log spend to one DEBUG-level Lambda, a ~$3K/month fix, and proposed a self-hosted log stack projected to save ~$47.9K a year.

### How I work

- **Requirements from the source.** I work directly with the finance, supply chain, clinical-operations and IT colleagues who raise each request.
- **Low-code first.** Routine automation is built from ready workflow steps. Custom code is used where it is actually needed.
- **Human approval on AI work.** AI drafts and automates, and a person approves before anything changes.

### Toolbox

Python · Django · React · TypeScript · SQL and PL/SQL · AWS (EKS, RDS, Lambda, Bedrock) · Terraform · Kubernetes · MCP · NetSuite · Snowflake · ServiceNow · Certinia · Jira · Microsoft Teams · Oracle · SQL Server · PostgreSQL

### Background

Four years as an Oracle DBA running client databases at service firms, two years building AWS infrastructure at Autodesk, and since 2022 at Signant Health, first in cloud operations, then building and running the internal platform.
