# BlackRoad-Memory

> *Agents that remember everything.*

The memory infrastructure for BlackRoad OS — long-term memory, semantic search, context windows, and the codex that makes Roadies persistent across sessions.

## Memory Stack
- **memory_ltm** — Long-term memory (D1 SQLite, vector-ready)
- **memory_stm** — Short-term working memory per session
- **memory_codex** — Solutions + patterns database
- **context_bridge** — Cross-session context continuity
- **memory_indexer** — FTS5 full-text search across all memories

## Live
Every agent at **[roadtrip.blackroad.io](https://roadtrip.blackroad.io)** uses this stack.

---
*Part of [BlackRoad OS, Inc.](https://os.blackroad.io) — Remember the Road. Pave Tomorrow.* 🖤🛣️
