# Guo Zhaojie

AI application and evaluation engineer focused on risk-sensitive LLM review, Codex-first workflows, AI output evaluation, regulated knowledge systems, and reproducible ML experimentation.

I work at the intersection of quality review, evaluation systems, agent workflows, and practical AI applications. My current work includes second-pass review of AI-related outputs, ambiguity resolution, and recurring error-pattern extraction. Outside work, I build public systems around LLM trust reports, industrial ML experiments, regulated AI workflows, proxy trust checks, and agent benchmarking.

## What I Do

- Review AI or annotation outputs, resolve ambiguous cases, and improve consistency across repeated judgments
- Turn recurring failure patterns into reusable review criteria and lightweight feature taxonomies
- Build risk-sensitive LLM review tools, Codex-centered workflows, evaluation pipelines, and public-safe AI case studies
- Explore how agent systems behave under success, failure, and timeout conditions instead of only demo-style wins

## Selected Projects

### Agent Trust Lab

Risk-sensitive LLM output evaluation system with a live review console, synthetic eval set, batch trust-report generation, evaluation metrics, and human-review routing.

- Built a 10-case synthetic eval library across AML, KYC, due diligence, trust and safety, customer support compliance, agent output review, and AI data quality
- Generates Markdown trust reports, JSON summaries, and reproducible evaluation metrics with risk score, trust level, findings, escalation recommendation, and finding distributions
- Demo metrics: 80% manual-review routing, 40% low-trust cases, average risk score 53.0, and top findings around policy mismatch, missing escalation, unsafe certainty, and unsupported claims
- Includes CI, GitHub Pages demo, public safety boundary, technical report, and patent-aware release checklist

Demo: <https://benben951.github.io/agent-trust-lab/>

Repo: <https://github.com/benben951/agent-trust-lab>

### TAAC / KDD Cup 2026 Industrial CVR Case Study

Public-safe industrial ML case study built under single-model, latency, and hidden-transfer constraints.

- Improved public LB AUC from `0.843964` to `0.846275`
- Ran 60+ controlled experiments around pairwise ranking, dense-only EMA, and noisy-label transfer
- Framed competition work as a recruiter-readable industrial recommendation project

Repo: <https://github.com/benben951/taac-2026-industrial-portfolio>

### Gemma AML Compliance Assistant

Offline RAG and evaluation prototype for AML and due diligence workflows.

- local LLM inference, retrieval grounding, citation-aware responses
- emphasis on grounding, uncertainty handling, and regulated-AI use cases

Repo: <https://github.com/benben951/gemma-aml-assistant>

### LLM Proxy Auditor

Trust-audit tool for OpenAI-compatible LLM proxies before connecting them to coding agents, browser agents, or internal workflows.

- checks prompt integrity, model substitution risk, structured-output stability, and agent readiness
- includes deterministic probes, CI, and trust-report artifacts

Repo: <https://github.com/benben951/llm-proxy-auditor>

### Agent Workflow Bench

Evaluation-first benchmark for planner-executor-reviewer-verifier workflows with reproducible simulated runs and live Codex-backed run history.

- Provides a model-free simulated pipeline that generates planner note, candidate output, reviewer note, verifier report, and JSON manifest
- Records success, failure, timeout, latency, pass-rate, verifier status, and failure taxonomy across workflow variants
- Includes CI, task specs, workflow specs, rubric judge, and public-safe sample artifacts

Repo: <https://github.com/benben951/agent-workflow-bench>

## Open Source Contributions

- Merged regression-test contribution to `recommenders-team/recommenders`:
  <https://github.com/recommenders-team/recommenders/pull/2319>
- Merged Windows installer contribution to `HKUDS/OpenHarness`:
  <https://github.com/HKUDS/OpenHarness/pull/118>

## Stack

Python, SQL, Pandas, NumPy, scikit-learn, LightGBM, XGBoost, PyTorch, RAG, Streamlit, FastAPI, Docker, GitHub Actions, Codex, Claude Code, evaluation workflows, and agent orchestration.

## Looking For

Roles in AI application engineering, LLM evaluation, agent workflow systems, GenAI solution engineering, and risk-tech or trust-and-safety AI.
