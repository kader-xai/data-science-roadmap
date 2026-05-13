# Data Science Roadmap

> A self-paced, code-first course covering the full path from `print("hello")` to production LLM fine-tuning + the practical engineering skills (SQL, MLOps, RAG, A/B testing) that complete a 2026 data-science career. **31 deep-dive notebooks** across six parts. Every notebook is one click away in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_01_python_basics.ipynb) ← start with **Module 1**

🌐 **Live site:** <https://kader-xai.github.io/data-science-roadmap/>
📦 **License:** [MIT](LICENSE)

---

## Who it's for

- **Beginners** who want a structured path from "what is a variable" to a working ML model — without paying for a Coursera certificate.
- **Self-taught coders** who can write Python but want to fill the gaps in Pandas, NumPy, and scikit-learn.
- **Career-switchers** building a portfolio. The capstone notebook (M16) is portfolio-ready as-is.

## What you'll be able to do at the end

- Load any CSV / Excel / JSON / SQL / API / scraped HTML into Pandas.
- Clean it — missing values, type fixes, scaling, encoding, binning, outliers.
- Explore it — distributions, correlations, group-bys, pivot tables.
- Visualise it — pick the right chart for the question; build dashboards.
- Model it — linear, multiple, polynomial regression with proper train/test split, cross-validation, and regularisation (Ridge / Lasso).
- **Communicate it** — the part most courses skip. Module 10 + Module 16 train you to write the one-page memo a stakeholder actually reads.

After **Part 4 (M17-22)** you'll additionally be able to:
- Train neural networks (MLP, CNN) in PyTorch from a fresh notebook.
- Use Hugging Face to run any pretrained model in 3 lines.
- Read a transformer paper and recognise every term in it — because you implemented multi-head causal attention by hand.
- Build and sample from a diffusion model — the technology behind Stable Diffusion / DALL-E.
- Forecast time-series with ARIMA, Prophet, and LSTM, and validate them honestly with walk-forward splits.

---

## Course structure

| Part | Track | Modules |
|---|---|---|
| 1 | **Python for Data Science** | 1 → 5 |
| 2 | **Data Visualization** | 6 → 10 |
| 3 | **Data Analysis & ML Foundations** | 11 → 16 |
| 4 | **Machine Learning & AI** *(deeper dive)* | 17 → 22 |
| 5 | **AI-Research Foundations** *(math + production internals + fine-tuning)* | 23 → 25 |
| 6 | **Practitioner Skills** *(SQL, gradient boosting, A/B, MLOps, RAG, prompts)* | 26 → 31 |
| 7 | **Production AI Stack** *(LLM frameworks, infra, languages — building)* | 32 → 54 |

### Part 1 — Python for Data Science

| # | Module | Open in Colab |
|---|---|---|
| 01 | **Python Basics** — variables, types, strings, format strings, debugging | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_01_python_basics.ipynb) |
| 02 | **Data Structures** — lists, tuples, dicts, sets, comprehensions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_02_data_structures.ipynb) |
| 03 | **Programming Fundamentals** — conditionals, loops, functions, exceptions, OOP, mini text-analyser | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_03_programming_fundamentals.ipynb) |
| 04 | **Working with Data** — files, CSV/JSON, NumPy arrays, Pandas DataFrames | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_04_working_with_data.ipynb) |
| 05 | **APIs, Web Scraping, Stock Data** — `requests`, BeautifulSoup, `pd.read_html`, `yfinance` (TSLA vs GME) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_05_apis_and_scraping.ipynb) |

### Part 2 — Data Visualization

| # | Module | Open in Colab |
|---|---|---|
| 06 | **Intro to Visualization** — Matplotlib OO API, line plots, styling | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_06_intro_visualization.ipynb) |
| 07 | **Basic Charts** — bar, hist, pie, box, scatter, bubble, area | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_07_basic_visualization.ipynb) |
| 08 | **Specialized Viz** — waffle, word cloud, regression plot, Folium, choropleth | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_08_specialized_visualization.ipynb) |
| 09 | **Advanced Viz** — subplots, time-series patterns, animation, Plotly | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_09_advanced_visualization.ipynb) |
| 10 | **Dashboards & Storytelling** — composing multiple charts to answer one question | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_10_dashboards.ipynb) |

### Part 3 — Data Analysis & Machine Learning

| # | Module | Open in Colab |
|---|---|---|
| 11 | **Importing Data Sets** — CSV, Excel, JSON, SQL, web; the 5-line inspection ritual | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_11_importing_data.ipynb) |
| 12 | **Data Wrangling** — missing values, scaling, binning, one-hot encoding, outliers | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_12_data_wrangling.ipynb) |
| 13 | **Exploratory Data Analysis** — distributions, correlations, group-bys, pivot tables | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_13_eda.ipynb) |
| 14 | **Model Development** — linear / multiple / polynomial regression with Pipelines | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_14_model_development.ipynb) |
| 15 | **Model Evaluation** — MSE/RMSE/MAE/R², over-/under-fitting, CV, Ridge & Lasso, GridSearch | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_15_model_evaluation.ipynb) |
| 16 | **Capstone** — California Housing end-to-end, R² ≈ 0.80 with Random Forest | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_16_capstone.ipynb) |

---

## Practice & Workbooks

| Workbook | What it's for | Open in Colab |
|---|---|---|
| **All Exercises (with Answer Key)** — every practice problem from M1–M16 in one notebook; solutions in an appendix at the end | self-test after each module | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/all_modules_exercises.ipynb) |
| **Output-First Workbook** — the *expected output* is shown, you write the code; reference answer is collapsed behind a `👀 Show answer` toggle | active recall practice | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/output_first_workbook.ipynb) |
| **Combined Roadmap** — single-notebook tour of every topic; useful as a refresher/reference | revisiting after the course | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/data_science_roadmap.ipynb) |
| **ML Track Exercises (M17-22)** — output-first practice for the ML & AI track; answers behind a `👀 Show answer` toggle | self-test after Modules 17-22 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/ml_track_exercises.ipynb) |

---

### Part 4 — Machine Learning & AI *(deeper dive)*

Picks up after the capstone (M16) and goes into the ML and AI machinery itself. **Assumes you're comfortable with everything in M1–M16** — Python, Pandas, scikit-learn, regression, evaluation. These three modules bridge from "fit a regression" to "build a transformer."

