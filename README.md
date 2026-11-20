# NOC to AI-Enabled SRE & CloudOps (90-Day GCP Build Log)

Public hands-on engineering log documenting my transition from reactive NOC operations to **AI-Enabled Site Reliability Engineering & CloudOps on Google Cloud Platform (GCP)**.

## Target Stack
* **Cloud & IaC:** GCP (VPC, IAM, Artifact Registry, Cloud Run, GKE, Cloud Trace/Monitoring), Terraform (GCS Remote State)
* **Containers & Orchestration:** Docker, Kubernetes (`v1.37` / `kind`), Helm (`v4`), Kustomize, Gateway API
* **Automation & Observability:** Python (`FastAPI`, `Pydantic`), Go, Linux Diagnostics, Prometheus, Grafana, OpenTelemetry (`gen_ai.*`)
* **AI SRE & Governance:** Google ADK 2.0, Gemini API / Vertex AI, RAG over Runbooks, K8sGPT, HolmesGPT, Read-Only RBAC & Human-in-the-Loop Guardrails

## Progress Tracker

| Phase | Timeline | Folder | Deliverable | Status |
| --- | --- | --- | --- | --- |
| **Phase 0** | Days 1–3 | [`/00-lab-setup`](./00-lab-setup) | Multi-node `kind` cluster, GCP keyless setup, billing guardrails, container templates | Complete |
| **Phase 1** | Days 4–30 | [`/01-ops-automation`](./01-ops-automation) & [`/02-terraform-gcp`](./02-terraform-gcp) | 3 automated NOC triage scripts + modular GCP VPC via Terraform | Next |
| **Phase 2** | Days 31–60 | [`/03-k8s-observability`](./03-k8s-observability) | Microservices on K8s + Prometheus/OTel + error-budget burn-rate alerts to Slack | Upcoming |
| **Phase 3** | Days 61–80 | [`/04-ai-sre-triage`](./04-ai-sre-triage) | Autonomous Incident Triage Bot (FastAPI + Alertmanager + RAG + Approval-Gated Slack RCA) | Upcoming |
| **Phase 4** | Days 81–90 | Portfolio & Docs | Architecture diagrams, demo GIF, 20-case eval report, interview drills | Upcoming |
