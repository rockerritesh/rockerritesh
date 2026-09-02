# Hi, I'm Sumit Yadav 👋

Building the **trust layer for AI agents** — the identity, audit, and memory primitives enterprise teams need before agents can actually ship.

💻  Computer Engineering · I.O.E. Pulchowk Campus, Nepal
🌐  [sumityadav.com.np](https://sumityadav.com.np) · [Google Scholar](https://scholar.google.com/citations?user=ag74ytsAAAAJ&hl=en) · X [@Rocker_Ritesh](https://x.com/Rocker_Ritesh)
💌  `echo 'cm9ja2Vycml0ZXNoNEBnbWFpbC5jb20K' | base64 -d`

---

## 🔭 What I'm working on

My bet: **memory without identity can't be audited, and identity without memory can't be explained.** Enterprise AI trust needs both halves — and today they're being built in isolation. I'm building them as one system.

| Repo | What it is | Stack |
|---|---|---|
| **[agentguard](https://github.com/rockerritesh/agentguard)** | Zero-trust security plane for AI agents. Every agent gets a SPIFFE X.509 identity; every tool call flows through an OPA policy engine and mTLS proxy; every action lands in an append-only audit log. Service-mesh primitives for agents. | Go · Python SDK · React dashboard |
| **[sumit-server](https://huggingface.co/spaces/rockerritesh/sumit-server)** | Audited memory infrastructure for agents — every read and write carries a queryable transaction trail. 18 MCP tools, live on HF Spaces. | Python · Qdrant · MCP |
| **[spiffe-core](https://github.com/rockerritesh/spiffe-core)** | A minimal SPIFFE implementation (Workload API, trust bundles, attestation) — the identity substrate AgentGuard builds on. | Python · FastAPI |
| **[trat-multi-agent](https://github.com/rockerritesh/trat-multi-agent)** | Reference build of IETF Transaction Tokens (TraT) applied to multi-agent AI workflows: TxTS + gateway + agent pipeline, end-to-end. | Python · TypeScript |

Each repo cross-links the others so any of them walks you through the whole story. Open to conversations with investors and design partners — happy to demo.

---

## 🧠 Other active work

- 🧪 [**Tatva**](https://tatva.sumityadav.com.np) — the dashboard for sumit-server: transaction trail, access stats, memory versioning.
- 📝 [**Blogs / Canvas**](https://sumityadav.com.np/blog) — thinking-in-public on agent trust, memory, and identity.
- 🤖 [**agents.ai**](https://rockerritesh.github.io/agents.ai/) — multi-agent orchestration playground with semantic agent selection.
- 🔖 [**bio-llm**](https://llm.sumityadav.com.np) — in-browser semantic RAG experiment.
- 🧒 [**vibe-coder**](https://rockerritesh.github.io/vibe_coder/) — an agent that scaffolds Streamlit + FastAPI projects from plain English.

⚡  *Fun fact: read 100%, understand <10% (without music).*

![](https://komarev.com/ghpvc/?username=rockerritesh&label=PROFILE+VIEWS)
