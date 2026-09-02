<div align="center">

<!-- Decorative band only. GitHub's camo proxy sanitises SVG, stripping the <style>
     block and inline style="fill:…" that capsule-render's text depends on — so any
     name baked into this image renders invisible on GitHub even though it looks fine
     when the URL is opened directly. The name and tagline are real markdown below,
     which is also the version search engines can actually read. -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d7a6b,50:b07c10,100:d64a26&height=150&section=header"/>

# Syed Muhammad Mujtaba

### AI Engineer · production LLM systems

**I build AI systems that know what they don't know.**

grounded, or it refuses · real-time voice, under 500ms · measured, not vibes

<br/>

<a href="https://mujtabashah.com" target="_blank"><img src="https://img.shields.io/badge/Portfolio-mujtabashah.com-0d7a6b?style=for-the-badge&logo=vercel&logoColor=white"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/mujtaba-shah/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-2761ad?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
&nbsp;
<a href="mailto:mujtabashah1204@gmail.com"><img src="https://img.shields.io/badge/Email-d64a26?style=for-the-badge&logo=gmail&logoColor=white"/></a>
&nbsp;
<a href="https://mujtabashah.com/Syed_Muhammad_Mujtaba_Resume.pdf" target="_blank"><img src="https://img.shields.io/badge/CV-b07c10?style=for-the-badge&logo=readdotcv&logoColor=white"/></a>

**[Syed Muhammad Mujtaba — AI Engineer](https://mujtabashah.com)** · agentic RAG, multi-agent workflows and real-time voice

</div>

---

### 📐 The numbers

<div align="center">

<img src="https://img.shields.io/badge/retrieval_precision@5-0.72_→_0.89-0d7a6b?style=flat-square&labelColor=1d1926"/>
<img src="https://img.shields.io/badge/voice_latency-under_500ms-d64a26?style=flat-square&labelColor=1d1926"/>
<img src="https://img.shields.io/badge/manual_processing-cut_50%25-b07c10?style=flat-square&labelColor=1d1926"/>
<img src="https://img.shields.io/badge/companies_shipped_for-5-2761ad?style=flat-square&labelColor=1d1926"/>
<img src="https://img.shields.io/badge/MS_Artificial_Intelligence-LUMS_2026-2761ad?style=flat-square&labelColor=1d1926"/>

</div>

---

### 👋 What I build

My obsession is LLMs that stay **grounded** — not impressive on benchmarks, but reliable when the retrieval fails, the query is ambiguous, or the user asks something the knowledge base was never built to answer. The failure mode that matters in production isn't a model that refuses; it's a model that answers confidently from nothing.

Three things in practice. **Retrieval that grades its own output** and corrects itself before answering — cross-encoder reranking over Qdrant took top-5 precision from 0.72 to 0.89. **Real-time voice**, where the whole architecture is shaped by a latency budget: speech-to-text, inference, text-to-speech and routing all finish under 500ms or the caller hears a pause. And **the full-stack product** around both, from the vector store to the interface someone actually clicks.

Every number above is an output of an evaluation harness, not an impression formed from trying a few queries by hand.

- 📍 **Lahore, Pakistan** · available remote
- 🔭 Most recently **AI Innovation Specialist at IgniteTech (Crossover)** — GenAI shipped to live customers
- 🎓 **MS Artificial Intelligence, LUMS** — advanced retrieval, query rewriting, grounding evaluation
- 📫 **mujtabashah1204@gmail.com**

---

### 🚀 Selected work

Five production systems, each written up in full on **[mujtabashah.com](https://mujtabashah.com)** — mechanism first, then the number it produced.

| System | What it does |
| --- | --- |
| **[Corrective RAG with self-reflective retrieval](https://mujtabashah.com/projects/corrective-rag)** | A cyclic LangGraph state machine that grades its own retrieved documents, rewrites failing queries and falls back to web search. Cross-encoder reranking over Qdrant took top-5 precision from 0.72 to 0.89. |
| **[Real-time voice AI agent integration](https://mujtabashah.com/projects/voice-ai-agent)** | Voice agents on Telnyx and Genesys with GPT-4 dialogue management, held under 500ms end-to-end across concurrent inbound calls. |
| **[Multi-agent content platform](https://mujtabashah.com/projects/multi-agent-content-platform)** | A LangGraph agent graph, not a prompt chain — a critic rejects weak drafts back into the graph for another pass. |
| **[AI-powered HRMS with semantic policy search](https://mujtabashah.com/projects/hrms-semantic-search)** | Conversational retrieval across policies and handbooks, every answer returned with the clause it came from. |
| **[Retrieval & grounding evaluation harness](https://mujtabashah.com/projects/eval-harness)** | Golden sets per knowledge base, precision@k and groundedness scored separately, run as a CI regression gate. |

More at **[mujtabashah.com/projects](https://mujtabashah.com/projects)** · background at **[mujtabashah.com/about](https://mujtabashah.com/about)**

---

### 🛠️ Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=py,pytorch,fastapi,nextjs,react,nodejs,postgres,mongodb,redis,docker,gcp,githubactions&perline=6"/>
</p>

Grouped by what it's for, rather than everything I've ever imported:

| | |
| --- | --- |
| **Retrieval & agents** | LangGraph · LangChain · Qdrant · FAISS · cross-encoder reranking · MCP |
| **Models** | GPT-4o · Claude · Mistral · PyTorch · HuggingFace · fine-tuning · quantization |
| **Voice** | Telnyx · Genesys · Retell · Vapi |
| **Serving & product** | FastAPI · Next.js · React · Node/Express · PostgreSQL · MongoDB · Redis |
| **Evaluation & ops** | golden sets · precision@k · MRR · groundedness scoring · LLM-as-judge · Docker · Google Cloud · GitHub Actions |

---

### 🤝 Connect

<div align="center">

<a href="https://mujtabashah.com" target="_blank"><img src="https://img.shields.io/badge/Portfolio-0d7a6b?style=for-the-badge&logo=vercel&logoColor=white"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/mujtaba-shah/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-2761ad?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
&nbsp;
<a href="mailto:mujtabashah1204@gmail.com"><img src="https://img.shields.io/badge/Gmail-d64a26?style=for-the-badge&logo=gmail&logoColor=white"/></a>
&nbsp;
<a href="https://www.kaggle.com/mujtabashah4" target="_blank"><img src="https://img.shields.io/badge/Kaggle-b07c10?style=for-the-badge&logo=kaggle&logoColor=white"/></a>
&nbsp;
<a href="https://x.com/mujtabashah4" target="_blank"><img src="https://img.shields.io/badge/X-4a4238?style=for-the-badge&logo=x&logoColor=white"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:d64a26,50:b07c10,100:0d7a6b&height=100&section=footer"/>

</div>