| # | Module | Open in Colab |
|---|---|---|
| 17 | **Python for ML & AI — Practice** — 12 sub-modules: Python language essentials, data structures, comprehensions, decorators, OOP, NumPy, Pandas, viz, scikit-learn, **PyTorch**, **Hugging Face**, the ML engineer's toolkit | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_17_python_for_ml_ai.ipynb) |
| 18 | **Six Core Models End-to-End** — one notebook, six full pipelines: **Linear Regression** (California housing) → **Logistic Regression** (cancer) → **K-Means** (customer segments) → **MLP** & **CNN** (Fashion-MNIST) → **Transformer LM** (from scratch). ~10 min on free Colab CPU. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_18_six_core_models.ipynb) |
| 19 | **Self-Attention From Scratch** — the transformer's core mechanism built step-by-step in PyTorch with `d_model = 2` so every Q/K/V matrix is hand-checkable. Then connects to multi-head causal attention. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_19_self_attention.ipynb) |
| 20 | **Multi-Head + Causal Attention** — multi-head split, causal masking, the full transformer block (LayerNorm + MHA + FFN + residual), stacked into a `TinyTransformer` you can train. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_20_multihead_causal_attention.ipynb) |
| 21 | **Diffusion Models From Scratch** — destroy → undo. The math behind Stable Diffusion built on a 2D toy dataset (two moons) so you can watch every step. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_21_diffusion_models.ipynb) |
| 22 | **Time-Series Forecasting** — when rows have an order. ARIMA, Prophet, LSTM, walk-forward validation. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_22_time_series_forecasting.ipynb) |

### Part 5 — AI-Research Foundations *(math + production internals)*

The math under every neural net, plus a guided tour of a real frontier-LLM codebase. Modules 23 and 24 stand alone — read them whenever you need the foundations, before or after Part 4.

| # | Module | Open in Colab |
|---|---|---|
| 23 | **Math & PyTorch Foundations for AI Research** — functions, derivatives, vectors, gradients, matrices, probability + a deeper PyTorch tensor primer (matmul flavours, transpose vs permute, view vs reshape, cat vs stack). The math you wish you'd reviewed before tackling M19-M22. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_23_math_and_pytorch_foundations.ipynb) |
| 24 | **New Transformer Programming** *(DeepSeek-V3 inference internals)* — read the actual code that runs the 671 B-parameter open-weight LLM. RMSNorm, RoPE, **Multi-Latent Attention** (the cache-shrinking trick), **Mixture of Experts** with top-K routing, FP8 inference, the autoregressive loop. Every concept simplified to run on Colab CPU. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_24_new_transformer_programming.ipynb) |
| 25 | **Fine-Tuning Examples** — full vs **LoRA** vs **QLoRA** vs **SFT with TRL**. End-to-end runnable: train a `distilgpt2` on a custom marketing-style corpus, swap to a 0.2%-trainable LoRA adapter, save & re-load it, then run instruction-tuning with `SFTTrainer`. Plus the recipes for DPO, RLHF, and ORPO. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_25_fine_tuning_examples.ipynb) |

### Part 6 — Practitioner Skills *(the production / business side)*

The day-to-day skills a working data scientist or ML engineer uses but most courses skip. SQL is the single biggest gap, RAG is the #1 LLM use case in production, MLOps is what gets a model from notebook to revenue.

| # | Module | Open in Colab |
|---|---|---|
| 26 | **SQL for Data Science** — SELECT/WHERE, JOINs, **CTEs**, **window functions**, date funcs, CASE, SQL ↔ Pandas. The single biggest gap in most ML courses; ~40% of a working DS's day. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_26_sql_for_data_science.ipynb) |
| 27 | **Tree-Based Models & Gradient Boosting** — Decision Tree → Random Forest → GradientBoosting → **XGBoost** / **LightGBM**. Plus the full classification-metrics suite (P/R/F1/ROC-AUC/PR-AUC), threshold tuning, imbalanced-class handling, and **SHAP** for per-prediction explanations. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_27_tree_based_models.ipynb) |
| 28 | **A/B Testing & Inferential Statistics** — proportion z-test, Welch's t-test, confidence intervals, **sample-size & power calc**, Bonferroni / BH correction, the **peeking trap** (with simulation), SRM detection, end-to-end test design. The universal product-DS interview topic. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_28_ab_testing.ipynb) |
| 29 | **MLOps: FastAPI · Docker · MLflow · Monitoring** — train → persist → serve via FastAPI (with TestClient demo) → containerise with a real Dockerfile → track experiments + register the winner with MLflow → detect drift with **KS test + PSI** → read a CI/CD pipeline. Notebook → revenue. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_29_mlops.ipynb) |
| 30 | **RAG & Vector Search** — full 5-stage pipeline: embed with `sentence-transformers` → store in **Chroma** → retrieve top-k → optionally **rerank** with a cross-encoder → stuff into a flan-t5 prompt for grounded answers + sources. Includes recall@k / MRR eval, **hybrid (BM25 + vector)** search, chunking strategies. The #1 production LLM use case in 2026. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_30_rag_and_vector_search.ipynb) |
| 31 | **Prompt Engineering & LLM Evaluation** — zero-shot / few-shot / role prompting · **chain-of-thought** · **ReAct** with toy tools · structured outputs (Pydantic + JSON mode) · **self-consistency** sampling · **LLM-as-judge** · **Ragas-style** RAG metrics (faithfulness, relevance) · end-to-end prompt-comparison eval harness. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_31_prompt_engineering_and_llm_eval.ipynb) |

### Part 7 — Production AI Stack *(LLM frameworks, infra, languages)*

Building. The frameworks, runtimes, and languages a 2026 ML/AI engineer reaches for at work. Modules 32–54 in progress.

