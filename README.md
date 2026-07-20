# Hi, I'm Minhyeok Seo 👋

> **Backend & Platform Engineer focused on building reliable systems across backend engineering, deployment platforms, and cloud operations.**

I build and verify reliability across three connected layers:

```text
Backend Reliability
  → Deployment Reliability
  → Operational Reliability
```

## Featured Engineering Evidence

### 1. Mini Core Banking v2.2

**Reliable transfer backend** — Java 21, Spring Boot, PostgreSQL, Flyway, Testcontainers, Docker Compose, Prometheus, Grafana

- Explicit transaction boundary
- Pessimistic locking and deterministic lock ordering
- Idempotency replay/conflict handling
- Failed-attempt persistence, audit metadata, request IDs
- Integration, CI, runtime health, metrics, and dashboard verification

[Repository](https://github.com/cbssmh/mini-core-banking)

### 2. Golden Path Deployment Platform

**Reproducible local GitOps foundation** — kind, Kubernetes, Argo CD, App-of-Apps, Kustomize

- Pinned cluster, controller, source, and image inputs
- Annotated release identity and post-tag release ledger
- Two clean destroy/bootstrap verifications
- Synced/Healthy reconciliation, digest match, and runtime response

[Repository](https://github.com/cbssmh/golden-path-deployment-platform)

### 3. AI Job Scout: Cloud Operations Edition

**Azure application operations without product changes** — Container Apps, ACR, GitHub OIDC, Key Vault, Managed Identity, RBAC, OpenTelemetry, Application Insights

- Product Freeze: no feature, API, UI, AI, scoring, or database redesign
- Commit-SHA deployment and runtime verification
- Deployment/runtime identity separation and Key Vault-backed configuration
- Request/exception telemetry, correlation, and cost governance

[Repository](https://github.com/cbssmh/ai-job-scout)

## Supporting Evidence

- **[Mini ERP MM](https://github.com/cbssmh/mini-erp-mm)** — compact PR → PO → GR → inventory workflow
- **[Mudangyi Shuttle Decision System](https://github.com/cbssmh/mudangyi-shuttle-decision-system)** — conservative rule-based backend decision support
- **[WorldJob Notifier](https://github.com/cbssmh/worldjob-notifier)** — checkpoint-based monitoring and duplicate prevention
- **[Hacker News Reading Decision Engine](https://github.com/cbssmh/Hacker-News-Reading-Decision-Engine)** — failure-aware reading-decision pipeline
- **[Google Alerts AI Landscape](https://github.com/cbssmh/google-alerts-ai-landscape)** — deterministic selection and validated AI-assisted synthesis

## Team Experience

**Team Gunchi** — contributed DXF data/training analysis and a parameterized model-training workflow with file-level splits, evaluation, artifact output, and integration into the team retraining path. The broader API, UI, database, deployment, and Cesium system were team context rather than my sole ownership.

## Capability Map

| Capability | Evidence |
|---|---|
| Transactions · concurrency · idempotency | Mini Core Banking v2.2 |
| GitOps · immutable inputs · clean rebuilds | Golden Path Deployment Platform |
| Azure deployment · identity · secrets · telemetry | AI Job Scout: Cloud Operations Edition |
| Workflow/state modeling | Mini ERP MM |
| Stateful automation | WorldJob Notifier |
| Team integration | Team Gunchi |

## Background

- B.S. Candidate in Computer Science, Gachon University — Expected Feb 2027
- KATUSA / Unit Supply Specialist (92Y), 2022–2024
- ADsP · TOEIC 830 · TOEIC Speaking IM3/130
- Based in Seoul, South Korea

## Contact

- LinkedIn: https://www.linkedin.com/in/minhyeok-seo
- Email: cbssmh@gmail.com

<sub>These repositories are project-based engineering evidence. They do not claim production banking, enterprise platform ownership, large-scale cloud migration, or professional years of experience.</sub>
