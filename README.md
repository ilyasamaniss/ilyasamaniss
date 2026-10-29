# Hi, I'm Ilyas 👋

AI/ML engineer and technical product manager in Montreal. I build search, ranking, and LLM-powered products, and I care about measuring whether they actually work. MSc in Machine Learning (Université de Montréal | Mila, Quebec AI Institute founded by Yoshua Bengio) and B.Eng. in Software Engineering (McGill). I work in English and French.

- 🛠️ Currently Technical PM (AI & Data) at FX Replay. Directed the end-to-end delivery of our **multimodal LLM copilot** (vision-language: text and image understanding) that **deflected ~30% of support tickets**, using **retrieval-augmented generation (RAG)** over a vector database of embedded knowledge-base content and **multi-model routing** across GPT, Claude and Gemini, for a fintech platform with 1M+ users (70K daily active).
- 🤖 I build with Claude and Claude Code every day, for prototyping, evals, agent workflows, and shipping code.
- 📈 Before that: ML research in systematic trading (FTMO) and ML engineering at CDPQ.
- 🔎 Interests: multimodal LLMs, hybrid retrieval, learning-to-rank, LLM evaluation and guardrails, agent and tool-calling workflows, A/B testing.

## Featured projects

### [commerce-query-aware-search](https://github.com/ilyasamaniss/commerce-query-aware-search)
**LLM-powered e-commerce search:** combines LLM query understanding with BM25 keyword retrieval for product search on a Shopify storefront. An open-source LLM (Gemma) interprets what the shopper means, while hard rules guarantee results respect real price and stock.
- Offline evaluation framework (pass rate, MRR@5, constraint violations) with reproducible ML pipelines and CI
- Adding LLM query understanding raised the benchmark pass rate from 50% to 70% and MRR@5 from 0.75 to 1.00, with zero constraint violations
- In progress: **hybrid (BM25 + embeddings)** retrieval and a **React + TypeScript** UI that compares search configurations side by side

`Python` `LLMs` `Search & ranking` `BM25` `Shopify API` `Evaluation` `CI/CD`

### [prediction-ranking-of-companies](https://github.com/ilyasamaniss/prediction-ranking-of-companies)
**Learning-to-rank for investment research.** Master's project (Mila / Université de Montréal) with CDPQ, comparing regression, classification, and ranking models with leakage-safe time-series evaluation and backtesting.
- The XGBoost ranker's top-20 recommendations beat an equal-weight benchmark by **8.17% on average over 12-month horizons** (2015–2019 test period)
- Compares ARIMAX, gradient boosting, and LSTM (with time-series clustering), using SHAP for model explainability

`Learning-to-rank` `XGBoost` `Time-series forecasting` `LSTM` `Explainable AI (SHAP)` `Backtesting`

## Toolbox

- **ML:** PyTorch, TensorFlow, scikit-learn, XGBoost, Transformers/LLMs, embeddings and vector search, SHAP
- **LLM apps:** RAG, multimodal (vision) LLMs, evals, guardrails, tool calling and agents, Claude / GPT / Gemini
- **Data & MLOps:** SQL, BigQuery, AWS SageMaker, Docker, Kubernetes, CI/CD, Datadog
- **Product:** roadmaps and PRDs, KPI ownership, A/B testing

## Contact

[LinkedIn](https://www.linkedin.com/in/ilyasamaniss/)