| # | Module | Open in Colab |
|---|---|---|
| 32 | **LangChain Essentials** — the LCEL pipe `\|` syntax · `PromptTemplate` & `ChatPromptTemplate` · output parsers (Pydantic, list, JSON) · 5-line RAG chain (vs M30's 50 lines) · memory with `RunnableWithMessageHistory` · `@tool` + ReAct agent · `langchain.debug` and LangSmith tracing. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_32_langchain_essentials.ipynb) |
| 33 | **LangGraph: Stateful Agents** — when chain → done isn't enough. State / Nodes / Edges · `add_conditional_edges` for branching · ReAct as a state graph with a visible loop · `MemorySaver` checkpointer for pause/resume/time-travel · `.stream()` for live event streaming · multi-agent orchestrator + workers · Mermaid graph rendering. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_33_langgraph_stateful_agents.ipynb) |
| 34 | **LlamaIndex for Production RAG** — the RAG-first framework. The 6 core abstractions (Document/Node/Index/Retriever/Postprocessor/QueryEngine) · build a query engine in 4 lines · `SentenceSplitter` vs **`SemanticSplitterNodeParser`** · cross-encoder rerankers as one-line postprocessors · **hierarchical / auto-merging retrieval** (small chunks, parent context) · persist/reload indices. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_34_llamaindex_production_rag.ipynb) |
| 35 | **DSPy: Programmatic Prompts** — declare WHAT, let the framework optimise HOW. **Signatures** as task contracts · `Predict` / `ChainOfThought` / `ReAct` modules · compose into PyTorch-style programs · **`BootstrapFewShot`** optimiser auto-tunes few-shot demos from a tiny labelled set · save/reload compiled programs · DSPy + RAG. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_35_dspy_programmatic_prompts.ipynb) |
| 36 | **PostgreSQL + pgvector** — your AI app's boring, reliable backbone. Install Postgres + pgvector inside Colab · **JSONB** for schemaless metadata · arrays & generated columns · **`tsvector` full-text search** with GIN indexes · the `vector` type and cosine `<=>` operator · **HNSW indexes** for sub-ms ANN at scale · **hybrid SQL filter + vector ranking** in one query · scaling notes (Neon, Supabase, pgvectorscale). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_36_postgresql_pgvector.ipynb) |
| 37 | **Redis for AI Backends** — the swiss-army knife of AI infra. **LLM response cache** with `SETEX` (biggest cost win you can ship today) · `HASH` for user sessions · `LIST` + `LTRIM` for sliding conversation history · **sorted-set sliding-window rate limiting** · **Streams + consumer groups** for durable async job queues · **Pub/Sub** for live token streaming to browsers · **RediSearch + `VECTOR` field** for sub-ms ANN inside Redis · production notes on persistence, eviction, cluster. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_37_redis_for_ai.ipynb) |
| 38 | **Ollama + llama.cpp** — run real LLMs locally, even without a GPU. The local stack (Ollama → llama-server → llama.cpp → GGUF) · **quantisation** (`Q4_K_M` default, why mixed-bit beats uniform) · install Ollama in Colab + pull a model · OpenAI-SDK-compatible calls (`base_url=…/v1`) · streaming + grammar-constrained **JSON mode** · build llama.cpp from source · `llama-server` with `-ngl` GPU offload · **embeddings** via `--embeddings` · model-picking guide (size · instruct · context · license) · production notes (Modelfile, KV cache, continuous batching, speculative decoding). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_38_ollama_llamacpp.ipynb) |
| 39 | **Unsloth Fine-Tuning** — teach the model your tone/domain on a free Colab GPU. Full-FT vs **LoRA** vs **QLoRA** demystified · why Unsloth is 2× faster + 60% lighter VRAM (Triton kernels + manual autograd) · `FastLanguageModel.from_pretrained` 4-bit · `get_peft_model` with rank/alpha/target_modules · format with the model's **chat template** · `SFTTrainer` (TRL) on a tiny synthetic support-agent dataset · inference with the trained adapter · `save_pretrained_gguf` → merged Q4_K_M GGUF you can `ollama run` · fine-tune vs RAG vs prompt decision table. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_39_unsloth_finetuning.ipynb) |
| 40 | **TensorFlow & Keras** — the other half of the deep-learning ecosystem. TF vs PyTorch decision table · tensors, eager mode, **`@tf.function`** graph compilation · **`tf.data`** pipelines with `prefetch(AUTOTUNE)` · all three Keras APIs (**Sequential**, **Functional** with branching, **Subclassing** PyTorch-style) · MNIST end-to-end · production callbacks (EarlyStopping, ModelCheckpoint, ReduceLROnPlateau, TensorBoard) · `.keras` + **SavedModel** formats · **TF Lite** convert + int8 quantise + interpreter · **TF Serving** docker one-liner with versioning + batching. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_40_tensorflow_keras.ipynb) |
| 41 | **CUDA Basics** — GPU kernels from Python. Why GPUs are fast (parallelism not clock) · the execution model (**thread → warp → block → grid → SM**) · the memory hierarchy (registers · **shared** · L1/L2 · global HBM) · first kernel — vector add with `@cuda.jit` · 2-D indexing for image kernels · **shared-memory tiled matmul** (the FlashAttention pattern in miniature) · **CuPy** for NumPy-on-GPU one-liners · CUDA events + `nvidia-smi` profiling · bridge to PyTorch + a peek at **Triton** · when to write CUDA vs let the framework handle it. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_41_cuda_basics.ipynb) |
| 42 | **Vector DB Comparison** — the whole landscape, not just one pick. Six categories (in-process · embedded · self-hosted · managed · Postgres ext · cache) with a one-line decision tree · ANN algorithms in 2 minutes (**flat / IVF / HNSW / PQ**, recall vs cost) · live demos: **FAISS** flat + HNSW · **Chroma** with metadata `where` · **Qdrant** with payload filters inside the ANN walk · API shapes for **Weaviate** hybrid + **Pinecone / Vespa / Milvus** · same-corpus latency micro-benchmark · why **filters + hybrid retrieval** is the real differentiator (not raw recall) · decision table + anti-patterns. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_42_vector_db_comparison.ipynb) |
| 43 | **crewAI & AutoGen** — multi-agent orchestration. When multi-agent helps vs when it just adds tokens · two mental models: **crewAI** (declarative roles + tasks) vs **AutoGen** (programmable conversations + GroupChatManager) · point both at local **Ollama** (free) or OpenAI · same Researcher → Writer → Critic pipeline in both · tool use via `@tool` (crewAI) and `register_function` (AutoGen) · **sequential** vs **hierarchical (Manager + Workers)** patterns · failure-mode table (loops, runaway cost, hallucinated handoffs) · decision table: crewAI vs AutoGen vs **LangGraph** (M33). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_43_crewai_autogen.ipynb) |
| 44 | **vLLM** — high-throughput LLM inference for production. **PagedAttention** (KV memory as OS-style pages, 3-5× more concurrent requests) + **continuous batching** (swap finished requests out, new ones in every step, ~10× throughput) explained in plain English · throughput vs latency knobs (TTFT · TPOT · `max_num_seqs` · `gpu_memory_utilization`) · offline `LLM(...).generate(prompts)` · `vllm.entrypoints.openai.api_server` OpenAI-compatible HTTP · **tensor parallelism** for 70B+ models · **prefix caching** + **speculative decoding** with a tiny draft model · vLLM vs **TGI** vs **SGLang** vs **TensorRT-LLM** vs **llama-server** decision table. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_44_vllm.ipynb) |
| 45 | **gRPC for AI Backends** — service-to-service plumbing. Why gRPC over REST (binary protobuf, HTTP/2, **enforced schema**, native streaming, 11-language SDKs from one `.proto`) · Protobuf in 5 minutes (messages, services, field numbers, `repeated`, `oneof`) · live: write `ai.proto` → run `grpc_tools.protoc` → implement Python server + client → unary RPC + **server-streaming token streams** · the four call shapes (unary / server / client / bidi) · production basics — **deadlines**, error codes, **interceptors**, mTLS, reflection · gRPC vs REST vs WebSocket vs message queue decision table · "REST/SSE at the edge, gRPC inside" pattern. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_45_grpc.ipynb) |
| 46 | **Kubernetes for ML** — running AI services in production. The 5 core objects (Pod · Deployment · Service · Ingress · ConfigMap/Secret) · **GPU scheduling** with `nvidia.com/gpu`, taints + tolerations · `readinessProbe` for slow-loading LLMs · **PVC** with `ReadWriteMany` for shared model caches (EFS/Filestore) · **Job + CronJob** for training and nightly re-indexes · **HPA on custom Prometheus metrics** (vLLM RPS, KV-cache utilisation) — why CPU is the wrong signal for LLMs · KEDA for queue-driven scaling · ML-native stack (**KServe**, **KubeRay**, **Kubeflow**, NVIDIA GPU Operator, NIM) · day-2 ops (GitOps, Sealed Secrets, anti-patterns). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_46_kubernetes_for_ml.ipynb) |
| 47 | **Helm Charts for ML** — packaging Kubernetes YAML. Mental model (**Chart · Values · Release**) · anatomy of a chart (`Chart.yaml`, `values.yaml`, `templates/`, `_helpers.tpl`, `NOTES.txt`) · Go templating + sprig (`include`, `nindent`, `toYaml`, `with`, whitespace trimming with `{{- -}}`) · designing `values.yaml` as your chart's API (groupings, `enabled` toggles, escape hatches) · `helm create / template / lint / install / upgrade / rollback / uninstall` · **sub-chart dependencies** (your app + Redis + Postgres) · **lifecycle hooks** + `helm test` smoke tests · Helmfile vs **Argo CD GitOps** for managing 50 charts · the ML-native chart catalog (KServe · KubeRay · GPU Operator · kube-prometheus-stack · cert-manager · Argo CD itself). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_47_helm_charts_for_ml.ipynb) |
| 48 | **Terraform for ML Infrastructure** — the layer below Kubernetes. Why IaC + why Terraform/OpenTofu won; **Pulumi · CDK · Crossplane** vs Terraform · the 5 primitives (**provider · resource · data · variable · output**) · **state** as the central concept (remote S3 + DynamoDB lock, encrypt, never in Git) · **modules** + the public registry (`terraform-aws-modules/eks/aws`) · a real ML platform — VPC, EKS with **scaled-from-zero GPU node pools**, S3 buckets for models/datasets/checkpoints, IRSA so pods read S3 without long-lived keys · `init / fmt / validate / plan -out / apply / destroy` workflow · directory-per-env for dev/staging/prod · **Atlantis / Spacelift / Argo CD** for PR-driven applies · secrets (Secrets Manager + `data` lookups, never in `.tf`) · day-2 + anti-patterns. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_48_terraform_for_ml.ipynb) |
| 49 | **Ansible for ML Provisioning** — configuring the boxes Terraform creates. Where Ansible fits next to Terraform / Helm (Day-0 vs Day-1 vs Day-1+) · the mental model (**inventory · playbook · task · module · role · handler · vault**) · INI + YAML inventories with group-of-groups · tasks calling `ansible.builtin.apt` / `systemd` / `template` · **idempotency** as the killer property (`--check`, `--diff`, `creates:`) · variables, **`ansible_facts`**, jinja2 templates, the variable-precedence chain · **roles + Ansible Galaxy collections** (`nvidia.nvidia_driver`, `kubernetes.core`) · **handlers** for restart-on-change · the canonical ML play (blacklist nouveau → Docker → NVIDIA driver → nvidia-container-toolkit → `nvidia-smi` in container sanity-check) · production basics (**ansible-vault**, dynamic inventory, AWX/Semaphore, Mitogen) · anti-patterns. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_49_ansible_for_ml.ipynb) |
| 50 | **Prometheus + Grafana** — observability for ML platforms. The 3 pillars (metrics · logs · traces) · Prometheus's **pull model** with `/metrics` HTTP endpoints · the four metric types (**counter · gauge · histogram · summary**) — when to use which · live: instrument a Python service with `prometheus_client` (Counter / Histogram / Gauge with labels) · **PromQL essentials** — `rate()`, `sum by`, `histogram_quantile`, `offset 1w` for anomalies · build a complete LLM Grafana dashboard (RPS · error rate · p50/p95/p99 latency · KV-cache · GPU util · tokens/sec) · **Alertmanager** rules with `for:` flap-control + silences/inhibition · ML-native exporter catalog (**DCGM**, vLLM `/metrics`, Triton, KServe, kube-state-metrics) · **RED / USE / SLO burn-rate** alerting — page on user impact, not raw resource %. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_50_prometheus_grafana.ipynb) |
| 51 | **OpenTelemetry for LLMs** — the trace half of observability. Trace mental model (**span tree** + **context propagation** via `traceparent` headers) · OTel architecture (SDK → OTLP → **Collector** → backend) · live: manual spans with `tracer.start_as_current_span` + status + events · 120+ auto-instrumentations (`opentelemetry-instrument python app.py`) · the **GenAI semantic conventions** (`gen_ai.system`, `gen_ai.request.model`, `gen_ai.usage.input_tokens`, …) · **OpenLLMetry / Traceloop / Langfuse / Phoenix** — LLM observability ecosystem on top of OTel · **tail-based sampling** in the Collector (keep errors / slow / LLM traces, drop the rest) · OTLP fan-out to Jaeger / Tempo / Datadog / Langfuse · debugging a real RAG bug from a slow Qdrant search to a missing payload index. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_51_opentelemetry_for_llms.ipynb) |
| 52 | **Go for AI Backends** — the language of cloud-native ML (Kubernetes, Docker, Prometheus, Argo, Helm, Terraform, vLLM gateways are all Go). Why Go won; coming-from-Python differences (errors are **values**, no classes, strict types) · install Go in Colab + hello world · syntax fast-tour (structs, methods, slices, maps, the `if err != nil { return err }` pattern) · **goroutines + channels** with `sync.WaitGroup` · `net/http` server in 12 lines + `encoding/json` · **`context.Context`** for deadlines, cancellation, request scoping (the single most important Go idiom for backends) · build a real **LLM gateway that races two backends** with fan-out + first-response-wins · tooling (`go mod`, `go fmt`, `go vet`, `go test -race`, **`pprof`**) · Go vs Python vs Rust decision table. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_52_go_for_ai_backends.ipynb) |
| 53 | **Rust Crash Course** — the hot-path language for AI (HF **`tokenizers`**, **`safetensors`**, **`polars`**, **`qdrant`**, **`candle`**, `burn`, `mistral.rs`, `uv`, `ruff` — all Rust). Install rustup + cargo · the **ownership + borrowing** rules in 5 minutes (shared XOR mutable, the borrow checker, `&T` vs `&mut T`) · syntax fast-tour (structs, `impl`, enums, `Result<T, E>` + the **`?` operator**, exhaustive `match`) · zero-cost iterator chains + closures + **`rayon`** parallelism · **Cargo** with workspaces and lockfile · async HTTP server with **`tokio` + `axum`** · **PyO3 + maturin** to ship a Rust crate as a Python wheel (the tokenizers story) · the ML-Rust ecosystem map · Rust vs Go vs C++ decision table. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_53_rust_for_ai.ipynb) |
| 54 | **TypeScript for AI Frontends** — closing the loop. The whole course built the backend; users only see the frontend. TS in 5 minutes (interfaces, generics, narrowing, `unknown` vs `any`) · the AI-SDK landscape (**Vercel AI SDK** as default, OpenAI/Anthropic SDKs, LangChain.js) · `createOpenAI({ baseURL })` to point at your **vLLM (M44)** or **Ollama (M38)** · **streaming** with `streamText().toDataStreamResponse()` · React **`useChat`** for a 30-line streaming chat UI · **tool calling with Zod schemas** (one schema = runtime validator + TS type + JSON schema + prompt description) · **`streamObject`** for live structured outputs · edge runtimes (Vercel · Cloudflare Workers · Bun · Deno) · production checklist (auth, Upstash rate-limit, OTel telemetry, cost, never client-side keys, fallback providers, eval). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_54_typescript_for_ai_frontends.ipynb) |

