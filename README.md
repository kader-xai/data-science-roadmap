# Data Science Roadmap

> A self-paced, code-first course covering the full path from `print("hello")` to working transformers, diffusion models, and time-series forecasters. **22 deep-dive notebooks** across four parts — Python foundations, visualization, data analysis, and a deeper machine-learning + AI track. Every notebook is one click away in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kader-xai/data-science-roadmap/blob/main/module_01_python_basics.ipynb) ← start with **Module 1**

🌐 **Live site:** <https://kader-xai.github.io/data-science-roadmap/>
📦 **License:** [MIT](LICENSE)

---

## What this is

Three IBM courses, condensed into a single GitHub repo you can work through in a weekend or stretch over a month. Every concept lands as **runnable code first**, then a short explanation of *why it works that way*. No videos to scrub through, no graded quizzes — just notebooks you can read, run, edit, and re-run until something clicks.

The course is one project — built around a shared dataset (auto-mpg cars from the 1970s–80s) — that you load in Module 11, clean in Module 12, explore in Module 13, model in Module 14, and evaluate in Module 15. The capstone in Module 16 deliberately switches to a different dataset (California Housing) to prove the workflow generalises.

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

> 🎯 **Why this part exists.** Most data-science courses end at "you can fit a regression and a random forest." This part picks up where that stops and walks through *why* modern AI works — building the same six model families that power production ML in 2026 (M18), opening up the transformer's attention mechanism (M19, M20), then doing the same for diffusion (M21) and time-series (M22). After Module 22 you've gone from `import pandas` (M1) to a working transformer language model, a diffusion sampler, and an LSTM forecaster — all in pure PyTorch, all in one repo.

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

## Why this repo exists

I built this for two reasons. First, the IBM Coursera tracks are excellent but locked behind a subscription and split across three courses — there was no single, runnable, open artefact that covered the whole arc. Second, most "data science from scratch" repos jump from `print("hello world")` to a Kaggle notebook with no in-between. This repo is the in-between. It walks you from variables → DataFrames → ML models in a single sequence where every step builds on the last.

Curriculum scaffold from the IBM Coursera tracks; notebooks rebuilt from scratch by [@kader-xai](https://github.com/kader-xai) with Claude (Anthropic) as a coding partner.

---

## Roadmap

- [x] **Modules 1-16** — Data Science (Python, Viz, Analysis & ML foundations)
- [x] **Modules 17-22** — Machine Learning & AI (Python for ML, six core models, attention, multi-head + causal, diffusion, time-series)
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
