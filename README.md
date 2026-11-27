# Ugur Tuna

**AI Lead** in UK central government (2026–present) · Previously **University of Cambridge** (2023–2026) · Cambridge / London, UK

I work on AI architecture, evaluation, runtime controls, assurance, and workplace adoption across regulated and commercial settings. Across 9 years in UK central government, biomedical research data platforms, commercial production ML, and experimentation, I pair practical architecture with inspectable Python systems.

[Portfolio & essays](https://dsugurtuna.github.io) · [Systems index](https://dsugurtuna.github.io/projects.html) · [LinkedIn](https://www.linkedin.com/in/ugurtuna)

## Delivery track record

- **AI Lead, UK central government (2026–present):** Focused on AI technical roadmaps, engineering standards, and pre-deployment readiness gates across Microsoft Azure, LLM evaluation (`UK AISI Inspect`), runtime guardrails, `Python`/`FastAPI` reference patterns (`OpenAI API`), retrieval-grounded (`RAG`) and tool-calling agents (`Microsoft Copilot Studio`, `Power Apps`), and workplace `Microsoft Copilot` adoption.
- **Senior Data Scientist, University of Cambridge (2023–2026):** Delivered 82 governed data programmes (including 45 statutory UK GDPR Subject Access Requests) across 91,000+ participants under Five Safes governance, alongside clinical NLP pipelines, vision-language PII-audit prototyping, AI vendor benchmarking, and design-level AWS EKS and Terraform cloud architecture.
- **Senior Forecasting Analyst, FCIT Solutions Ltd (2021–2023):** Delivered £700K verified annual savings across 600,000+ SKUs (stockouts down 18%, excess inventory down 12%) from a production forecasting ensemble (`Temporal Fusion Transformers`, `N-BEATS`, `LightGBM`) served via FastAPI, Redis, MLflow, and Airflow.
- **Machine Learning Specialist (Contract), Xceptor (2021):** Shipped PyTorch/YOLOv5/OCR Document AI and FastAPI inference microservices with confidence-gated human review — achieving 96% end-to-end extraction accuracy on validation data, cutting manual processing by 40% and unmatched postings by 60%, and shortening month-end close by 2 days.
- **Data & Experimentation Analyst (Freelance), Patreon & Digital Clients (2017–2021):** Ran A/B and multivariate experiments and automated Python/SQL analytics pipelines, delivering up to 22% conversion uplift and 15% lower acquisition cost.

## Core AI systems

Open-source reference implementations built on synthetic and public data:

| Repository | Focus |
|---|---|
| **[`ai-systems-architecture`](https://github.com/dsugurtuna/ai-systems-architecture)** | Deployment-boundary gates (residency, failover parity), ADRs, and full-TCO routing economics across hosted, VPC, and open-weights clusters |
| **[`agent-guardrails`](https://github.com/dsugurtuna/agent-guardrails)** | Runtime `allow`/`draft`/`approve`/`block` policy gates, execution-time re-validation, idempotency, hash-chained audit logs, kill switches, and OpenAI / Azure OpenAI / Anthropic Claude adapters |
| **[`evidence-synthesis-eval`](https://github.com/dsugurtuna/evidence-synthesis-eval)** | Faithfulness, deterministic citation checks, weighted coverage, and blinded human-judge calibration (`Cohen's kappa`) on UK AISI `Inspect` |
| **[`ai-assurance-kit`](https://github.com/dsugurtuna/ai-assurance-kit)** | Open-source YAML assurance records, automated checks, GOV.UK ATRS public-licence templates, and illustrative governance reference mappings (NIST AI RMF) |

Clinical & genomics reference pipelines (synthetic data): [`clinical-cohort-ai-platform`](https://github.com/dsugurtuna/clinical-cohort-ai-platform) (NLP and PII-audit services with design-level Kubernetes and Terraform definitions) · [`hla-pipeline-manager`](https://github.com/dsugurtuna/hla-pipeline-manager) · [`genomic-cohort-delivery-pipeline`](https://github.com/dsugurtuna/genomic-cohort-delivery-pipeline)

## Writing (2026)

Practitioner notes on AI adoption, evaluation, runtime controls, and model economics ([all essays](https://dsugurtuna.github.io/writing/)):

- [Usage is not quality: what to measure when you roll out AI](https://dsugurtuna.github.io/writing/usage-is-not-quality.html) *(September 2026)* — Pre-defined task rubrics, fixed evaluation sets, and total human checking cost beyond seat telemetry
- [Read freely, write carefully: controls for AI agents that act](https://dsugurtuna.github.io/writing/read-freely-write-carefully.html) *(September 2026)* — Deterministic authorisation modes, execution-time re-validation, tamper-evident audit logs, and tested kill switches
- [A second model is a critic, not a verifier](https://dsugurtuna.github.io/writing/a-second-model-is-a-critic.html) *(September 2026)* — Limits of LLM-as-judge agreement, cited-source isolation, and blinded human calibration
- [Why you should write your own prompts](https://dsugurtuna.github.io/writing/write-your-own-prompts.html) *(November 2026)*
- [A partner, not a button: keeping judgement in AI workflows](https://dsugurtuna.github.io/writing/a-partner-not-a-button.html) *(November 2026)*
- [Beyond code: what most people actually need from AI](https://dsugurtuna.github.io/writing/ai-is-not-a-coding-tool.html) *(November 2026)*
- [Token price is a trap: pricing AI routing by total cost](https://dsugurtuna.github.io/writing/cheap-models-are-expensive.html) *(November 2026)*

## Engineering ownership & quality gates

- **Synthetic & public data only:** Public repositories hold standalone reference code and synthetic fixtures — zero employer code, participant records, or operational telemetry. Detailed employer context and role-tailored CVs are available via [LinkedIn](https://www.linkedin.com/in/ugurtuna).
- **Human ownership & CI verification:** Problem framing, architecture, threat modelling, domain logic, code review, and automated offline CI verification gates (linting, static checks where configured, and unit, property, or concurrency tests) are human-owned and reviewed.
