# Hi, I'm Areeb 👋

**AI Engineer · RAG & Agentic Systems** · Barcelona, Spain

I'm an ML/AI engineer specialising in RAG, retrieval, LLM orchestration and AI evaluation. I build end-to-end AI systems where retrieval quality is measured, answers are grounded in evidence, and the system abstains when the evidence isn't there.

- 🎓 MSc in Intelligent Interactive Systems, Pompeu Fabra University (2024–2026). My thesis built a neuro-symbolic LLM workflow that turns a chess engine's reasoning into grounded natural-language explanations.
- 💼 Previously a backend developer at SigmaX Marketing, shipping client web apps in Django, Flask and Node.js with React front ends.
- 🛰️ Before that, a geospatial data science intern at Aligarh Muslim University.
- 🏆 Winner, PLYO Lab Hackathon, Barcelona (2025).

[LinkedIn](https://linkedin.com/in/areebfazli) · [Email](mailto:areeb.fazli@outlook.com)

## Featured projects

### [rag_search](https://github.com/areebfazli/rag_search): Semantic search with a RAG engine

A hybrid search API over BEIR/SciFact that fuses BM25 and dense embeddings in Qdrant with Reciprocal Rank Fusion, then generates cited, evidence-grounded answers or abstains.

- Hybrid retrieval reaches **nDCG@10 0.724** and **Recall@100 0.965** on 300 queries, beating BM25 by +0.038 nDCG@10 (p = 0.0007).
- Cross-encoder reranking was left off by default because it added roughly 160× latency without a meaningful quality gain.
- An LLM-as-judge evaluation crosses answer/abstain verdicts with gold relevance labels, so abstention is measured rather than assumed.

`Python` `FastAPI` `Qdrant` `bm25s` `BGE embeddings` `ranx` `Docker` `GitHub Actions`

### [repo_sentinel](https://github.com/areebfazli/repo_sentinel): AI code review and security platform

An AI security reviewer for pull requests. It parses changed functions with tree-sitter, retrieves evidence from a CVE corpus and from the team's past review discussions, validates each finding against the code it quotes, and posts deduplicated inline comments through a GitHub Action.

`Python` `FastAPI` `Qdrant` `tree-sitter` `Semgrep` `SQLAlchemy` `GitHub Actions`

### [find_waldo](https://github.com/areebfazli/find_waldo): Warm-intro finder for VC funds 🏆

Winner of the PLYO Lab Hackathon (2025), built by a team of three in under 48 hours. Partners upload their LinkedIn connections, and founders ask "who can intro me to X at Y?" to get ranked warm-introduction paths across the fund's portfolio.

`Next.js` `TypeScript` `FastAPI` `MongoDB` `OpenAI`

### Other projects

- [football_prediction](https://github.com/areebfazli/football_prediction): a Streamlit app that predicts a player's next-season goals and assists, comparing hand-implemented linear regression with tuned neural networks. `TensorFlow` `scikit-learn` `Streamlit`
- [stock_trading_app](https://github.com/areebfazli/stock_trading_app): buy and sell stocks with virtual currency and track your portfolio. `Flask` `SQLite` `Chart.js`

## Skills

- **Applied AI/ML:** RAG, hybrid retrieval (BM25 + dense), embeddings, reranking, agentic systems, LLM orchestration, LLM evaluation (LLM-as-judge), nDCG / Recall / MRR, Qdrant, Hugging Face, PyTorch, TensorFlow, scikit-learn
- **Backend:** Python, FastAPI, Flask, Django, Node.js, TypeScript, React, REST APIs, SQLAlchemy, PostgreSQL, MySQL, MongoDB, pytest
- **Cloud & MLOps:** Docker, GitHub Actions, CI/CD, AWS (S3, EC2, SageMaker), Kubernetes, MLflow, DVC

## Publication

**Co-author**, *Assessment of Solid Waste Management Using Geospatial Techniques and Artificial Intelligence: A Case Study of the United Arab Emirates.* In *Shaping the Future of Development in the GCC*, Springer, 2025. [DOI: 10.1007/978-981-96-7963-8_10](https://doi.org/10.1007/978-981-96-7963-8_10)
