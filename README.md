# Guo Zhaojie

LLM evaluation and AI automation practitioner focused on financial risk, AML due diligence, and agentic workflows.

I work on the practical side of large model applications: prompt evaluation, annotation quality review, multi-agent due diligence workflows, retrieval-augmented compliance assistants, and reproducible experiment tracking. My current direction is to build from LLM applications into evaluation-driven data flywheels and, later, domain-specific post-training.

## Focus

- LLM application engineering: RAG, tool use, agent orchestration, workflow automation
- Model evaluation: eval sets, bad-case analysis, prompt/version comparison, quality rubrics
- Financial risk and AML: due diligence, compliance knowledge retrieval, risk evidence tracing
- Reproducible ML experiments: recommendation systems, reasoning tasks, leaderboard discipline

## Featured Work

### Hermes Control Plane

Mobile-first orchestration layer for Codex CLI and Claude Code through a Feishu bot.

- Routes messages into chat, task, review, and verification workflows.
- Coordinates multiple coding agents with explicit pipeline modes.
- Designed for WSL2, local development, and long-running project control from mobile.
- Includes architecture docs, examples, config templates, and tests.

Repo: https://github.com/benben951/hermes-control-plane

### Gemma AML Compliance Assistant

Offline RAG assistant for AML and due diligence knowledge analysis.

- Combines local LLM inference, Qdrant retrieval, citation formatting, and confidence scoring.
- Uses AML/DD evaluation cases to check answer quality, source grounding, and hallucination risk.
- Built as a privacy-preserving prototype for regulated financial workflows.

Repo: https://github.com/benben951/gemma-aml-assistant

### Kaggle Nemotron Reasoning Lab

Reproducible workspace for the NVIDIA/Kaggle Nemotron reasoning challenge.

- Tracks task-family analysis, deterministic solver baselines, LoRA/distillation attempts, and failed runs.
- Treats competition work as an evaluation and post-training data pipeline, not only a submission file.

Repo: https://github.com/benben951/kaggle-nemotron-reasoning

### Open Source Contribution

Submitted a regression-test PR to `recommenders-team/recommenders` for ranking metrics with threshold-based relevancy.

- Covered edge cases for `precision_at_k`, `ndcg_at_k`, and `map_at_k`.
- Targeted tests passed locally.

PR: https://github.com/recommenders-team/recommenders/pull/2319

## Technical Stack

Python, SQL, Pandas, NumPy, scikit-learn, LightGBM, XGBoost, PyTorch basics, RAG, vector databases, Streamlit, FastAPI, GitHub Actions, Docker, LLM APIs, prompt evaluation, and agent workflows.

## Career Direction

Near term: AI application engineer, LLM evaluation engineer, GenAI solution engineer, or risk data analyst roles in financial risk, AML, KYC, due diligence, trust and safety, or enterprise AI automation.

Long term: move from LLM applications into model evaluation, post-training data pipelines, and domain-specific alignment for regulated workflows.
