<div align="center">

<br>

# Shreyas Shelar

**Software Engineer &nbsp;·&nbsp; Distributed Systems &nbsp;·&nbsp; Fintech &nbsp;·&nbsp; Cloud**

Pune, India

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-shreyasshelar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shreyasshelar)
&nbsp;
[![Email](https://img.shields.io/badge/Email-shreyasshelarrr%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:shreyasshelarrr@gmail.com)
&nbsp;
[![AWS Certified](https://img.shields.io/badge/AWS_Data_Engineer-Associate_·_Oct_2025-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/27ced960-e42f-4114-927e-2a53db55b5d7/public_url)

<br>

</div>

---

Backend engineer building production-grade distributed systems at scale. At **Kanaka Software**, I engineer a forex treasury management platform serving **16,000+ clients** across swaps, spot, tom/cash, and forward contracts — owning real-time trade execution, post-trade settlement, and platform-wide infra services.

---

## What I Build

- **High-throughput pipelines** — Reduced a data ingestion job processing 81K API calls from ~269 days → 6 hours (>99.9% improvement) via nested parallelism and HTTP/2 upgrade
- **Distributed backends** — Event-driven microservices, Saga orchestration, CQRS, transactional outbox, distributed caching — engineered for correctness under failure
- **Fintech infrastructure** — Payment systems, ledger design, reconciliation engines, fraud detection pipelines, OAuth2/OIDC multi-IdP federation, AES encryption at rest
- **Greenfield services** — Notification engine, email pipeline, distributed Quartz scheduler, document management system (1,000+ encrypted docs/month), custom DB-to-DB integration engine replacing AWS DMS

---

## Flagship Project

### [AegisPay](https://github.com/shreyasshelar/AegisPay) — Event-Driven Fintech Platform

Production-grade payment infrastructure built from the ground up.

`Java 21` `Spring Boot 3.3` `Apache Kafka` `PostgreSQL` `ClickHouse` `Redis` `Kubernetes` `ArgoCD` `AWS EKS`

- **10 microservices** over **18 Kafka topics (KRaft)** with 5-step Saga orchestration, compensating transactions, and exactly-once delivery via transactional outbox
- **Stripe PaymentIntents + 3DS**, multi-IdP OAuth2/OIDC (Keycloak / Entra / Okta), zero-trust JWT relay, dual-key Redis token-bucket rate limiting
- **Spring Batch reconciliation** comparing ledger COMMITs against Stripe Balance Transactions API — catching MISSING_IN_STRIPE, MISSING_IN_LEDGER, AMOUNT_MISMATCH
- **4 AI components** — RAG fraud copilot (pgvector + Claude), agentic incident triage, multimodal KYC/OCR, LLM error resolution — all with AI audit log for RBI/DPDP compliance
- **GitOps on AWS EKS** via ArgoCD, umbrella Helm chart across 3 environments, GitHub Actions parallel CI/CD, secrets via HashiCorp Vault + ESO, full distributed tracing (W3C → Micrometer → Prometheus → Grafana)

---

## Tech Stack

**Backend & Architecture**

![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring Batch](https://img.shields.io/badge/Spring_Batch-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)

**Databases & Streaming**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS_(EKS·MSK·RDS·S3)-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP_(BigQuery·Looker)-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Observability & Security**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![HashiCorp Vault](https://img.shields.io/badge/HashiCorp_Vault-000000?style=flat-square&logo=vault&logoColor=white)
![OAuth2/OIDC](https://img.shields.io/badge/OAuth2_·_OIDC-000000?style=flat-square&logo=openid&logoColor=white)

**AI & LLM**

![Claude API](https://img.shields.io/badge/Claude_API-CC785C?style=flat-square&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_·_pgvector-4169E1?style=flat-square)
![Agentic Workflows](https://img.shields.io/badge/Agentic_Workflows-6B52AE?style=flat-square)

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=shreyasshelar&show_icons=true&theme=default&hide_border=true&count_private=true&include_all_commits=true&card_width=450" alt="GitHub Stats" />

&nbsp;&nbsp;

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shreyasshelar&layout=compact&theme=default&hide_border=true&card_width=350" alt="Top Languages" />

<br><br>

<img src="https://streak-stats.demolab.com?user=shreyasshelar&theme=default&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub Streak" />

</div>

---

## Certification

**[AWS Certified Data Engineer — Associate](https://www.credly.com/badges/27ced960-e42f-4114-927e-2a53db55b5d7/public_url)** &nbsp;·&nbsp; Amazon Web Services &nbsp;·&nbsp; Oct 2025

---

<div align="center">

[linkedin.com/in/shreyasshelar](https://linkedin.com/in/shreyasshelar) &nbsp;·&nbsp; [shreyasshelarrr@gmail.com](mailto:shreyasshelarrr@gmail.com) &nbsp;·&nbsp; Pune, India

<br>

</div>
