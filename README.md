<h1 align="center">Hey, I'm Shaman 👋</h1>
<h3 align="center">CS Engineer building systems from first principles — runtimes, retrieval pipelines, and the infra in between</h3>

<p align="center">
  <a href="mailto:shamankannan@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/kShaman771"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<br>

### About

- 🎓 B.Tech Computer Science Engineering, PES University, Bengaluru — CGPA 8.90/10 (2023–2027)
- 🛠️ Ex Software Development Intern @ **AiNions Solutions** — built a multi-tenant onboarding platform that cut client setup time by ~90%
- 🔬 I default to first principles: raw syscalls instead of a framework, ablations instead of assumptions, until the numbers back the design
- 📄 Published research on uncertainty-guided RAG, peer-reviewed on Zenodo
- 📫 Reach me at **shamankannan@gmail.com**

<br>

### Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**🐳 [Docksmith](https://github.com/kShaman771/CC_Project_DockSmith)**
Docker-like container build & runtime, written from scratch in Go using raw Linux syscalls — no Docker, runc, or containerd underneath.
- 92% faster rebuilds via a SHA-256 content-addressed build cache
- Byte-for-byte reproducible image layers, full namespace/chroot isolation
- `Go` `Linux Syscalls` `Namespaces` `Content-Addressed Storage`

</td>
<td width="50%" valign="top">

**🧠 [URAG](https://github.com/kShaman771/URAG)**
Agentic RAG system replacing binary reflect/skip logic with a continuous joint confidence score. Published as a peer-reviewed Zenodo preprint.
- +76% F1, −75% hallucinations vs. Naive RAG on HotPotQA
- 7-condition ablation across 1,000 samples, 2 benchmarks
- `PyTorch` `Transformers` `ChromaDB` `Qwen2.5-7B`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🔍 [CodeLens](https://github.com/kShaman771/CodeLens)**
Automated GitHub PR review agent pairing AST-based static analysis with a local LLM reviewer — no paid APIs.
- 24 issues caught across 4 test PRs, 87.5% security-related
- Two-phase pipeline: 0.5s static scan + ~12s LLM review
- `Python` `FastAPI` `Ollama` `GitHub API`

</td>
<td width="50%" valign="top">

**🛍️ [CoMemo++](https://github.com/kShaman771/CoMemo_SBN06)**
Dual-path LVLM fusing product images, reviews, and sales signals for trend-aware inventory prediction.
- 22M+ Amazon reviews, 5.8M+ products processed
- 200K+ ViT/CLIP embeddings indexed for multimodal reasoning
- `CLIP` `ViT` `Cross-Attention` `DuckDB`

</td>
</tr>
</table>

<details>
<summary><b>⚡ <a href="https://github.com/kShaman771/169_Project2_BD">Real-Time Dynamic Content Streaming Platform</a></b></summary>
<br>
A 4-node Kafka streaming system — multi-threaded producers, broker infra, dynamic consumers, and a Flask/MySQL control plane — with an approval-driven <code>pending → approved → active → inactive</code> workflow replacing manual topic creation.
<br><br>
<code>Apache Kafka</code> <code>Python</code> <code>Flask</code> <code>MySQL</code> <code>Zookeeper</code>
</details>

<details>
<summary><b>🧮 <a href="https://github.com/kShaman771/neetcode-submissions">NeetCode Submissions</a></b></summary>
<br>
Ongoing log of DSA problem solutions worked through via the NeetCode roadmap — patterns over memorization, with clean, commented solutions per problem.
<br><br>
<code>DSA</code> <code>Algorithms</code> <code>Problem Solving</code>
</details>

<br>

### Open Source

- **[ChromaDB](https://github.com/kShaman771/chroma)** — Contributed a hybrid BM25 + dense retrieval RAG example (RRF fusion) to the official examples library ([PR #7499](https://github.com/chroma-core/chroma/pull/7499))
- **[Agent Lens (MCP)](https://github.com/kShaman771/agent-lens)** — Fixed deprecated `datetime.utcnow()` calls across the core entrypoint of this MLflow-evaluation MCP server, replacing with timezone-aware UTC handling

<br>

### Tech Stack

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
</p>
<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
</p>
<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>
<p>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square&logo=databricks&logoColor=white" />
</p>

<br>

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kShaman771&show_icons=true&theme=default&hide_border=true&count_private=true&cache_seconds=86400" height="165" alt="Shaman's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kShaman771&layout=compact&theme=default&hide_border=true&cache_seconds=86400" height="165" alt="Top languages" />
</p>

<!-- If the cards above show as broken images, GitHub's image cache is likely
     stale or the public vercel instance is rate-limited. This usually
     resolves itself within a few hours. If it persists, deploy your own
     free instance from https://github.com/anuraghazra/github-readme-stats
     (one-click "Deploy to Vercel" button in that repo's README) and swap
     the domain above for your own, e.g. your-app-name.vercel.app -->

<br>

<p align="center"><i>Always up for a conversation about systems design, retrieval, or infra — feel free to reach out.</i></p>
