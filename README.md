# Anderson Leon Ayora

<p align="center">
  <strong>AI ENGINEER · APPLIED AI · AI SAFETY</strong><br/>
  <sub>Agentic AI · RAG · MCP · Security · Document Intelligence · Data Engineering</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/anderson-leon-ayora">LinkedIn</a> ·
  <a href="https://github.com/Ayorinha">GitHub</a> ·
  <a href="https://ayorinha.github.io/global-tech-news-ai/">AYORAI · Applied Intelligence</a>
</p>

> I build AI systems where **reasoning, authority and execution are explicit engineering boundaries**.

**Intelligence ≠ Authorization ≠ Execution**

---

## Engineering Focus

My portfolio focuses on **Applied AI, AI Engineering and AI Safety**, with emphasis on:

**Architecture · Security · Evaluation · Reproducibility · Observability · Governance**

The work spans agentic systems, RAG, MCP, document intelligence, data pipelines and deterministic controls for AI-assisted execution.

---

# Featured Projects

## 01 · Global Tech News AI
### Public technology intelligence platform

[Repository](https://github.com/Ayorinha/global-tech-news-ai) · [Live platform](https://ayorinha.github.io/global-tech-news-ai/)

A public-facing intelligence platform combining automated technology ingestion, structured data, AI tooling intelligence and an AI Safety laboratory.

**Role in the portfolio:** public intelligence and research layer.

---

## 02 · AYORAI ATTRACTOR

<a href="https://github.com/Ayorinha/ayorai-opensearch"><img src="https://raw.githubusercontent.com/Ayorinha/ayorai-opensearch/main/docs/assets/brand/ayorai-attractor-banner.png" alt="AYORAI ATTRACTOR" width="100%"></a>

### Evidence-first AI verification

[Repository](https://github.com/Ayorinha/ayorai-opensearch) · [Evaluation](https://github.com/Ayorinha/ayorai-opensearch/tree/main/docs/eval)

[For partners and investors](https://github.com/Ayorinha/ayorai-opensearch/blob/main/docs/INVESTIDORES.md)

> **AI can produce an answer. ATTRACTOR asks: where is the evidence?**

**ATTRACTOR** is an evidence-verification layer for AI systems that transforms claims into **traceable, reproducible and auditable** verification results.

```text
                    AI / Human Claim
                           │
                           ▼
                    ┌─────────────┐
                    │   Evidence  │
                    └──────┬──────┘
                           │
                           ▼
                    ┌─────────────┐
                    │    Stance   │
                    └──────┬──────┘
                           │
                           ▼
                    ┌─────────────┐
                    │ Provenance  │
                    └──────┬──────┘
                           │
                           ▼
                 ┌───────────────────┐
                 │ Evidence Clusters │
                 └─────────┬─────────┘
                           │
                           ▼
                 ┌───────────────────┐
                 │ Deterministic     │
                 │      Judge        │
                 └─────────┬─────────┘
                           │
                           ▼
                    ┌─────────────┐
                    │   Verdict   │
                    └──────┬──────┘
                           │
                           ▼
                    Auditable Record
```

**Core principle:** **LLM ≠ Judge.** The model may help discover or interpret evidence, but final verification is determined by **explicit, auditable rules**.

### Governance and regulated environments

ATTRACTOR is designed for scenarios where **traceability, integrity, security and auditability** matter, with an initial focus on Brazilian telecommunications regulation (Anatel RGC) and LGPD-aware workflows.

It can support governance and validation processes involving evidence, provenance and reproducibility. It **does not claim regulatory compliance by itself**.

Relevant Brazilian reference: the **LGPD (Law No. 13,709/2018)**. The architecture is also designed to support controls informed by **rules issued by financial-system and capital-market regulators**, without asserting regulatory compliance by itself.

### Experimental evidence

- Golden v0: **34 cases · 52 documents · SHA-256 manifest** (development/evaluation set)
- F1 global-verdict accuracy, always reported side by side (n = 30 each):

| Path | Golden v0 | Golden v0.1 |
|---|---:|---:|
| A (EVAL_ONLY, research-only) | 40.00% | 76.67% |
| B (commercial candidate) | 43.33% | 66.67% |
| C (rules) | 26.67% | 33.33% |
| Majority baseline | 43.33% | 43.33% |

- On Golden v0, Path B equals the majority baseline. Golden v0.1 was rewritten after per-case results were observed, so it is **not** independent confirmatory evidence.
- Development sets use synthetic English documents; Portuguese performance is reserved for the hidden Golden v1.
- Judge 2.0 (deterministic adjudication, canonical output, rule trace and generated traceability) shipped in v0.5.0.
- CI: **Python 3.11 · 3.12 · 3.13** with Ruff, mypy, pytest, CodeQL and workflow-lint; `main` is protected by required checks.
- Release: **v0.5.0** · DOI: **10.5281/zenodo.23344005** · all versions: **10.5281/zenodo.23125082**

**Evaluation classification:** `A = EVAL_ONLY` · `B = Commercial Candidate`

> **Do not trust the AI response alone. Verify the evidence.**

---

## 03 · AYORAI AI Shield
### Deterministic runtime defense for autonomous AI agents

[Repository](https://github.com/Ayorinha/ayorai)

A security boundary where model intent does not automatically become executable authority.

```text
Agent
  ↓
Identity / Delegation
  ↓
MCP Tool Integrity
  ↓
Runtime Containment
  ↓
Data-flow Guard
  ↓
Policy + Authorization
  ↓
Transaction / Egress Governance
  ↓
Tool Execution
  ↓
Provenance / Audit
```

**Focus:** least privilege · fail-closed controls · MCP security · threat modeling · adversarial evaluation · auditability.

---

# Portfolio Architecture

The three featured projects form a compact applied-AI portfolio:

```text
             AYORAI · APPLIED INTELLIGENCE
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
 Global Tech News   AYORAI ATTRACTOR   AYORAI AI Shield
 Intelligence       Evidence-first     Runtime defense
       │             verification            │
       └─────────────────┼─────────────────┘
                         ↓
              Security + Governance
                         ↓
             Authorization / Policy
                         ↓
                     Execution
                         ↓
              Audit / Observability
```

The recurring architectural boundary is:

```text
Reasoning
   ≠
Authorization
   ≠
Execution
```

---

# Engineering Standards

| Layer | Evidence |
|---|---|
| Architecture | Explicit components, boundaries and data flow |
| Security | Threat models, least privilege and fail-closed controls |
| Quality | Tests, linting and static analysis |
| Reproducibility | Deterministic examples and documented setup |
| Evaluation | Regression tests and measurable validation |
| Observability | Logs, traces, metrics or audit evidence |
| Delivery | CI/CD and automated quality gates |
| Documentation | Architecture, assumptions, limitations and roadmap |
| Privacy | Public, synthetic or anonymized data |

---

# Technical Stack

**AI Engineering**  
Python · LLMs · Agents · RAG · Generative AI · NLP · Vision AI

**AI Safety & Security**  
Policy Engines · Tool Authorization · Least Privilege · MCP Security · Threat Modeling · Adversarial Evaluation · Auditability

**Data & Document Intelligence**  
SQL · pandas · NumPy · ETL/ELT · Data Quality · Power BI · OCR · OpenCV · Tesseract · PDF Processing

**Backend & Infrastructure**  
FastAPI · REST · APIs · JSON · Docker · AWS · Local LLMs · Private AI

**Engineering**  
Git · GitHub Actions · pytest · Ruff · mypy · Bandit · Dependency Auditing · CI/CD · Observability

---

# Links

**AYORAI · Applied Intelligence**  
https://ayorinha.github.io/global-tech-news-ai/

**GitHub**  
https://github.com/Ayorinha

**LinkedIn**  
https://www.linkedin.com/in/anderson-leon-ayora

---

# Education

**MBA — Data Science, Analytics & Artificial Intelligence — USP/Esalq**  
2026–2027

**Technology in Database — FIAP**  
Completed · 2022

---

## License

This portfolio and its original source code are released under the **MIT License**.

[View MIT License](LICENSE)

Copyright © 2026 Anderson Leon Ayora

<p align="center">
  <strong>AYORAI · Applied Intelligence</strong><br/>
  <sub>Applied AI · AI Engineering · AI Safety</sub>
</p>
