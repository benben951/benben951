# Guo Zhaojie

AI application and evaluation engineer focused on Codex-first workflows, regulated knowledge systems, and reproducible ML experiments.

I build LLM application systems that need to be useful, auditable, and safe enough for real work: Codex-centered automation, RAG and evaluation pipelines, competition-backed experimentation, and risk or compliance tooling.

## Focus

- Agent systems: tool use, workflow routing, human-in-the-loop controls, and multi-agent execution
- Model evaluation: eval sets, bad-case review, prompt and version comparison, and regression discipline
- Regulated AI workflows: AML, due diligence, risk evidence retrieval, and trust or safety checks
- Reproducible ML: leaderboard discipline, ablation tracking, and experiment packaging

## Selected Projects

### TAAC / KDD Cup 2026 Industrial CVR Case Study

Public-safe case study of an industrial recommendation system built under single-model, latency, and hidden-transfer constraints.

- Tracks a unified-token recommendation backbone, pairwise ranking, dense-only EMA, and ablation evidence.
- Documents the jump from public LB AUC `0.843964` to `0.846275` with controlled iteration rather than leaderboard tricks.
- Positions competition work as a recruiter-readable industrial ML project, not just a score screenshot.

Repo: <https://github.com/benben951/taac-2026-industrial-portfolio>

### Gemma AML Compliance Assistant

Offline RAG and evaluation project for AML and due diligence knowledge workflows.

- Combines local LLM inference, retrieval grounding, citation-aware responses, and confidence or explainability layers.
- Includes evaluation notes, due-diligence demo artifacts, and a roadmap for regulated AI use cases.
- Designed as a privacy-preserving prototype for finance, compliance, and trust-sensitive environments.

Repo: <https://github.com/benben951/gemma-aml-assistant>

### LLM Proxy Auditor

Trust-audit tool for OpenAI-compatible proxies before they are connected to coding agents, browser agents, or internal workflows.

- Checks prompt integrity, model-substitution risk, structured-output stability, and agent readiness.
- Frames AI safety as an operator problem, not only a policy discussion.
- Includes deterministic probes, scoring, and report generation.

Repo: <https://github.com/benben951/llm-proxy-auditor>

### Hermes Control Plane

Supporting systems project for mobile-first control of coding workflows through Feishu.

- Routes tasks across planner, executor, reviewer, and smoke-test modes.
- Demonstrates orchestration and control-plane thinking even though my day-to-day usage is more directly Codex-centered.

Repo: <https://github.com/benben951/hermes-control-plane>

### Open Source Contribution

Merged regression-test contribution to `recommenders-team/recommenders`.

- Added threshold-based ranking-metrics regression coverage for `precision_at_k`, `ndcg_at_k`, and `map_at_k`.
- Demonstrates external collaboration and accepted contribution quality, not only solo portfolio work.

PR: <https://github.com/recommenders-team/recommenders/pull/2319>

## Selected Experiments

- `kaggle-nemotron-reasoning`: reasoning-evaluation lab for task-family analysis, deterministic baselines, adapter attempts, and failed-run evidence.

## Stack

Python, SQL, Pandas, NumPy, scikit-learn, LightGBM, XGBoost, PyTorch, RAG, vector databases, Streamlit, FastAPI, Docker, GitHub Actions, LLM APIs, evaluation workflows, and agent orchestration.

## Looking For

Roles in AI application engineering, LLM evaluation, agent workflow systems, GenAI solution engineering, or risk-tech tooling for AML, KYC, due diligence, trust and safety, and enterprise automation.
