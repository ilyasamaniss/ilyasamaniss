# Ilyas Amaniss

AI/ML engineer and technical product manager in Montreal. I build LLM products, search, and ranking systems, and I care about measuring whether they actually work. MSc in Machine Learning (Université de Montréal | Mila, Quebec AI Institute founded by Yoshua Bengio), B.Eng. in Software Engineering (McGill). English and French.

**Current focus:** multimodal LLM applications, retrieval-augmented generation (RAG), multi-model routing, AI agents with MCP, and LLM evaluation and guardrails.

## Featured projects

### [commerce-query-aware-search](https://github.com/ilyasamaniss/commerce-query-aware-search)
**LLM-powered e-commerce search.** Combines LLM query understanding with hybrid retrieval (BM25 keyword + embedding-based semantic search) for product search on a Shopify storefront, while hard rules in code guarantee results respect real price and stock.
- Offline evaluation framework (pass rate, MRR@5, constraint violations) with CI
- Adding LLM query understanding raised the benchmark pass rate from 50% to 70% and MRR@5 from 0.75 to 1.00, with zero constraint violations
- React + TypeScript web app that compares two search configurations side by side

### [prediction-ranking-of-companies](https://github.com/ilyasamaniss/prediction-ranking-of-companies)
**Learning-to-rank for investment research.** Master's project (Mila) with CDPQ, comparing regression, classification, and ranking models with leakage-safe time-series evaluation and backtesting.
- The XGBoost ranker's top-20 recommendations beat an equal-weight benchmark by 8.17% on average over 12-month horizons
- ARIMAX, gradient boosting, and LSTM with time-series clustering; SHAP for explainability

## Toolbox

Python, SQL, PyTorch, scikit-learn, XGBoost · LLMs (Claude, GPT, Gemini), RAG, embeddings and vector search, evals · BigQuery, AWS SageMaker, Docker, CI/CD · React, TypeScript

[LinkedIn](https://www.linkedin.com/in/ilyasamaniss/)