### Part 8 — LLMs from Scratch *(Raschka deep-dive)*

The middle layer M19–M24 hinted at but never built: real tokenizers, real GPT-2 weights loaded into your own code, a pretraining loop, classification + instruction fine-tuning without TRL, plus KV-cache, GPT-2→Llama conversion, and DPO. Inspired by [`rasbt/LLMs-from-scratch`](https://github.com/rasbt/LLMs-from-scratch).

| # | Module | Open in Colab |
|---|---|---|
| 55 | **Tokenization + Text Pipeline from Scratch** — closes the gap between M19/M20 (random IDs) and a real corpus. Toy regex tokenizer → vocab → **`SimpleTokenizerV1` / `V2`** with special tokens (`<\|unk\|>`, `<\|endoftext\|>`) → **BPE via `tiktoken`** (50 257 vocab, no `<unk>`) · **`GPTDatasetV1`** sliding-window dataset with shift-by-one targets · **`create_dataloader_v1`** with `max_length` + `stride` · **token + positional embeddings** summed to the `(B, T, D)` tensor every block in this course has been waiting for. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_55_tokenization_text_pipeline.ipynb) |
| 56 | **Real GPT-2 124M Assembly + Loading Pretrained Weights** — your hand-coded transformer generates real GPT-2 text. `GPT_CONFIG_124M` (vocab 50 257 · ctx 1024 · d_model 768 · 12 heads · 12 layers · `qkv_bias=True`) · LayerNorm + tanh-GELU + FFN(4×) · MHA with separate Q/K/V projections · **pre-norm** transformer block · full `GPTModel` assembly · **weight tying** turns 163M → canonical **124M** · download OpenAI's TF checkpoint via Raschka's helper · `load_weights_into_gpt` — **split the fused `c_attn` (768→2304) into Q/K/V**, transpose every TF (in,out) matrix to PyTorch (out,in), re-tie `out_head.weight = tok_emb.weight` · `generate_text_simple` greedy decode · prompt the loaded model and watch your code produce real English. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_56_gpt2_assembly_load_weights.ipynb) |
| 57 | **Pretraining Loop from Scratch** — train your own GPT, end to end. The next-token cross-entropy objective · `calc_loss_batch` / `calc_loss_loader` flattening `(B,T,V)` and `(B,T)` for `F.cross_entropy` · **`train_model_simple`** the full PyTorch loop (AdamW, `optimizer.zero_grad → backward → step`) · periodic eval + **periodic generation** so you can *see* the model learn · **perplexity = exp(loss)** as the canonical LM metric · **temperature scaling** (T<1 sharpens, T→∞ flattens) · **top-k sampling** with `-inf` masking · production-shape **`generate()` = temperature + top-k + `torch.multinomial`** · checkpointing both **model + optimiser state-dicts** for clean resume · what real pretraining adds (warmup, cosine LR, grad-clip, AMP, gradient accumulation, DDP — covered in M66). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_57_pretraining_loop_from_scratch.ipynb) |
| 58 | **Classification Fine-Tune (Spam on GPT-2)** — the *other* flavour of fine-tune. Classification vs instruction comparison table · UCI SMS-Spam + **balanced undersampling** · `SpamDataset` with fixed-length padding to GPT-2's EOT (50256) · **swap the LM head for `Linear(emb_dim, 2)`** · **selective freezing** — freeze everything, then unfreeze final LN + last block + new head (≈ LoRA-without-LoRA) · the **last-token-logits** trick `model(x)[:, -1, :]` (and *why* — only the last token has seen the whole message under a causal mask) · loss + accuracy helpers · train + plot · `classify_review` production inference · when to pick a fine-tuned classifier vs an LLM tool call. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_58_classification_finetune.ipynb) |
| 59 | **Instruction-Tuning Internals (no TRL)** — re-implement `SFTTrainer` by hand so nothing is magic. **Alpaca prompt format** with optional `### Input:` · `InstructionDataset` (no padding/labels — those decisions belong in the collate) · **`custom_collate_fn`** with **per-batch dynamic padding** (sized to the longest in *this* batch, not the global max) + shift-by-one + `pad_id=50256` · the **`ignore_index=-100`** masking trick (one EOT kept un-masked so the model learns end-of-text) · **instruction-loss masking** — mask the prompt tokens, train *only* on the response · plug into the M57 loop (one-line change: `ignore_index=-100`) · **LLM-as-judge with Ollama Llama 3** — `make_judge_prompt` + integer 0-100 scoring · what `SFTTrainer` *also* hides (packing, NEFTune, kernel patches, auto chat templates) · forward to **DPO** (M62). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_59_instruction_tuning_internals.ipynb) |
| 60 | **KV-Cache Implementation** — turn `generate()` from O(N²) into O(N). Why naive decode is wasteful (re-computes K/V for every prior token every step) · **modify `CausalMHA`** to accept + return a `(K, V)` cache and `torch.cat` the new K/V onto the cached ones · per-layer **list of caches** + a `pos_offset` so positional embeddings line up during decode · **pre-fill once / decode one-token-at-a-time** with `generate_with_cache` · benchmark naive vs cached on the same model (sanity check: identical outputs) · **KV-cache memory math** — Llama-3-8B 8K-ctx ≈ 1 GB *per request*, 32 concurrent ≈ a whole A100 · ties straight back to **PagedAttention** in vLLM (M44) · the frontier: **GQA** (M61), **MLA**, **SWA**, **FP8 KV**, **speculative decoding**. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_60_kv_cache_implementation.ipynb) |
| 61 | **GPT-2 → Llama 3 Architecture Conversion** — four contained swaps and you have Llama. **LayerNorm → RMSNorm** (drop mean centring, no beta, one fewer matmul per LN) · **abs `pos_emb` → RoPE** with `precompute_rope_freqs` + `apply_rope` rotating Q/K pairs; Llama-3's `base=500 000` for extended context · **GELU MLP → SwiGLU** with three weight matrices (`w_gate · silu · ⊙ · w_up · w_down`) and the ~2.66× `d_ff` rule · **MHA → GQA** with `n_kv_heads < n_heads` and `repeat_interleave` (KV-cache shrinks `n_heads/n_kv_heads`× — *why* Llama-3-8B holds 32K context on one GPU) · full `LlamaBlock` with identical skeleton to M56 · `LlamaModel` spec (vocab 128 256, **untied** LM head) · **load Llama-3.2-1B `safetensors` from HF** — clean state-dict, no transpose, no fused split, no tying · bigger-picture table mapping Mixtral · DeepSeek-V3 · Mistral · Gemma · Olmo · Phi to "Llama + one extra trick". | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_61_gpt2_to_llama3_conversion.ipynb) |
| 62 | **DPO from Scratch** — alignment after SFT, in one formula. SFT vs **DPO** vs PPO comparison · the Bradley-Terry → DPO loss derivation (Z(x) cancels; loss = −log σ(β · log-ratio difference)) · the **frozen reference model** (your SFT model, `requires_grad=False`) and why you need it · preference dataset shape `(prompt, chosen, rejected)` (Anthropic HH-RLHF · UltraFeedback) · DPO **collate** that pads chosen and rejected separately and masks prompt tokens like M59 · **`compute_log_probs`** (SUM not average — vanilla DPO doesn't length-normalise) · **`dpo_loss_batch`** — the entire algorithm in 15 lines with metrics (reward chosen / rejected / **margin** / **accuracy**) · **β ≈ 0.1**, LR 5e-7→5e-6, 1-3 epochs · failure-mode table (both rewards falling, reward hacking, OOM) · variants you'll meet — **IPO · KTO · SimPO · ORPO · GRPO** (M67) · what `trl.DPOTrainer` adds on top (LoRA, accelerate, packing). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_62_dpo_from_scratch.ipynb) |
| 63 | **BPE Tokenizer from Scratch** — train BPE end-to-end in pure Python so `tiktoken` stops being magic. Why subword wins (recap from M55) · **byte-level pre-tokenisation** with `</w>` end-of-word markers + `{word_tuple: count}` corpus shape · the 4-step training algorithm · **`get_stats`** (count adjacent pairs weighted by word count) + **`merge`** (apply one merge rule across the corpus) · **`train_bpe`** loop with the merge-rank ledger that becomes `tiktoken`'s `merges.txt` · **encode** by greedily applying the lowest-rank merge first (deterministic, no `<unk>` — falls back to bytes) · trivial decode · side-by-side with **`tiktoken`** on the same string · what real BPE adds (**byte-level fallback** for full Unicode, GPT-2's pre-tokeniser regex, special tokens, Rust cores, `bytes_to_unicode` dance). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_63_bpe_tokenizer_from_scratch.ipynb) |

