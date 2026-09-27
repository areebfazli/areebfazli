<a href="https://github.com/areebfazli">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg" />
    <img src="./assets/banner-light.svg" width="100%" alt="Areeb Abad Fazli. AI Engineer, RAG and Agentic Systems. Building RAG pipelines that measure what they claim. Hybrid retrieval, LLM orchestration, AI evaluation. MSc Intelligent Interactive Systems at UPF. Barcelona, Spain." />
  </picture>
</a>

<p>
  <a href="https://linkedin.com/in/areebfazli"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/btn-linkedin-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="./assets/btn-linkedin-light.svg" /><img src="./assets/btn-linkedin-light.svg" height="60" alt="LinkedIn" /></picture></a><a href="mailto:areeb.fazli@outlook.com"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/btn-email-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="./assets/btn-email-light.svg" /><img src="./assets/btn-email-light.svg" height="60" alt="Email" /></picture></a><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/btn-location-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="./assets/btn-location-light.svg" /><img src="./assets/btn-location-light.svg" height="60" alt="Barcelona, Spain" /></picture>
</p>

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/h-about-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/h-about-light.svg" />
  <img src="./assets/h-about-light.svg" width="100%" alt="About" />
</picture>

I'm an ML/AI engineer specialising in **RAG, retrieval, LLM orchestration and AI evaluation**. I build end-to-end AI systems where retrieval quality is measured, answers are grounded in evidence, and the system abstains when the evidence isn't there.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/about-timeline-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/about-timeline-light.svg" />
  <img src="./assets/about-timeline-light.svg" width="100%" alt="2024–2026: MSc in Intelligent Interactive Systems, Pompeu Fabra University. My thesis built a neuro-symbolic LLM workflow that turns a chess engine's reasoning into grounded natural-language explanations. 2025: Winner, PLYO Lab Hackathon, Barcelona. 2023–2024: Backend Developer, SigmaX Marketing. I shipped client web apps in Django, Flask and Node.js with React front ends. 2021–2022: Geospatial Data Science Intern, Aligarh Muslim University." />
</picture>

<a href="https://doi.org/10.1007/978-981-96-7963-8_10"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/about-publication-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="./assets/about-publication-light.svg" /><img src="./assets/about-publication-light.svg" width="100%" alt="Publication: Co-author of a Springer chapter on AI and geospatial techniques for waste management (DOI)" /></picture></a>

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/h-projects-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/h-projects-light.svg" />
  <img src="./assets/h-projects-light.svg" width="100%" alt="Selected work" />
</picture>

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/areebfazli/rag_search"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-rag_search-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="./assets/card-rag_search-light.svg" /><img src="./assets/card-rag_search-light.svg" width="100%" alt="rag_search: Semantic search with a RAG engine. Python, FastAPI, Qdrant, Docker" /></picture></a>

A hybrid search API over BEIR/SciFact that fuses BM25 and dense embeddings in Qdrant with Reciprocal Rank Fusion, then generates cited, evidence-grounded answers or abstains.

<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/rag-metrics-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="./assets/rag-metrics-light.svg" /><img src="./assets/rag-metrics-light.svg" width="100%" alt="nDCG@10 0.724 · Recall@100 0.965 · +0.038 vs. BM25 (p = 0.0007)" /></picture>

- Reranking was left off by default because it added roughly 160× latency for no meaningful quality gain.
- An LLM-as-judge evaluation checks answer/abstain verdicts against gold relevance labels, so abstention is measured rather than assumed.

</td>
<td width="50%" valign="top">

<a href="https://github.com/areebfazli/repo_sentinel"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-repo_sentinel-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="./assets/card-repo_sentinel-light.svg" /><img src="./assets/card-repo_sentinel-light.svg" width="100%" alt="repo_sentinel: AI code review and security platform. Python, FastAPI, Qdrant, GitHub Actions" /></picture></a>

An AI security reviewer for pull requests. It parses changed functions with tree-sitter and retrieves evidence from a CVE corpus and from the team's past review discussions. It keeps only findings that quote the offending code, then posts deduplicated inline comments through a GitHub Action.

- **Ghost Hunter** matches changed code against known CVE patterns.
- **Team Memory** recalls how your team reviewed similar code before.
- It includes a FastAPI backend, a web dashboard, and a GitHub Action that comments on PRs.

</td>
</tr>
<tr></tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/areebfazli/find_waldo"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-find_waldo-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="./assets/card-find_waldo-light.svg" /><img src="./assets/card-find_waldo-light.svg" width="100%" alt="find_waldo: Warm-intro finder for VC funds. Next.js, TypeScript, FastAPI, MongoDB" /></picture></a>

It won the PLYO Lab Hackathon (2025) and was built by a team of three in under 48 hours. Partners upload their LinkedIn connections, and founders ask *"who can intro me to X at Y?"* to get ranked warm-introduction paths across the fund's portfolio.

</td>
<td width="50%" valign="top">

<a href="https://github.com/areebfazli/football_prediction"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/card-football_prediction-dark.svg" /><source media="(prefers-color-scheme: light)" srcset="./assets/card-football_prediction-light.svg" /><img src="./assets/card-football_prediction-light.svg" width="100%" alt="football_prediction: Player performance predictor. TensorFlow, scikit-learn, Streamlit" /></picture></a>

A Streamlit app that predicts a player's next-season goals and assists. It compares hand-implemented linear regression (normal equation and gradient descent) with tuned neural networks.

</td>
</tr>
</table>

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/h-stack-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/h-stack-light.svg" />
  <img src="./assets/h-stack-light.svg" width="100%" alt="Toolbox" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/stack-skills-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/stack-skills-light.svg" />
  <img src="./assets/stack-skills-light.svg" width="100%" alt="Python, FastAPI, PyTorch, TensorFlow, scikit-learn, Django, Flask, Node.js, TypeScript, React, Next.js, PostgreSQL, MySQL, MongoDB, Docker, Kubernetes, AWS, GitHub Actions, Git, Linux. Retrieval &amp; RAG: Hybrid retrieval (BM25 + dense), embeddings, reranking, RRF fusion, Qdrant. LLM systems: Agentic systems, LLM orchestration, LLM-as-judge evaluation. Evaluation: nDCG, Recall, MRR, BEIR, paired significance tests, ablations. Backend: FastAPI, Flask, Django, Node.js, REST APIs, PostgreSQL, MongoDB. MLOps &amp; cloud: Docker, Kubernetes, GitHub Actions, AWS (S3, EC2, SageMaker), MLflow, DVC. Also: Hugging Face, SQLAlchemy, pytest." />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/footer-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/footer-light.svg" />
  <img src="./assets/footer-light.svg" width="100%" alt="Grounded answers, or an honest abstention." />
</picture>
