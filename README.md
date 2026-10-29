# Hi, I'm Ilyas 👋

AI/ML engineer and technical product manager in Montreal. I build search, ranking, and LLM-powered products, and I care about measuring whether they actually work. MSc in Machine Learning (Université de Montréal / Mila) and B.Eng. in Software Engineering (McGill). I work in English and French.

- 🛠️ Currently Technical PM (AI & Data) at FX Replay. I shipped a RAG trading copilot with multi-model routing (GPT, Claude, Gemini) that has handled 12K+ conversations, on a platform with 1M+ users.
- 📈 Before that: ML research in systematic trading (FTMO) and ML engineering at CDPQ.
- 🔎 Interests: hybrid retrieval, learning-to-rank, LLM evaluation and guardrails, agent and tool-calling workflows, A/B testing.

## Featured projects

### [commerce-query-aware-search](https://github.com/ilyasamaniss/commerce-query-aware-search)
Query-aware product search for a Shopify storefront. An LLM (Gemma via Ollama) interprets the shopper's query, and code enforces catalog truth for price and stock.
- BM25, dense, and **hybrid (BM25 + embeddings)** retrieval with score fusion
- A benchmark suite with pass rate, MRR@5, and constraint-violation metrics, orchestrated with Tangle and SkyPilot
- A **React + TypeScript** UI that compares two search configurations side by side
- On the smoke benchmark, adding query analysis raised pass rate from 50% to 70%, raised MRR@5 from 0.75 to 1.00, and cut constraint failures to zero

`Python` `Shopify Storefront API` `BM25` `Embeddings` `Ollama` `React` `TypeScript` `GitHub Actions`

### [prediction-ranking-of-companies](https://github.com/ilyasamaniss/prediction-ranking-of-companies)
Master's project with CDPQ. It frames stock selection as regression, classification, and **learning-to-rank**, evaluated with leakage-safe time-series splits.
- An XGBoost ranker's monthly top-20 picks averaged a **+8.17% 12-month excess return** over the 2015–2019 test period
- Compares ARIMAX, gradient boosting, and LSTM, with SHAP for interpretability

`XGBoost` `Learning-to-rank` `LSTM` `ARIMAX` `SHAP` `Time series`

## Toolbox

**ML:** PyTorch, TensorFlow, scikit-learn, XGBoost, Transformers/LLMs, embeddings and vector search, SHAP
**LLM apps:** RAG, evals, guardrails, tool calling and agents, Claude / GPT / Gemini
**Data & MLOps:** SQL, BigQuery, AWS SageMaker, Docker, Kubernetes, CI/CD, Datadog
**Product:** roadmaps and PRDs, KPI ownership, A/B testing