### Part 9 — Production Gaps *(MCP, multimodal, distributed training, alignment beyond DPO, orchestration, feature stores, evals, Triton, browser agents, big-data)*

The remaining production capabilities a 2026 AI/ML engineer reaches for. Modules 64–73.

| # | Module | Open in Colab |
|---|---|---|
| 64 | **MCP — Model Context Protocol** — Anthropic's "USB-C for AI tools." Why `N × M` integrations become `N + M` · the **three primitives** (**tools** for actions, **resources** for read-only data, **prompts** for templated workflows) · host / client / server / transport (**stdio** vs **Streamable HTTP**) · build a working server in ~30 lines with **`FastMCP`** (`@mcp.tool` / `@mcp.resource` / `@mcp.prompt`) · the JSON-RPC wire format (`initialize` → `tools/list` → `tools/call`) · templated resources via URI placeholders + binary resources · wire it to **Claude Desktop / Cursor / Code** via one `mcpServers` config block · MCP vs OpenAI function-calling vs LangChain `@tool` decision table · the 2025 ecosystem (GitHub · Slack · Postgres · Stripe · Linear · Notion servers). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_64_mcp_model_context_protocol.ipynb) |
| 65 | **Multimodal — VLM + Whisper + TTS** — beyond text-only. The "same transformer, swap the encoder on the front" mental model · **VLM architecture**: ViT image encoder → MLP projector → LLM with image as "soft tokens" · **CLIP** as the workhorse — same-space image + text embeddings for search, zero-shot classification, safety filters, VLM front-ends · run a real VLM (**Moondream2 / LLaVA / Qwen2-VL**) with the encode-image-once pattern · **Whisper** for ASR + the speed family (**faster-whisper · distil-whisper · whisper.cpp**) · TTS landscape — **OpenAI TTS · ElevenLabs · XTTS · Bark · Piper · F5-TTS / Kokoro** · end-to-end voice agent pipeline (ASR → LLM → TTS) with sub-second latency budget + **Realtime APIs** (OpenAI Realtime, Gemini Live) · **multimodal RAG** patterns (caption-then-embed · CLIP embeddings · **ColPali** late-interaction) · hosted vs local cost table · frontier (**GPT-4o · Gemini 2.5 · Qwen2.5-VL**). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_65_multimodal_vlm_whisper_tts.ipynb) |
| 66 | **Distributed Training (DDP / FSDP / DeepSpeed)** — how serious training actually runs. The **"16 bytes/param" rule** (7B = 112 GB, 70B = 1.1 TB → you *must* distribute) · `torch.distributed` primitives + the **NCCL collectives** (all-reduce, all-gather, reduce-scatter, broadcast, barrier) over NVLink and InfiniBand · **DDP** (`DistributedSampler` + `DDP(model)` + `loss.backward()` auto-all-reduce) · **FSDP** with `transformer_auto_wrap_policy`, `MixedPrecision(bf16)`, `BackwardPrefetch`, activation checkpointing, CPU offload · **DeepSpeed ZeRO stages 1/2/3** — same idea, different knob (ZeRO-3 ≡ FSDP) · **Tensor + Pipeline parallelism** for when one *layer* > one GPU · **3D parallelism** (`TP=8 · PP=16 · DP=4` on 512 GPUs) for Llama-3-405B / DeepSeek-V3 · launchers — **`torchrun` / `accelerate` / `deepspeed`** + SLURM/k8s · the small wins that stack (**bf16 · grad-accum · grad-checkpoint · Flash-Attn · `torch.compile`**) · production recipe for fine-tuning Llama-3-8B on 4× A100 with FSDP + accelerate. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_66_distributed_training.ipynb) |
| 67 | **RLHF / GRPO** — alignment beyond DPO. SFT → DPO → RL pipeline diagram + where each adds value · **classical RLHF** (the InstructGPT 3-stage: SFT, RM, PPO) · the **reward model** (SFT body + scalar head + Bradley-Terry loss) · **PPO in five equations** — rollouts, reward+KL, GAE advantages with a value model, **clipped surrogate**, value loss · why PPO is painful (4 models in memory, rollouts as bottleneck, hyperparameter hell, reward hacking) · **GRPO** (DeepSeek-R1's algorithm) — drop the value model, use **group-relative standardised rewards** as the advantage, keep PPO's clipping · **RLVR** — Reinforcement Learning with **Verifiable Rewards** (math `int(pred==gold)`, code `int(tests_pass)`, Lean proofs) → the recipe behind emergent reasoning · reward-hacking failure table (length bias · sycophancy · refusal collapse · reasoning collapse) · what frontier labs actually run (**GPT-4o · Claude 3.5 · Gemini 2.5 · DeepSeek-R1 · Qwen3 · Llama-3 · Tülu 3**) · decision table — DPO / KTO / PPO / GRPO / RLVR / Constitutional-AI. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_67_rlhf_grpo.ipynb) |
| 68 | **Workflow Orchestration** — Airflow vs Prefect vs Dagster (and the ML-native cousins). The pain orchestrators kill (failed task #3 of 7 at 3 AM, stale-data silent runs, hand-rolled backfills, missing lineage) · the universal 7 concepts (Task · DAG · Schedule · Sensor · Run · Backfill · Result) · **Airflow** with `PythonOperator` + `>>` dependency syntax + parse-time DAGs · **Prefect** with `@flow` + `@task`, dependency inferred from return-value flow, dynamic-by-default · **Dagster** with `@asset` + `AutoMaterializePolicy.eager()` and lineage built-in · ML-native: **Argo Workflows · Kubeflow Pipelines · Flyte · ZenML · Metaflow** · retries / alerts / idempotency / backfills + Airflow's "logical date" trap · **OpenLineage** + Prometheus + OTel for observability · cron-plus-bash as the legitimate alternative when ≤ 5 linear tasks · decision table including AWS Step Functions and dbt+Dagster combos. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_68_workflow_orchestration.ipynb) |
| 69 | **Feature Stores (Feast)** — the canonical fix for training-serving skew. The invisible bug (offline AUC 0.91, online lift 0 — same feature computed two slightly different ways) · the three layers (**registry · offline store · online store**) · Feast setup with `feast init` · the `Entity` / `FeatureView` / `Field` abstractions · **point-in-time correctness** via `AS OF` joins (Feast's killer feature; without it every team eventually leaks future data into training) · `feast apply` → `feast materialize-incremental` → `get_online_features` in ~1 ms · hosted alternatives — **Tecton · Hopsworks · Vertex AI FS · Databricks FS · SageMaker FS · Chronon** · **streaming features** via push API + on-demand transforms · feature stores for **LLM / RAG** (user profiles, session signals, conversation memory) and how they compose with vector DBs (M42) · "do you actually need one?" decision tree — most teams don't until ≥ 2 models share features across ≥ 2 systems. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_69_feature_stores_feast.ipynb) |
| 70 | **LLM Evals — lm-eval-harness · Promptfoo · Langfuse · Phoenix** — turning chatbots from demos into products. Five eval flavours (**reference metrics · programmatic checks · LLM-as-judge · human · online**) · how to curate a **golden set** (200-300 stratified production traces, version in git, every bug fix → new row) · when reference metrics work (deterministic outputs) and when they fail (paraphrase) · **LLM-as-judge done right** — pairwise > absolute, swap A/B to kill position bias, stronger judge than candidate, calibrate vs humans, never judge a model with itself · **`lm-eval-harness`** with the 2026-relevant benchmark cheat sheet (favour **GPQA Diamond · AIME · SimpleBench · LiveBench · IFEval · Arena-Hard** over saturated MMLU/HellaSwag/HumanEval) · **Promptfoo** YAML with `contains`/`javascript`/`llm-rubric`/`factuality` assertions running in CI · **Langfuse + Phoenix** for production tracing + online scorers + UMAP-clustered failure exploration · **online A/B** with LLM-specific gotchas (latency confound, cost confound, length bias, long-tail vs common-case) · **anti-patterns** table (contamination, Goodhart, judge bias, tiny eval set, eval-only-once) · the 6-step shipping-team **playbook** (golden set → Promptfoo CI → harness on release → Langfuse traces → online A/B → weekly review loop). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_70_llm_evals.ipynb) |
| 71 | **Triton Inference Server** — one server for many models. The "9 models, 9 servers" problem and how Triton replaces it with **one Docker image** + one `/metrics` + hot-loaded models from a file-system **model repository** · the only-config-you-write `config.pbtxt` (`backend`, `max_batch_size`, `input` / `output` specs, `dynamic_batching`, `instance_group`) · **multi-framework backends** — PyTorch · TensorFlow · ONNX · TensorRT · OpenVINO · FIL (XGBoost) · **vLLM** · Python (escape hatch) · DALI · **TRT-LLM** · **dynamic batching** as the signature throughput win (2-10× on the same hardware) with latency-vs-throughput tuning rules · **multi-instance** per GPU with `instance_group { count }` + per-GPU pinning · **ensembles** (DAG in `config.pbtxt`) vs **Business Logic Scripting (BLS)** for branching/loops — keep multi-model pipelines INSIDE the server (no extra HTTP hops) · **TensorRT** + **TRT-LLM** for the fastest backend (in-flight batching, paged KV, FP8/INT4) · the latency-breakdown Prometheus metrics (queue / compute_input / compute_infer / compute_output) + **`model-analyzer`** auto-sweep · decision table vs vLLM / TGI / TF Serving / TorchServe / Ray Serve / SageMaker. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_71_triton_inference_server.ipynb) |
| 72 | **Computer-use / Browser Agents** — when the only API is the human UI. The screenshot → VLM → action → loop mental model · the standard **action space** (`screenshot · click · type · scroll · key · navigate · done`) · 2025-26 hosted: **Claude computer-use · OpenAI Operator (Computer-use Agent) · Gemini Mariner** with API sketches · OSS: **browser-use · Skyvern · Stagehand · WebVoyager · UI-TARS / OS-Atlas / SeeClick** · the **Playwright + LLM** build-it-yourself recipe with constrained action vocabulary · benchmarks landscape — **OSWorld · WebArena · WebVoyager · Mind2Web · ScreenSpot · AndroidWorld** with frontier numbers (grounding ≈ solved at 90%+, full tasks ~30-55%) · **the three-layer safety stack** (VM isolation + allowlist + human-in-the-loop confirmation) · the **prompt-injection-via-pixels** threat and the **guard model** pattern · 10-row failure-mode table (coordinate drift, infinite loop, CAPTCHA wall, stale screenshots, cost runaway) · decision tree — Playwright script > browser-use > full computer-use; when NOT to use (an API exists, high-volume, money / privileged data, customer-facing real-time). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_72_computer_use_browser_agents.ipynb) |
| 73 | **Spark + Delta Lake** — the data-engineering foundation. The single-machine memory wall (Pandas ~1 GB → Polars ~50 GB → DuckDB ~TB → **Spark = petabytes**) · architecture (**driver / cluster manager / executors / tasks / partitions**) · PySpark DataFrame API + **Spark SQL** producing identical Catalyst plans · **lazy evaluation + Catalyst + Tungsten** + `.cache()` discipline · hot patterns — `broadcast()` small dim tables, `Window` rolling features, vectorised `@pandas_udf`, partitioned writes · **Delta Lake**: ACID + schema enforcement + **`MERGE INTO`** + **time travel** + `OPTIMIZE` + `Z-ORDER` + `VACUUM` (with Iceberg / Hudi as cousins) · the **medallion architecture** (**Bronze / Silver / Gold**) · **Structured Streaming** with `withWatermark` + `checkpointLocation` for exactly-once · decision table vs **Polars · DuckDB · Snowflake · BigQuery · Trino · Flink** · 🎓 **course wrap-up** — what 73 modules let you build. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_73_spark_delta_lake.ipynb) |

