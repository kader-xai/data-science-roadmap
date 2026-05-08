---
layout: page
title: "Data Science Roadmap — From print('hello') to Production LLMs"
date: 2026-05-07
permalink: /article/
---

# From `print('hello')` to Production LLMs

*A 31-module open-source data-science course you can finish in a weekend or stretch over a month.*

---

## Why I built this

Most "learn data science" courses do one of two things badly:

- They lock the good stuff behind a subscription and split it across three separate courses (and never talk to each other).
- Or they jump from `print("hello world")` straight to a Kaggle notebook, with no in-between.

This repo is the in-between. **31 deep-dive notebooks**, every one runnable in Google Colab in one click, every one paired with a colour-coded explanation document. From your first variable to reading the inference code of a 671-billion-parameter LLM.

## Who it's for

- **Beginners** who want a structured path that doesn't skip steps.
- **Self-taught coders** who can write Python but want to fill the gaps in Pandas, NumPy, scikit-learn — and beyond.
- **Career-switchers** building a portfolio. The capstone notebook (Module 16) and the production modules (M29-M31) are portfolio-ready as-is.

## What's inside — six parts

### Part 1 · Python for Data Science (Modules 1–5)
Variables, data structures, OOP, file I/O, NumPy, Pandas, APIs, web scraping. The alphabet of every later module.

### Part 2 · Data Visualization (Modules 6–10)
Matplotlib's object-oriented API; the seven core chart types; specialised tools (waffle, word cloud, Folium maps); animation and Plotly; building dashboards that tell one cohesive story.

### Part 3 · Data Analysis & ML Foundations (Modules 11–16)
The universal workflow: import → wrangle → explore → model → evaluate → communicate. Built around a shared dataset (auto-mpg) so each step builds on the last, then validated end-to-end on California Housing.

### Part 4 · Machine Learning & AI (Modules 17–22)
PyTorch fundamentals; the six core model archetypes (Linear, Logistic, K-Means, MLP, CNN, Transformer LM); self-attention from scratch with `d_model = 2` so every matrix is hand-checkable; multi-head + causal attention; diffusion models on a 2D toy; time-series forecasting with ARIMA, Prophet, and LSTM.

### Part 5 · AI-Research Foundations (Modules 23–25)
The math under every neural network (functions, derivatives, gradients, matrices, probability) plus a deep PyTorch primer. A guided tour of **DeepSeek-V3's actual inference code** (RMSNorm, RoPE, Multi-Latent Attention, Mixture-of-Experts). Fine-tuning examples — full fine-tuning, **LoRA**, **QLoRA**, and SFT with TRL.

### Part 6 · Practitioner Skills (Modules 26–31)
The day-to-day skills a working data scientist or ML engineer uses but most courses skip:

- **SQL** — JOINs, CTEs, window functions, the SQL ↔ Pandas bridge
- **Tree-based models** — Random Forest, **XGBoost**, **LightGBM**, **SHAP** for interpretation
- **A/B testing** — proportion z-test, sample-size calc, Bonferroni / BH correction, the peeking trap
- **MLOps** — FastAPI, Docker, **MLflow**, drift monitoring with KS + PSI
- **RAG & vector search** — embeddings, Chroma, hybrid BM25 + vector, reranker, grounded answers
- **Prompt engineering & LLM eval** — few-shot, chain-of-thought, ReAct, structured outputs, LLM-as-judge

## What makes it different

| | This course | Typical course |
|---|---|---|
| Production architecture depth | DeepSeek-V3 dissection | "Transformers exist" |
| Math integrated with code | Yes (Module 23) | usually skipped |
| Practical skills (SQL, A/B, MLOps) | Modules 26-29 | rarely covered |
| Companion docs | Line-by-line, colour-coded, ~30 pages each | None |
| Cost | Free, MIT-licensed | $40-300/month |

## How to use it

**Option A — Colab.** Click any badge in the README, hit `Save a copy in Drive`, run the cells. Zero install.

**Option B — Locally.**

```bash
git clone https://github.com/kader-xai/data-science-roadmap.git
cd data-science-roadmap
pip install jupyter numpy pandas scikit-learn torch transformers
jupyter notebook
```

## What you walk away with

After the 31 modules you can:

- Write any Python program and load data from any source.
- Build classical ML models (regression, gradient boosting) AND modern AI models (transformers, diffusion).
- Read production LLM source code (DeepSeek, Llama, Mistral, Qwen).
- Fine-tune any open-weight model on your own data with LoRA.
- Ship a model behind FastAPI + Docker with MLflow tracking.
- Build a working RAG pipeline with vector search.
- A/B-test prompts and evaluate LLMs scientifically.

That's effectively a 2026 ML-engineer career, built from `print('hello')`.

---

**Repo:** [github.com/kader-xai/data-science-roadmap](https://github.com/kader-xai/data-science-roadmap)
**Live site:** [kader-xai.github.io/data-science-roadmap](https://kader-xai.github.io/data-science-roadmap/)
**License:** MIT
