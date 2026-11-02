# Ilyas Amaniss

AI/ML engineer and technical product manager in Montreal. I build LLM products, search and ranking systems, and I measure whether they actually work. I use Claude and Claude Code daily to prototype and ship code. MSc in Machine Learning (Université de Montréal | Mila, Quebec AI Institute founded by Yoshua Bengio), B.Eng. in Software Engineering (McGill). English and French.

## What I work on

Technical PM (AI & Data) at a fintech platform with 1M+ users (70K daily active), building a trading journal and analytics platform for traders.

- **Multimodal LLM copilot:** Led the end-to-end build of a multimodal LLM copilot (retrieval-augmented, text and images) serving 70K daily users and deflecting ~30% of support tickets. It routes each request across GPT, Claude and Gemini and retrieves answers from a vector database of knowledge-base content.
- **AI agents and agentic workflows:** Built internal AI agents (Claude skills) that connect through MCP to BigQuery, Datadog and other tools. One agent guides product managers to define success metrics and builds their KPI monitoring dashboard. Scheduled agent routines refresh every team's dashboards daily, and these dashboards gate each feature-flag rollout against the north-star metric. Trained teams to adopt the agents.
- **LLM evaluation (evals):** Built automated and human-in-the-loop evals, guardrails and production monitoring. They score model and prompt changes on quality, latency and cost.
- **Product and data:** Owned company-wide KPIs and the north-star dashboards that leadership uses. Ran A/B tests to decide which features to build, scale or cut.

**[MedBalance](https://medbalance.ca):** Built a bilingual fintech platform for Canadian healthcare professionals end-to-end with one partner. It runs on web, iOS and Android, with a bank reconciliation engine, a tax-rules engine and accountant-ready reports. All data is encrypted and stored in Canada.

Before that: ML research in systematic trading (FTMO) and ML engineering at CDPQ.

## Featured projects

### [commerce-query-aware-search](https://github.com/ilyasamaniss/commerce-query-aware-search)
**LLM-powered e-commerce search.** Combines LLM query understanding with hybrid retrieval (BM25 keyword search plus embedding-based semantic search) for a Shopify storefront. Hard rules in code guarantee that every result respects real price and stock.
- Adding LLM query understanding raised the benchmark pass rate from 50% to 70% and MRR@5 from 0.75 to 1.00, with zero constraint violations.
- An offline evaluation framework (pass rate, MRR@5, constraint violations) runs in CI, so every change is benchmarked before merge.
- A React + TypeScript web app compares two search configurations side by side on the same query.

### [prediction-ranking-of-companies](https://github.com/ilyasamaniss/prediction-ranking-of-companies)
**Learning-to-rank for investment research.** Master's project (Mila) with CDPQ. It compares regression, classification and ranking models using leakage-safe time-series evaluation and backtesting.
- The XGBoost ranker's top-20 recommendations beat an equal-weight benchmark by 8.17% on average over 12-month horizons.
- Models include ARIMAX, gradient boosting and LSTM with time-series clustering. SHAP shows which features drive each ranking.

## Toolbox

Python, SQL, PyTorch, scikit-learn, XGBoost · LLMs (Claude, GPT, Gemini), RAG, embeddings and vector search, evals · BigQuery, AWS SageMaker, Docker, CI/CD · React, TypeScript

[LinkedIn](https://www.linkedin.com/in/ilyasamaniss/)