> 🎯 **Why this part exists.** Most data-science courses end at "you can fit a regression and a random forest." This part picks up where that stops and walks through *why* modern AI works — building the same six model families that power production ML in 2026 (M18), opening up the transformer's attention mechanism (M19, M20), then doing the same for diffusion (M21) and time-series (M22). After Module 22 you've gone from `import pandas` (M1) to a working transformer language model, a diffusion sampler, and an LSTM forecaster — all in pure PyTorch, all in one repo. **Modules 23-24 then go one layer deeper** — the math foundations you wish you'd reviewed first, and the inference internals of a real frontier LLM (DeepSeek-V3).

---

## How to use

### Path A — In Colab (zero install, recommended)

1. Click any **Open in Colab** badge above.
2. The notebook opens in Colab. **File → Save a copy in Drive** to make it editable.
3. **Runtime → Run all** to execute, or step through with `Shift + Enter`.

### Path B — Locally

```bash
git clone https://github.com/kader-xai/data-science-roadmap.git
cd data-science-roadmap

pip install jupyter pandas numpy matplotlib seaborn scikit-learn \
            yfinance beautifulsoup4 lxml folium wordcloud pywaffle plotly requests

jupyter notebook
```

Each notebook starts with a `!pip install` cell, so you only need a working Python (3.9+) and pip.

