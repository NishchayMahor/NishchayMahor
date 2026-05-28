<h1 align="center">Nishchay Mahor</h1>
<p align="center">
  ML Systems Engineer at <a href="https://mysta.ge">MyStage Music</a> · MS in Data Science at UC San Diego<br/>
  Incoming ML intern at <a href="https://www.infoblox.com/">Infoblox</a> for Summer 2026
</p>
<p align="center">
  <a href="https://linkedin.com/in/nishchaymahor">LinkedIn</a> ·
  <a href="https://medium.com/@emailfornishchay">Medium</a> ·
  <a href="https://contextjetai.com/nishchay">contextjetai.com/nishchay</a> ·
  <a href="mailto:emailfornishchay@gmail.com">emailfornishchay@gmail.com</a>
</p>

---

I build production AI systems and the unglamorous infra that keeps them upright. I get nerd-sniped by anything at the intersection of evals, agent orchestration, and inference cost.

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,cpp,java,bash,pytorch,tensorflow,sklearn,fastapi,react,nextjs,nodejs,docker,kubernetes,aws,azure,gcp,postgres,redis,supabase&perline=11" alt="Core stack" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/LlamaIndex-181818?style=for-the-badge&logoColor=white" alt="LlamaIndex" />
  <img src="https://img.shields.io/badge/DSPy-2F4858?style=for-the-badge&logoColor=white" alt="DSPy" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Anthropic-D4A27F?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Pinecone-1B8DC4?style=for-the-badge&logoColor=white" alt="Pinecone" />
  <img src="https://img.shields.io/badge/Weaviate-00C9A7?style=for-the-badge&logoColor=white" alt="Weaviate" />
  <img src="https://img.shields.io/badge/FAISS-336791?style=for-the-badge&logoColor=white" alt="FAISS" />
  <img src="https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j" />
</p>

### Stack I reach for

**Languages** Python, SQL, TypeScript, C++, Bash
**ML & modeling** PyTorch, TensorFlow, scikit-learn, XGBoost, CatBoost, Prophet, MLflow
**LLM tooling** LangChain, LangGraph, LlamaIndex, DSPy, MCP, Hugging Face, OpenAI, Anthropic
**Vector & graph** Pinecone, Milvus, Weaviate, FAISS, Neo4j
**Infra & delivery** Docker, Kubernetes, FastAPI, GitHub Actions, Azure, AWS, GCP, Databricks, Supabase
**Frontend & data viz** React, Next.js, Streamlit, Plotly, D3.js, Dash

### Now

- Working on the AI pipelines at **[MyStage Music](https://mysta.ge)**, a live-music discovery platform connecting independent artists with audiences and venues.
- Shipping fixes and features into the AI tooling I actually use day to day. Recent merges in [promptfoo](https://github.com/promptfoo/promptfoo) (NVIDIA NIM provider) and [dify](https://github.com/langgenius/dify). Open PRs in [garak](https://github.com/NVIDIA/garak), [dspy](https://github.com/stanfordnlp/dspy), [phoenix](https://github.com/Arize-ai/phoenix), the [MCP Python](https://github.com/modelcontextprotocol/python-sdk) and [TypeScript](https://github.com/modelcontextprotocol/typescript-sdk) SDKs, [openllmetry](https://github.com/traceloop/openllmetry), [openai-cookbook](https://github.com/openai/openai-cookbook), and a few more.
- Reading the LangGraph internals, whatever new agent paper is going viral that week, and the older systems books that age well (Designing Data-Intensive Applications stays open on my desk).

### Selected work

| Project | What it does | Impact |
|---|---|---|
| **Knowledge GraphRAG Platform** | Entity-linked graph over docs for import/export compliance. LangGraph, vector DB, Salesforce. | +87% answer precision, −45% research time. Auditable citations. |
| **Multimodal Synthetic Market Surveys** (C5i.ai) | Real-time respondent synthesis for CPG and marketing studies. LangChain, Azure OpenAI, multi-agent, Apify. | ~90% accuracy vs live benchmarks. $300K+ in attributable revenue. |
| **AI Sales Development Representative** (Wall Street client) | Prospecting, enrichment, personalization, outreach, reply handling for a PE / hedge-fund / family-office target list. LangChain agents, Pydantic workflows, React. | +35% qualified meetings, −60% manual prospecting, 200–300 leads/week. |
| **LLM Virtual Try-On Assistant** (apparel client) | Diffusion-based try-on (StableVITON) + OpenAI image + LangGraph + MediaPipe + Pinecone RAG over catalog. | Time-on-page +25%, CTR +18%. |
| **Predictive Maintenance + RAG** (Industry 4.0) | Vibration/temperature anomaly detection + RAG + forecasting for conveyor planners. scikit-learn, Prophet, LangGraph, Databricks. | Unplanned maintenance −15%, planning cycle −30%. |

### Things I have opinions about

- Evals are the only thing that scales engineering judgment. Most teams write the eval *after* deciding the model is good, which is backwards.
- Agent frameworks are mostly thin glue. Read the source before you adopt one.
- The best LangChain users I know also use less of LangChain over time.
- The cheapest performance win is almost always a smaller, better prompt. The second cheapest is caching. Quantization is rarely the answer people think it is.

### Hackathon builds

When I get a weekend and a problem statement, I build things like **StepWise** (AWS Breaking Barriers 2024, digital inclusion copilot), **DocuGuard AI** (HackAI Dell/NVIDIA 2024, enterprise document risk), and **NeuroForecast AI** (UCSD SMASH NSF HDR 2026, OOD-robust neural forecasting). Constraints make for sharper systems.

### Writing & talks

- *Revolutionizing Market Surveys through Generative AI for Efficient Data Synthesis*, keynote at the [Machine Learning Developers Summit 2024](https://mlds.analyticsindiamag.com/), published in Lattice Journal (AoDS), Vol. 5 Issue 1.
- Occasional notes on [Medium](https://medium.com/@emailfornishchay).
