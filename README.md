<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Areeb%20Abad%20Fazli&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20RAG%20%26%20Agentic%20Systems&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="Areeb Abad Fazli, AI Engineer, RAG and Agentic Systems" />

<a href="https://github.com/areebfazli"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3500&pause=900&color=2C9AB7&center=true&vCenter=true&width=640&lines=Building+RAG+pipelines+that+measure+what+they+claim;Hybrid+retrieval+%C2%B7+LLM+orchestration+%C2%B7+AI+evaluation;Grounded+answers%2C+or+an+honest+abstention;MSc+Intelligent+Interactive+Systems+%40+UPF" alt="Typing summary" /></a>

<a href="https://linkedin.com/in/areebfazli"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NSAyMC40NWgtMy41NnYtNS41N2MwLTEuMzMtLjAyLTMuMDQtMS44NS0zLjA0LTEuODUgMC0yLjE0IDEuNDUtMi4xNCAyLjk0djUuNjdIOS4zNFY5aDMuNDF2MS41NmguMDVjLjQ4LS45IDEuNjQtMS44NSAzLjM3LTEuODUgMy42IDAgNC4yNyAyLjM3IDQuMjcgNS40NnY2LjI4ek01LjM0IDcuNDNhMi4wNiAyLjA2IDAgMSAxIDAtNC4xMyAyLjA2IDIuMDYgMCAwIDEgMCA0LjEzek03LjEyIDIwLjQ1SDMuNTZWOWgzLjU2djExLjQ1ek0yMi4yMiAwSDEuNzdDLjc5IDAgMCAuNzcgMCAxLjczdjIwLjU0QzAgMjMuMjMuNzkgMjQgMS43NyAyNGgyMC40NWMuOTggMCAxLjc4LS43NyAxLjc4LTEuNzNWMS43M0MyNCAuNzcgMjMuMiAwIDIyLjIyIDB6Ii8%2BPC9zdmc%2B&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:areeb.fazli@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yIDRoMjBhMiAyIDAgMCAxIDIgMnYxMmEyIDIgMCAwIDEtMiAySDJhMiAyIDAgMCAxLTItMlY2YTIgMiAwIDAgMSAyLTJ6bTAgMnYuNGwxMCA2LjIgMTAtNi4yVjZIMnptMjAgMi44LTkuNDcgNS44N2ExIDEgMCAwIDEtMS4wNiAwTDIgOC44VjE4aDIwVjguOHoiLz48L3N2Zz4%3D&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/Barcelona%2C%20Spain-2c5364?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Barcelona, Spain" />

</div>

## 👋 About me

I'm an ML/AI engineer specialising in **RAG, retrieval, LLM orchestration and AI evaluation**. I build end-to-end AI systems where retrieval quality is measured, answers are grounded in evidence, and the system abstains when the evidence isn't there.

- 🎓 **MSc in Intelligent Interactive Systems**, Pompeu Fabra University (2024–2026). My thesis built a neuro-symbolic LLM workflow that turns a chess engine's reasoning into grounded natural-language explanations.
- 💼 **Backend Developer**, SigmaX Marketing (2023–2024). I shipped client web apps in Django, Flask and Node.js with React front ends.
- 🛰️ **Geospatial Data Science Intern**, Aligarh Muslim University (2021–2022).
- 🏆 **Winner**, PLYO Lab Hackathon, Barcelona (2025).
- 📄 **Co-author** of a Springer chapter on AI and geospatial techniques for waste management ([DOI](https://doi.org/10.1007/978-981-96-7963-8_10)).

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🔎 [rag_search](https://github.com/areebfazli/rag_search)

**Semantic search with a RAG engine.** A hybrid search API over BEIR/SciFact that fuses BM25 and dense embeddings in Qdrant with Reciprocal Rank Fusion, then generates cited, evidence-grounded answers or abstains.

| nDCG@10 | Recall@100 | vs. BM25 |
| :---: | :---: | :---: |
| **0.724** | **0.965** | **+0.038** (p = 0.0007) |

- Reranking was left off by default because it added roughly 160× latency for no meaningful quality gain.
- An LLM-as-judge evaluation checks answer/abstain verdicts against gold relevance labels, so abstention is measured rather than assumed.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
<td width="50%" valign="top">

### 🛡️ [repo_sentinel](https://github.com/areebfazli/repo_sentinel)

**AI code review and security platform.** An AI security reviewer for pull requests. It parses changed functions with tree-sitter and retrieves evidence from a CVE corpus and from the team's past review discussions. It keeps only findings that quote the offending code, then posts deduplicated inline comments through a GitHub Action.

- **Ghost Hunter** matches changed code against known CVE patterns.
- **Team Memory** recalls how your team reviewed similar code before.
- It includes a FastAPI backend, a web dashboard, and a GitHub Action that comments on PRs.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏆 [find_waldo](https://github.com/areebfazli/find_waldo)

**Warm-intro finder for VC funds.** It won the PLYO Lab Hackathon (2025) and was built by a team of three in under 48 hours. Partners upload their LinkedIn connections, and founders ask *"who can intro me to X at Y?"* to get ranked warm-introduction paths across the fund's portfolio.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

</td>
<td width="50%" valign="top">

### ⚽ [football_prediction](https://github.com/areebfazli/football_prediction)

**Player performance predictor.** A Streamlit app that predicts a player's next-season goals and assists. It compares hand-implemented linear regression (normal equation and gradient descent) with tuned neural networks.

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
</tr>
</table>

## 🧰 Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,pytorch,tensorflow,sklearn,django,flask,nodejs,ts,react,nextjs,postgres,mysql,mongodb,docker,kubernetes,aws,githubactions,git,linux&perline=10" alt="Tech stack icons" />

<br /><br />

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=for-the-badge&logo=dvc&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

</div>

| Area | What I use |
| --- | --- |
| **Retrieval & RAG** | Hybrid retrieval (BM25 + dense), embeddings, reranking, RRF fusion, Qdrant |
| **LLM systems** | Agentic systems, LLM orchestration, LLM-as-judge evaluation |
| **Evaluation** | nDCG, Recall, MRR, BEIR, paired significance tests, ablations |
| **Backend** | FastAPI, Flask, Django, Node.js, REST APIs, PostgreSQL, MongoDB |
| **MLOps & cloud** | Docker, Kubernetes, GitHub Actions, AWS (S3, EC2, SageMaker), MLflow, DVC |

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=110&section=footer" width="100%" alt="" />

</div>