---

## Datasets used

| Dataset | Source | Used in |
|---|---|---|
| **auto-mpg** — fuel efficiency of 1970s–80s cars | UCI ML Repository | M11–M15 (the spine of Part 3) |
| **California Housing** — block-level house values | scikit-learn built-in | M16 capstone |
| **Iris** — flower measurements | UCI ML Repository | M11 practice |
| **CO₂ Mauna Loa** — atmospheric CO₂ since 1958 | github.com/datasets/co2-ppm | M6 practice |
| **TSLA / GME / AAPL** stock prices + financials | Yahoo Finance via `yfinance` | M5 |

All datasets are fetched at runtime — nothing to download manually.

---

## Tech stack

| Layer | Tools |
|---|---|
| **Numerical** | NumPy, Pandas |
| **Visualization** | Matplotlib, Seaborn, Folium, Plotly, WordCloud, PyWaffle |
| **ML** | scikit-learn (LinearRegression, Ridge, Lasso, RandomForest, Pipelines, ColumnTransformer, GridSearchCV) |
| **Data ingestion** | `requests`, BeautifulSoup, `pd.read_html`, `yfinance`, sqlite3 |
| **Notebook host** | Jupyter / Google Colab |

---

## Roadmap

- [x] **Modules 1-16** — Data Science (Python, Viz, Analysis & ML foundations)
- [x] **Modules 17-22** — Machine Learning & AI (Python for ML, six core models, attention, multi-head + causal, diffusion, time-series)
- [x] **Modules 23-25** — AI-Research Foundations (math + PyTorch deep dive, DeepSeek-V3 inference internals, fine-tuning with full/LoRA/QLoRA/SFT)
- [x] **Module 26** — SQL for Data Science (the single biggest practitioner gap)
- [x] **Module 27** — Tree-Based Models & Gradient Boosting (XGBoost, LightGBM, SHAP)
- [x] **Module 28** — A/B Testing & Inferential Statistics
- [x] **Module 29** — MLOps: FastAPI + Docker + MLflow + Monitoring
- [x] **Module 30** — RAG & Vector Search
- [x] **Module 31** — Prompt Engineering & LLM Evaluation
- [x] **Module 32** — LangChain Essentials (LCEL, RAG, memory, tools)
- [x] **Module 33** — LangGraph: Stateful Agents
- [x] **Module 34** — LlamaIndex for Production RAG
- [x] **Module 35** — DSPy: Programmatic Prompts
- [x] **Module 36** — PostgreSQL + pgvector
- [x] **Module 37** — Redis for AI Backends
- [x] **Module 38** — Ollama + llama.cpp (local LLMs)
- [x] **Module 39** — Unsloth: Fast Fine-Tuning
- [x] **Module 40** — TensorFlow & Keras
- [x] **Module 41** — CUDA Programming Basics
- [x] **Module 42** — Vector DB Comparison (FAISS / Pinecone / Weaviate / Qdrant)
- [x] **Module 43** — crewAI & AutoGen (multi-agent)
- [x] **Module 44** — vLLM (high-throughput inference)
- [x] **Module 45** — gRPC for Service-to-Service
- [x] **Module 46** — Kubernetes for ML
- [x] **Module 47** — Helm Charts for ML
- [x] **Module 48** — Terraform for ML Infrastructure
- [x] **Module 49** — Ansible for ML Provisioning
- [x] **Module 50** — Prometheus + Grafana
- [x] **Module 51** — OpenTelemetry for LLMs
- [x] **Module 52** — Go for AI Backends
- [x] **Module 53** — Rust Crash Course
- [x] **Module 54** — TypeScript for AI Frontends

