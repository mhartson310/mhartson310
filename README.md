# Cloud Security Architect | Azure · Zero Trust · AI Security · SIEM/XDR

I design secure cloud and AI architectures—and show how to **implement, validate, monitor, and govern them**.

**Identity → Platform → Workloads → Data & AI → Detection → Governance**

[LinkedIn](https://www.linkedin.com/in/mariohartson) · [Website](https://mhartson.com) · [Explore my work](#featured-architecture-and-security-engineering)

## Architecture decision-making

Alongside deployable reference patterns, I publish [architecture decision records, business-value trade-offs, and validation gates](https://github.com/mhartson310/Azure-Zero-Trust-Reference-Architectures/tree/main/docs/decision-framework/architecture-decision-framework) so reviewers can follow **why** a design was selected—not only what it contains.

## Featured architecture and security engineering

### 1. [Azure Zero Trust Reference Architectures](https://github.com/mhartson310/Azure-Zero-Trust-Reference-Architectures)

**Design → Terraform → Negative-security testing → Detection → SOAR → Controlled remediation**

Architecture reference patterns covering identity, workload permissions, private connectivity, monitoring, and security operations. Includes deployable implementation examples, KQL detections, validation scripts, playbooks, and an end-to-end Azure lab runbook.

**Start here:** [Architecture](https://github.com/mhartson310/Azure-Zero-Trust-Reference-Architectures/tree/main/architecture/enterprise-application) · [Terraform](https://github.com/mhartson310/Azure-Zero-Trust-Reference-Architectures/tree/main/terraform/enterprise-application) · [Validation runbook](https://github.com/mhartson310/Azure-Zero-Trust-Reference-Architectures/blob/main/docs/validation/zero-trust-end-to-end-runbook.md)

### 2. [Secure Enterprise RAG on Azure](https://github.com/mhartson310/Azure-Secure-Enterprise-RAG)

**Identity-aware retrieval → Authorization boundaries → Threat modeling → Observability**

A practical design for enterprise RAG with authorization before document content reaches the model. Covers Azure AI Search, application-level authorization, Entra ID, Managed Identity, Private Link, threat modeling, defensive controls, and Sentinel monitoring patterns.

**Start here:** [Architecture](https://github.com/mhartson310/Azure-Secure-Enterprise-RAG/tree/main/architecture) · [Threat model](https://github.com/mhartson310/Azure-Secure-Enterprise-RAG/blob/main/docs/threat-model.md) · [Security controls](https://github.com/mhartson310/Azure-Secure-Enterprise-RAG/blob/main/docs/security-controls.md)

### 3. [Sentinel KQL Library](https://github.com/mhartson310/Sentinel-KQL-Library)

**Detection logic → Tuning → Analytics-as-code → Automated triage → Approval-gated response**

Microsoft Sentinel and Defender detection examples with prerequisites, false-positive considerations, and response guidance. Includes architecture-linked Zero Trust KQL, Bicep analytics rules, automation rules, Logic Apps playbooks, and conditional-remediation decision models.

**Start here:** [Zero Trust detections](https://github.com/mhartson310/Sentinel-KQL-Library/tree/main/kql-queries/zero-trust/enterprise-application) · [Analytics Bicep](https://github.com/mhartson310/Sentinel-KQL-Library/tree/main/deploy/bicep/zero-trust-analytics) · [Response playbooks](https://github.com/mhartson310/Sentinel-KQL-Library/tree/main/deploy/playbooks/zero-trust)

## Platform, governance, and cost engineering

| Project | Engineering focus |
|---|---|
| [Azure Landing Zones](https://github.com/mhartson310/Azure-Landing-Zones) | Terraform hub/spoke modules, networking architecture, infrastructure review |
| [FedRAMP Azure Toolkit](https://github.com/mhartson310/FedRAMP-Azure-Toolkit) | Selected AC-2 and AU-2 control automation, account lifecycle, audit evidence |
| [Azure Cost Optimization Toolkit](https://github.com/mhartson310/Azure-Cost-Optimization-Toolkit) | FinOps, waste detection, resource analysis, reviewable optimization decisions |

## My architecture approach

**Problem → Architecture → Trust boundaries → Threats → Controls → Deployment → Validation → Monitoring**

I focus on practical questions:

- **What are we protecting?** Assets, identities, data, workloads, and business outcomes.
- **Where can it fail?** Trust boundaries, privilege paths, telemetry gaps, and unsafe assumptions.
- **How do we control risk?** Least privilege, workload identity, isolation, policy, monitoring, and response.
- **How do we prove it works?** Tests, reproducible deployment paths, detection logic, and documented evidence.

My portfolio emphasizes **inspectable engineering artifacts** over product claims. Reference implementations and CI checks are not represented as successful production deployments or live validation unless that evidence is available.

## Areas of focus

Azure security architecture · Zero Trust · Entra ID · Microsoft Sentinel · Defender XDR · KQL · Terraform · Private Link · Managed Identity · Cloud governance · FedRAMP patterns · Secure RAG · AI threat modeling · FinOps

## Connect

Interested in cloud security architecture, secure AI platforms, detection engineering, governance, or engineering collaboration?

[Connect on LinkedIn](https://www.linkedin.com/in/mariohartson) · [Visit my website](https://mhartson.com)
