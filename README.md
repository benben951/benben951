# Zhaojie Guo

LLM evaluation, risk-review AI, and agent workflow systems.

I work at the intersection of risk-operation review, AI output quality calibration, human-in-the-loop evaluation, and practical agent workflows. My current work includes second-pass review of AI-related outputs, ambiguity resolution, and recurring error-pattern extraction. Outside work, I build public-safe systems that turn LLM or agent outputs into inspectable reports, metrics, and governance artifacts.

## Fast Review Path

| What to check | Link | What it proves |
|---|---|---|
| Main demo | <https://benben951.github.io/agent-trust-lab/> | A usable browser review console, not only a README idea. |
| Agent Trust Lab | <https://github.com/benben951/agent-trust-lab> | Risk-sensitive LLM/agent output review with reports, metrics, baseline, CI, and GitHub Pages. |
| Risk Review Copilot | <https://github.com/benben951/agent-trust-lab/blob/main/docs/RISK_REVIEW_COPILOT.md> | AML/KYC, sanctions, due diligence, payment-fraud, and compliance-QA framing. |
| Realistic agent cases | <https://github.com/benben951/agent-trust-lab/blob/main/docs/REALISTIC_CASES.md> | Public-safe cases adapted from real tool-using agent failure patterns. |
| Agent Workflow Bench | <https://github.com/benben951/agent-workflow-bench> | Planner-executor-reviewer-verifier evaluation with verifier artifacts. |
| LLM Proxy Auditor | <https://github.com/benben951/llm-proxy-auditor> | Trust checks for OpenAI-compatible proxies before agents depend on them. |
| Gemma AML Assistant | <https://github.com/benben951/gemma-aml-assistant> | Local-first AML/RAG evaluation and governance prototype. |

## Current Focus

- Evaluating LLM and agent outputs in risk-sensitive workflows.
- Turning reviewer judgment into reusable failure taxonomies and evidence checks.
- Building human-in-the-loop review systems for AML/KYC, compliance QA, due diligence, and agent reliability.
- Testing agent workflows under failure, timeout, missing evidence, and false-completion conditions.

## Selected Projects

### Agent Trust Lab

Risk-sensitive LLM output review and trust-report generation system.

- 52-case synthetic evaluation set across AML/KYC, sanctions, due diligence, trust and safety, health-safety, data quality, financial risk, and agent reliability.
- Generates Markdown and JSON trust reports with findings, risk score, trust level, and accept/escalate/reject routing.
- Includes naive-baseline comparison, case-family metrics, error taxonomy, realistic agent failure cases, CI, and a GitHub Pages demo.
- Adds a Risk Review Copilot slice for AML/KYC, sanctions, due diligence, payment-fraud, and compliance-QA interviews.

Repo: <https://github.com/benben951/agent-trust-lab>

### Agent Workflow Bench

Evaluation-first benchmark for planner-executor-reviewer-verifier workflows.

- Produces planner notes, candidate outputs, reviewer notes, verifier reports, JSON manifests, and Markdown summaries.
- Tracks evidence coverage, risk flags, pass/fail status, and human-takeover recommendations.
- Helps answer whether multi-agent workflows improve quality or only add cost and latency.

Repo: <https://github.com/benben951/agent-workflow-bench>

### LLM Proxy Auditor

Trust-audit tool for OpenAI-compatible LLM proxies before connecting them to coding agents, browser agents, or internal workflows.

- Checks prompt integrity, model substitution risk, response rewriting, strict JSON behavior, fake-secret leakage, and agent readiness.
- Produces Markdown/JSON trust reports with deterministic probes and CI-backed tests.

Repo: <https://github.com/benben951/llm-proxy-auditor>

### Gemma AML Compliance Assistant

Offline RAG and evaluation prototype for AML and due-diligence workflows.

- Uses local inference, retrieval grounding, citation-aware responses, and public-safe AML-style evaluation cases.
- Emphasizes grounding, uncertainty handling, escalation behavior, and regulated-domain governance boundaries.

Repo: <https://github.com/benben951/gemma-aml-assistant>

### Industrial ML / Competition Evidence

- TAAC / KDD Cup 2026 Industrial CVR case study: public-safe industrial recommendation workflow and experiment governance.
- ROGII Wellbore Geology Prediction: active Kaggle medal sprint, kept separate from GitHub because data and submissions should not be committed.
- NVIDIA / Kaggle Nemotron reasoning challenge: reasoning-evaluation lab and reproducibility notes.

Public repo: <https://github.com/benben951/taac-kddcup-2026-industrial-cvr>

## Open Source Contributions

- Merged regression-test contribution to `recommenders-team/recommenders`: <https://github.com/recommenders-team/recommenders/pull/2319>
- Merged Windows installer contribution to `HKUDS/OpenHarness`: <https://github.com/HKUDS/OpenHarness/pull/118>

## Stack

Python, SQL, Pandas, NumPy, scikit-learn, LightGBM, XGBoost, PyTorch, RAG, Streamlit, FastAPI, Docker, GitHub Actions, Codex, Claude Code, LLM evaluation, trust reports, review workflows, and agent orchestration.

## Looking For

LLM evaluation, AI data quality, AI application engineering, agent workflow systems, GenAI solution engineering, Trust & Safety AI, risk-tech AI, and compliance AI.
