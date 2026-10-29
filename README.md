# Ilyas Amaniss

AI/ML engineer and technical product manager in Montreal. I build LLM products, search, and ranking systems, and I care about measuring whether they actually work. MSc in Machine Learning (Université de Montréal | Mila, Quebec AI Institute founded by Yoshua Bengio), B.Eng. in Software Engineering (McGill). English and French.

## What I work on

Technical PM (AI & Data) at a fintech platform with 1M+ users (70K daily active), building a trading journal and analytics platform for traders.

- **Multimodal LLM copilot:** directed the end-to-end delivery of a vision-language copilot (text and image understanding) that deflected ~30% of support tickets, using retrieval-augmented generation (RAG) over a vector database of embedded knowledge-base content and multi-model routing across GPT, Claude and Gemini.
- **AI agents and agentic workflows:** built internal AI agents (Claude skills) connected through MCP to BigQuery, Datadog and other tools. One agent guides product managers to define their product's success metrics and builds their KPI monitoring dashboard; scheduled agent routines refresh every team's dashboards daily to gate feature-flag rollouts against the north-star metric. Trained teams to adopt them.
- **LLM quality:** automated and human-in-the-loop evaluations (evals), guardrails, and production monitoring of quality, latency and cost.
- **Product and data:** owned company-wide KPIs and north-star dashboards for leadership, ran A/B tests, and use Claude and Claude Code daily for prototyping and shipping code.

Before that: ML research in systematic trading (FTMO) and ML engineering at CDPQ.

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
