# David Dunn
 
**Applied AI & Integration Engineer** · Santa Clara, CA · [daviddunn.dev](https://daviddunn.dev) · [LinkedIn](https://linkedin.com/in/mrdaviddunn)
 
I build AI systems that plan, execute, review, and fix their own work, with a person approving what actually ships. Before that: 7+ years of data engineering, BI, and automation for clients.
 
### Now: an agent runtime
 
Three small systems that let an AI agent do real work on a real computer, with every step checked, every action recorded, and a person in charge of what ships. They work with Claude Code and other MCP clients.
 
| Repo | What it does | Proof |
| --- | --- | --- |
| [heimdall](https://github.com/algorhythmic/heimdall) | Task state, checkpoints and write permissions for long-running human–agent work, over MCP | 293 tests · CI on Linux and Windows |
| [wayland-computer-use](https://github.com/algorhythmic/wayland-computer-use) | Guarded desktop control: rechecks the window before every input, logs every action, never replays what it can't confirm | 27/27 end-to-end desktop tasks · 37–47% faster with batching |
| [braid](https://github.com/algorhythmic/braid) | Explainable retrieval within a budget: BM25, embeddings, graph and recency, with an eval harness | 19–41× faster warm queries |
| [skald](https://github.com/algorhythmic/skald) | Archive of Claude Code and Codex conversations with exact provenance | 49 tests |
 
<!-- Uncomment when the explainer is live:
▶ [3-minute walkthrough of how they fit together](https://daviddunn.dev/projects#runtime)
-->
 
### Also built
 
- [**Nexus**](https://github.com/algorhythmic/projectnexus): real-time prediction-market intelligence that pre-filters 161M cross-platform pairs to ~1K before any LLM call; live at [marketfinder](https://marketfinder.daviddunn.dev)
- [**dbriefly**](https://dbriefly.daviddunn.dev): a daily audio brief built from 80+ sources, with a voice agent you can talk back to, at ~$0.03 per brief
- [**Saga**](https://daviddunn.dev/projects#saga): parallel Claude Code workers in sandboxed containers; a critic reviews every plan and I approve every merge (private repo)
- [**steam-mcp**](https://github.com/algorhythmic/steam-mcp): open-source MCP server for the Steam Web API (TypeScript)
More on [daviddunn.dev](https://daviddunn.dev).
