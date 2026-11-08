# Anderson Leon Ayora

<p align="center">
  <strong>AI ENGINEER · APPLIED AI · AI SAFETY</strong><br/>
  <sub>Agentic AI · Evidence Verification · RAG · MCP · Security · Document Intelligence · Data Engineering</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/anderson-leon-ayora">LinkedIn</a> ·
  <a href="https://github.com/Ayorinha">GitHub</a> ·
  <a href="https://ayorinha.github.io/global-tech-news-ai/">AYORAI · Applied Intelligence</a>
</p>

> I build AI systems where **reasoning, authorization and execution are explicit engineering boundaries**.

<p align="center"><strong>INTELLIGENCE ≠ AUTHORIZATION ≠ EXECUTION</strong></p>

---

## Engineering focus

My work sits at the intersection of **AI Engineering, Applied AI and AI Safety**. I focus on systems that can be inspected, evaluated and operated with explicit controls:

- Agentic systems, tool use and MCP security
- Evidence-grounded verification, RAG and document intelligence
- Deterministic policy and decision boundaries
- Evaluation methodology, reproducibility and statistical calibration
- Data engineering, observability and audit trails

I favor measurable evidence over unsupported capability claims: implemented features, experimental results, limitations and open work are documented separately.

## Featured projects

### 01 · Global Tech News AI — Applied technology intelligence

**[Repository](https://github.com/Ayorinha/global-tech-news-ai)** · **[Live platform](https://ayorinha.github.io/global-tech-news-ai/)**

A public technology intelligence platform combining automated information ingestion, structured data, AI tooling intelligence and an AI Safety research area.


### 02 · AYORAI ATTRACTOR — Evidence-first AI verification

<p align="center">
  <a href="https://github.com/Ayorinha/ayorai-opensearch"><img src="https://raw.githubusercontent.com/Ayorinha/ayorai-opensearch/main/docs/assets/brand/ayorai-attractor-banner.png" alt="AYORAI ATTRACTOR" width="100%"></a>
</p>

**[Repository](https://github.com/Ayorinha/ayorai-opensearch)** · **[Technical status](https://github.com/Ayorinha/ayorai-opensearch/blob/main/docs/STATUS.md)** · **[Documentation](https://github.com/Ayorinha/ayorai-opensearch/tree/main/docs)** · **[Public site](https://ayorinha.github.io/ayorai-opensearch/)**

An open-source verification layer designed to inspect AI-generated claims against their cited evidence, preserve provenance and produce reproducible, rule-governed verdicts.

**Core architecture:** models may assist with evidence discovery and interpretation; a deterministic Judge applies explicit, versioned rules to determine the final verdict. The system separates analysis from decision authority.

```text
AI / Human Claim
      ↓
Evidence + Provenance
      ↓
Evidence Analysis
      ↓
Deterministic Judge
      ↓
Versioned Verdict
      ↓
Auditable Record
```

#### Latest published release and experimental evidence

- **Release:** v0.7.0 · **Version DOI:** [10.5281/zenodo.24045951](https://doi.org/10.5281/zenodo.24045951)
- **Concept DOI:** [10.5281/zenodo.23125082](https://doi.org/10.5281/zenodo.23125082)
- **Calibration V2 DEV:** 30,420 examples across 11 cohorts in the English-language LLM-AggreFact dataset.
- **Balanced accuracy, cross-fitted (DEV-A):** FactCG **74.68%** (selected), MiniCheck **72.87%**, mDeBERTa **62.57%**.
- **FactCG probabilistic metrics (DEV-A):** AUROC **0.8650**, AUPRC **0.9454**, Brier **0.1168**, ECE **0.0054**.

These are development-partition results, not TEST, production performance, an external validation or a ranking. The original v0.7.0 LTT rule reported 0/11 cohorts certified. A post-hoc re-aggregation under Amendment 2 found four cohorts passing the amended procedure in DEV (RAGTruth, ClaimVerify, Lfqa and Reveal); this is explicitly exploratory, not confirmatory certification. Seven cohorts did not reject the null at their first tested threshold. The follow-up power analysis proposes (but does not adopt) a 367-accepted-sample operational floor for discussion in v0.8; this would make some smaller cohorts untestable by design. Confirmatory certification remains reserved for untouched TEST data under a rule frozen in advance.

**Scientific and domain limits:** no Portuguese benchmark result is published; the Brazilian RGC protocol remains in development and is not frozen. The project does not claim certification, guaranteed hallucination detection or regulatory compliance by itself. Third-party models and datasets are credited in the [benchmark report](https://github.com/Ayorinha/ayorai-opensearch/tree/main/reports/benchmarks/2026-11-07-dev-calibration-v2). The subsequent [Amendment 2 exploratory report and LTT power analysis](https://github.com/Ayorinha/ayorai-opensearch/tree/main/reports/benchmarks/2026-11-08-phase1b-amendment-2-exploratory) documents the post-hoc re-aggregation and the proposed v0.8 sample-size floor.



### 03 · AYORAI AI Shield — Runtime defense for AI agents

**[Repository](https://github.com/Ayorinha/ayorai)**

A security-oriented project exploring deterministic boundaries between model intent and executable authority, with focus on least privilege, policy enforcement, MCP integrity, runtime containment and auditability.


---

## Engineering principles

| Area | Approach |
|---|---|
| Architecture | Explicit components, contracts and trust boundaries |
| AI safety | Model output is not authorization |
| Security | Least privilege, fail-closed controls and threat modeling |
| Evaluation | Reproducible datasets, baselines and regression tests |
| Statistics | Pre-registration, partition discipline and declared uncertainty |
| Observability | Traceability, provenance and audit records |
| Delivery | CI, static analysis and documented release artifacts |
| Privacy | Public, synthetic or appropriately anonymized data |

## Technical stack

**AI & ML**  
Python · LLMs · Agents · RAG · NLP · Document Intelligence · Model Evaluation · Calibration

**AI Safety & Security**  
MCP · Tool Authorization · Policy Engines · Least Privilege · Threat Modeling · Adversarial Evaluation · Auditability

**Data Engineering**  
SQL · pandas · NumPy · ETL/ELT · Data Quality · Power BI

**Backend & Infrastructure**  
FastAPI · REST · Docker · AWS · Local LLMs · Private AI

**Engineering & Quality**  
Git · GitHub Actions · pytest · Ruff · mypy · CodeQL · CI/CD · Reproducibility

## Professional background

I bring experience across data, software, document-centric workflows and applied AI, connecting engineering execution with process reliability, traceability and operational constraints.

My current technical interests include evidence-grounded AI, agentic systems, security boundaries, evaluation science and responsible deployment in environments where decisions must be explainable and auditable.

## Education

- **MBA — Data Science, Analytics & Artificial Intelligence, USP/Esalq** · 2026–2027
- **Technology in Database, FIAP** · Completed 2022

## Links

- **GitHub:** https://github.com/Ayorinha
- **LinkedIn:** https://www.linkedin.com/in/anderson-leon-ayora
- **AYORAI · Applied Intelligence:** https://ayorinha.github.io/global-tech-news-ai/

---

<p align="center">
  <strong>AYORAI · Applied Intelligence</strong><br/>
  <sub>Applied AI · AI Engineering · AI Safety · Evidence · Governance</sub>
</p>

<p align="center"><sub>Copyright © 2026 Anderson Leon Ayora</sub></p>
