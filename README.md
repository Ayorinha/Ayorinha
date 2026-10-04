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

My portfolio is organized around one principle:

**Intelligence ≠ Authorization ≠ Execution**

---

## 🏆 Engineering Evidence

**Verified engineering evidence:** AYORAI ATTRACTOR — F1 evaluation evidence at **76.67% / 66.67% / 33.33%**, with the historical **43.33%** majority-class baseline explicitly retained for comparison · CI on Python 3.11–3.13 · coverage ratchet verified at 73% · strict typing on the evidence core · frozen golden set (34 cases, 52 documents, SHA-256 manifest).

**Primary engineering themes:** AI Safety · Agent Security · Agentic Systems · RAG · MCP · Document Intelligence · Automation · Data Engineering

This profile intentionally surfaces the projects that best demonstrate **architecture, security, reproducibility, testing, observability and production-oriented engineering** rather than a large collection of isolated demos.

---

# ⭐ Featured Projects

<div align="center">

## 01 · AYORAI ATTRACTOR
### Evidence-first claim-level verification

**Checks whether a claim is actually supported by the sources cited for it.**

[Repository](https://github.com/Ayorinha/ayorai-opensearch) · [Baseline / Evaluation](https://github.com/Ayorinha/ayorai-opensearch/tree/main/docs/eval)

</div>

> **ATTRACTOR is the evaluation and verification layer of the portfolio:** it separates claims, evidence, stance, provenance and deterministic judgment instead of treating an LLM response as proof.

**Current evidence**

- Golden v0 frozen: **34 cases · 52 documents**
- Frozen SHA-256 manifest
- F1 evaluation evidence: **76.67% / 66.67% / 33.33%**
- Historical majority-class baseline: **43.33%**
- Scenario classification: **A = EVAL_ONLY · B = Commercial Candidate**
- Deterministic Judge: **6/6 fixtures passing**
- CI: **Python 3.11 · 3.12 · 3.13**
- Ruff + mypy + pytest + CodeQL + workflow-lint

**Architecture**

```text
Claim
  ↓
Evidence
  ↓
Stance
  ↓
Provenance
  ↓
Evidence Clusters
  ↓
Deterministic Judge
  ↓
VERIFIED · SUPPORTED · PARTIALLY_SUPPORTED
CONFLICTING · REFUTED · UNVERIFIED
  ↓
Auditable verdict
```

**F1 evaluation evidence**

```text
Primary evaluated result     76.67%
Additional evaluated result  66.67%
Evaluation scenario result   33.33%
Historical baseline           43.33%
```

The **43.33%** figure is retained as the historical majority-class baseline; it is not presented as the current F1 result.

**Scenario classification:** `A = EVAL_ONLY` · `B = Commercial Candidate`

**Why it matters:** ATTRACTOR turns citation verification into an explicit engineering problem with reproducible evaluation, deterministic judgment and auditable evidence chains — rather than relying on an opaque LLM-as-judge pattern.

---

<div align="center">

## 02 · AYORAI AI Shield
### Deterministic runtime defense for autonomous AI agents

[Repository](https://github.com/Ayorinha/ayorai-vision-intelligence)

</div>

The flagship AI Safety project. The model may propose an action, but execution requires deterministic policy, identity, authorization and security controls.

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

**Demonstrates:** least privilege · fail-closed controls · threat modeling · MCP security · adversarial evaluation · auditability · CI/CD · security testing.

---

### 03 · AYORAI
**Agentic AI engineering framework**

[Repository](https://github.com/Ayorinha/ayorai)

A modular foundation for agents, orchestration, safety controls, memory, RAG, MCP and governed tools.

---

### 04 · AgentHound
**Security analysis of multi-agent architectures**

[Repository](https://github.com/Ayorinha/AgentHound)

Analyzes agent architectures for risky capability paths using a normalized graph model and rule engine.

---

### 05 · MCP-Sentinel
**Security gateway for Model Context Protocol environments**

[Repository](https://github.com/Ayorinha/MCP-Sentinel)

Deterministic authorization boundary for MCP tools with schema validation, least privilege and structured audit decisions.

---

### 06 · AyorGraph
**Explicit graph orchestration for AI agents**

[Repository](https://github.com/Ayorinha/AyorGraph)

Represents agents, tools, validation and execution paths as an explicit graph instead of an opaque chain.

---

### 07 · RAG Framework
**Modular Retrieval-Augmented Generation framework**

[Repository](https://github.com/Ayorinha/RAG-framework)

Separates loaders, chunkers, embedders, retrievers, rerankers and generators behind explicit contracts.

---

### 08 · vault-mcp
**Private knowledge access through MCP**

[Repository](https://github.com/Ayorinha/vault-mcp)

MCP-based access layer for local knowledge bases, hybrid search, semantic retrieval and controlled tool access.

---

### 09 · Hybrid Data Management RPA Pipeline
**Validation-first operational data pipeline**

[Repository](https://github.com/Ayorinha/hybrid-data-management-rpa-pipeline)

A reproducible foundation for RPA-ready data workflows and operational data quality.

---

### 10 · AYORAI Financial Control
**Synthetic financial reconciliation and state analytics**

[Repository](https://github.com/Ayorinha/project-ayorai-financial-control)

Runnable synthetic-data project for reconciliation, settlement analysis and state-level aggregation.

---

### 11 · Global Tech News AI
**Public technology intelligence platform**

[Repository](https://github.com/Ayorinha/global-tech-news-ai) · [Live platform](https://ayorinha.github.io/global-tech-news-ai/)

Public-facing intelligence hub combining automated ingestion, structured data, AI tooling intelligence and a defensive AI laboratory.

---

# 🧭 Portfolio Architecture

The projects are not isolated demos. Together they form an engineering stack:

```text
                    AYORAI · APPLIED INTELLIGENCE
                              │
             ┌────────────────┼────────────────┐
             │                │                │
        Intelligence      Agentic AI       Data / Docs
             │                │                │
      Global Tech       AYORAI / AyorGraph   RAG
         News           AgentHound           Doc Intelligence
                          MCP-Sentinel       Data Pipelines
                          AI Shield           Financial Control
                              │
                              ↓
                     Security + Governance
                              │
                              ↓
                     Authorization / Policy
                              │
                              ↓
                         Execution
                              │
                              ↓
                    Audit / Observability
```

### Engineering boundary

```text
Reasoning
   ≠
Authorization
   ≠
Execution
```

That separation is the central design pattern across the AI Safety projects.

---

# 🔬 Engineering Standards

Every serious project is progressively evaluated against:

| Layer | Evidence |
|---|---|
| Architecture | Explicit components, boundaries and data flow |
| Security | Threat model, least privilege, fail-closed controls |
| Quality | Tests, linting and static analysis |
| Reproducibility | Deterministic examples and documented setup |
| Observability | Logs, events, traces or audit evidence |
| Evaluation | Regression tests and measurable validation |
| Delivery | GitHub Actions / CI/CD where applicable |
| Documentation | Architecture, assumptions, limitations and roadmap |
| Privacy | Public, synthetic or anonymized data |

---

# 🧰 Technical Focus

**AI Engineering**  
Python · LLMs · Agents · RAG · Generative AI · NLP · Vision AI

**AI Safety & Security**  
Policy Engines · Tool Authorization · Least Privilege · MCP Security · Threat Modeling · Adversarial Evaluation · Auditability

**Data Engineering**  
SQL · pandas · NumPy · ETL / ELT · Data Quality · Power BI

**Backend & Systems**  
FastAPI · REST · APIs · JSON · Docker

**Document Intelligence**  
OCR · OpenCV · Tesseract · PDF Processing

**Engineering & DevSecOps**  
Git · GitHub Actions · pytest · Ruff · Bandit · Dependency Auditing · CI/CD

**AI Infrastructure**  
Local LLMs · Private AI · AWS · Observability

---

# 🌐 Portfolio

**AYORAI · Applied Intelligence**  
https://ayorinha.github.io/global-tech-news-ai/

**GitHub**  
https://github.com/Ayorinha

**LinkedIn**  
https://www.linkedin.com/in/anderson-leon-ayora

---

## Education

**MBA — Data Science, Analytics & Artificial Intelligence — USP/Esalq**  
2026–2027

**Technology in Database — FIAP**  
Completed · 2022

---

## 📄 License

This portfolio and its original source code are released under the **MIT License**.

[View MIT License](LICENSE)

Copyright © 2026 Anderson Leon Ayora

---

<p align="center">
  <strong>AYORAI · Applied Intelligence</strong><br/>
  <sub>Applied AI · AI Engineering · AI Safety</sub>
</p>
