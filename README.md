# David Dunn
 
**Applied AI & Integration Engineer** · Santa Clara, CA · [daviddunn.dev](https://daviddunn.dev) · [LinkedIn](https://linkedin.com/in/mrdaviddunn)
 
I build AI systems that plan, execute, review, and fix their own work, with a person approving what actually ships. Background: 7+ years of data engineering, BI, and integration work for clients.
 
### Now building: a local-first agent runtime
 
Four small systems that let an AI agent do real work on a real computer. Every step is checked, every action is recorded, everything stays on the machine, and a person decides what ships. They work with Claude Code, Codex, and other MCP clients.
 
| Repo | What it does | Proof |
| --- | --- | --- |
| [heimdall](https://github.com/algorhythmic/heimdall) | Durable task state for long-running human–agent work: event-sourced and replayable, with scoped write grants over MCP | 293 tests · CI on Linux and Windows |
| [braid](https://github.com/algorhythmic/braid) | Retrieval within a byte budget: BM25, embeddings, graph, and recency, with a reason attached to every result and an eval harness to check it | 19–41× faster warm queries at 2K–20K records |
| [wayland-computer-use](https://github.com/algorhythmic/wayland-computer-use) | Guarded desktop control: rechecks the window before every input, logs every action, never replays what it can't confirm | 27/27 end-to-end desktop tasks · 2.58× faster change detection than screenshot polling |
| [skald](https://github.com/algorhythmic/skald) | Archive of Claude Code and Codex conversations with exact provenance, resumable from checkpoints | 49 tests |
 
<!-- Uncomment when the explainer is live:
▶ [3-minute walkthrough of how they fit together](https://daviddunn.dev/projects#runtime)
-->
 
### Also built
 
- [**Saga**](https://daviddunn.dev/projects#saga) — parallel agent workers in sandboxed containers; a critic reviews every plan and I approve every merge (private repo)
- [**dbriefly**](https://dbriefly.daviddunn.dev) — a daily audio brief built from 80+ sources, with a voice agent you can talk back to, at ~$0.03 per brief (private repo)
- [**Nexus**](https://github.com/algorhythmic/projectnexus) — real-time prediction-market intelligence that pre-filters 161M cross-platform pairs to ~1K before any LLM call; live at [marketfinder](https://marketfinder.daviddunn.dev)
- [**steam-mcp**](https://github.com/algorhythmic/steam-mcp) — open-source MCP server for the Steam Web API (TypeScript)
More on [daviddunn.dev](https://daviddunn.dev).