**Part 8 — LLMs from Scratch (Raschka deep-dive)**
- [x] **Module 55** — Tokenization + Text Pipeline from Scratch
- [x] **Module 56** — Real GPT-2 124M Assembly + Loading Pretrained Weights
- [x] **Module 57** — Pretraining Loop from Scratch
- [x] **Module 58** — Classification Fine-Tune (Spam Classifier on GPT-2)
- [x] **Module 59** — Instruction-Tuning Internals (no TRL)
- [x] **Module 60** — KV-Cache Implementation
- [x] **Module 61** — GPT-2 → Llama 3 Architecture Conversion
- [x] **Module 62** — DPO from Scratch
- [x] **Module 63** — BPE Tokenizer from Scratch

**Part 9 — Production Gaps**
- [x] **Module 64** — MCP (Model Context Protocol)
- [x] **Module 65** — Multimodal (Vision-Language + Whisper/TTS)
- [x] **Module 66** — Distributed Training (DDP / FSDP / DeepSpeed)
- [x] **Module 67** — RLHF / GRPO
- [x] **Module 68** — Workflow Orchestration (Airflow / Prefect / Dagster)
- [x] **Module 69** — Feature Stores (Feast)
- [x] **Module 70** — LLM Evals (lm-eval-harness / Promptfoo / Langfuse)
- [x] **Module 71** — Triton Inference Server
- [x] **Module 72** — Computer-use / Browser Agents
- [x] **Module 73** — Spark + Delta Lake

- [x] Exercises workbook + answer key (M1-M16)
- [x] Output-first practice workbook (M1-M16)
- [x] **ML track exercises workbook (M17-M22)**
- [x] Colab badges on every notebook + README
- [x] GitHub Pages static site
- [x] MIT license
- [ ] Per-module video walkthroughs
- [ ] **Module 23** — Reinforcement learning (Q-learning, REINFORCE, PPO)
- [ ] **Module 24** — Graph neural networks (GCN, GAT)
- [ ] **Module 25** — Production ML (FastAPI serving, Docker, monitoring)
- [ ] Translate README + practice problems to Tamil

If you'd like to contribute one of the open items, open an issue first to scope it.

---

## License

MIT — use, fork, teach with this repo freely. Attribution appreciated but not required.

## Contact

Found a bug or have a suggestion? Open an issue at <https://github.com/kader-xai/data-science-roadmap/issues>.
