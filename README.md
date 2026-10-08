<h1 align="center">Nishchay Mahor</h1>
<p align="center">
  ML Systems Engineer at <a href="https://mysta.ge">MyStage Music</a> · MS in Data Science at UC San Diego<br/>
  Product Management Intern at <a href="https://www.infoblox.com/">Infoblox</a> (Summer 2026)
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

- Spending the summer in the product org at **[Infoblox](https://www.infoblox.com/)** as a Product Management intern.
- Working on the AI pipelines at **[MyStage Music](https://mysta.ge)**, a live-music discovery platform connecting independent artists with audiences and venues.
- Shipping fixes and features into the AI tooling I actually use day to day; 30 merged PRs across 20 orgs so far, highlights below.
- Reading the LangGraph internals, whatever new agent paper is going viral that week, and the older systems books that age well (Designing Data-Intensive Applications stays open on my desk).

### Open source

The merges I'd show first:

- <img src="https://github.com/ml-explore.png?size=40" width="18" height="18" align="top" alt="" /> **[Apple MLX](https://github.com/ml-explore/mlx-lm/pull/1912)** <img src="https://img.shields.io/github/stars/ml-explore/mlx-lm?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — `top_p` small enough to round past float precision masked every token, so the sampler returned noise instead of the most likely one. Worst at bfloat16, which is what on-device inference actually runs.
- <img src="https://github.com/comet-ml.png?size=40" width="18" height="18" align="top" alt="" /> **[Comet Opik](https://github.com/comet-ml/opik)** <img src="https://img.shields.io/github/stars/comet-ml/opik?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — four merges: [Groq](https://github.com/comet-ml/opik/pull/7341) and [Cerebras](https://github.com/comet-ml/opik/pull/7342) integrations, the [Ollama SDK integration](https://github.com/comet-ml/opik/pull/8368), and a [logging fix](https://github.com/comet-ml/opik/pull/8238) that was swallowing every stream diagnostic
- <img src="https://github.com/dottxt-ai.png?size=40" width="18" height="18" align="top" alt="" /> **[dottxt outlines](https://github.com/dottxt-ai/outlines)** <img src="https://img.shields.io/github/stars/dottxt-ai/outlines?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — two type-system fixes found by differential-fuzzing the hand-rolled regexes against `ipaddress` — [leading-zero octets in `ipv4`](https://github.com/dottxt-ai/outlines/pull/1904) and [the same bug in IPv4-mapped IPv6](https://github.com/dottxt-ai/outlines/pull/1936) — plus [a mypy hook fix](https://github.com/dottxt-ai/outlines/pull/2003) for the style job
- <img src="https://github.com/NVIDIA.png?size=40" width="18" height="18" align="top" alt="" /> **[NVIDIA garak](https://github.com/NVIDIA/garak/pull/1809)** <img src="https://img.shields.io/github/stars/NVIDIA/garak?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — native Anthropic generator for the LLM vulnerability scanner
- <img src="https://github.com/langgenius.png?size=40" width="18" height="18" align="top" alt="" /> **[dify](https://github.com/langgenius/dify/pull/36755)** <img src="https://img.shields.io/github/stars/langgenius/dify?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — storage-layer `@override` refactor in the most-starred open-source LLM app platform
- <img src="https://github.com/stanfordnlp.png?size=40" width="18" height="18" align="top" alt="" /> **[Stanford DSPy](https://github.com/stanfordnlp/dspy/pull/9977)** <img src="https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — `Document.format()` was emitting an invalid source type for PDFs
- <img src="https://github.com/a2aproject.png?size=40" width="18" height="18" align="top" alt="" /> **[Google A2A](https://github.com/a2aproject/a2a-python/pull/1153)** <img src="https://img.shields.io/github/stars/a2aproject/a2a-python?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — a silently-ignored `queue_manager` in the v2 request handler, with the warning the project's own test harness needed
- <img src="https://github.com/promptfoo.png?size=40" width="18" height="18" align="top" alt="" /> **[promptfoo](https://github.com/promptfoo/promptfoo)** <img src="https://img.shields.io/github/stars/promptfoo/promptfoo?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — three provider integrations: [NVIDIA NIM](https://github.com/promptfoo/promptfoo/pull/9491), [Fireworks AI](https://github.com/promptfoo/promptfoo/pull/9542), and [Moonshot Kimi](https://github.com/promptfoo/promptfoo/pull/9672)
- <img src="https://github.com/Arize-ai.png?size=40" width="18" height="18" align="top" alt="" /> **[Arize openinference](https://github.com/Arize-ai/openinference)** <img src="https://img.shields.io/github/stars/Arize-ai/openinference?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — [Cohere](https://github.com/Arize-ai/openinference/pull/3349), [Ollama](https://github.com/Arize-ai/openinference/pull/3348) and [Together AI](https://github.com/Arize-ai/openinference/pull/3350) instrumentors
- <img src="https://github.com/mistralai.png?size=40" width="18" height="18" align="top" alt="" /> **[Mistral AI](https://github.com/mistralai/mistral-common/pull/231)** — `from_model` deprecation fix in the official tokenizer library
- <img src="https://github.com/aws.png?size=40" width="18" height="18" align="top" alt="" /> **[AWS agentcore-cli](https://github.com/aws/agentcore-cli/pull/1424)** — zip-stage config regression fix
- <img src="https://github.com/SQLMesh.png?size=40" width="18" height="18" align="top" alt="" /> **[SQLMesh](https://github.com/SQLMesh/sqlmesh/pull/5878)** <img src="https://img.shields.io/github/stars/SQLMesh/sqlmesh?style=flat-square&label=%E2%98%85&labelColor=161b22&color=30363d" align="top" alt="stars" /> — invalidating a nonexistent environment failed silently instead of erroring

Also merged into <img src="https://github.com/weaviate.png?size=40" width="16" height="16" align="top" alt="" /> [Weaviate](https://github.com/weaviate/weaviate), <img src="https://github.com/deepgram.png?size=40" width="16" height="16" align="top" alt="" /> [Deepgram](https://github.com/deepgram/deepgram-python-sdk), <img src="https://github.com/voyage-ai.png?size=40" width="16" height="16" align="top" alt="" /> [Voyage AI](https://github.com/voyage-ai/voyageai-python), <img src="https://github.com/cartesia-ai.png?size=40" width="16" height="16" align="top" alt="" /> [Cartesia](https://github.com/cartesia-ai/cartesia-python), <img src="https://github.com/braintrustdata.png?size=40" width="16" height="16" align="top" alt="" /> [Braintrust](https://github.com/braintrustdata/braintrust-sdk), <img src="https://github.com/basetenlabs.png?size=40" width="16" height="16" align="top" alt="" /> [Baseten Truss](https://github.com/basetenlabs/truss), <img src="https://github.com/Mirascope.png?size=40" width="16" height="16" align="top" alt="" /> [Mirascope](https://github.com/Mirascope/mirascope) and ogx.

Still open in <img src="https://github.com/traceloop.png?size=40" width="16" height="16" align="top" alt="" /> [openllmetry](https://github.com/traceloop/openllmetry/pull/4202), <img src="https://github.com/Aider-AI.png?size=40" width="16" height="16" align="top" alt="" /> [aider](https://github.com/Aider-AI/aider/pull/5200), the <img src="https://github.com/modelcontextprotocol.png?size=40" width="16" height="16" align="top" alt="" /> [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk/pull/2170), <img src="https://github.com/vllm-project.png?size=40" width="16" height="16" align="top" alt="" /> [vLLM](https://github.com/vllm-project/vllm/pull/49923), <img src="https://github.com/apple.png?size=40" width="16" height="16" align="top" alt="" /> [Apple coremltools](https://github.com/apple/coremltools/pull/2887), <img src="https://github.com/pinecone-io.png?size=40" width="16" height="16" align="top" alt="" /> [pinecone](https://github.com/pinecone-io/python-sdk/pull/683) and a few more.

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
- REAL MADRID and CR7. 

### Hackathon builds

When I get a weekend and a problem statement, I build things like **StepWise** (AWS Breaking Barriers 2024, digital inclusion copilot), **DocuGuard AI** (HackAI Dell/NVIDIA 2024, enterprise document risk), and **NeuroForecast AI** (UCSD SMASH NSF HDR 2026, OOD-robust neural forecasting). Constraints make for sharper systems.

### Writing & talks

- *Revolutionizing Market Surveys through Generative AI for Efficient Data Synthesis*, keynote at the [Machine Learning Developers Summit 2024](https://mlds.analyticsindiamag.com/), published in Lattice Journal (AoDS), Vol. 5 Issue 1.
- Occasional notes on [Medium](https://medium.com/@emailfornishchay).
