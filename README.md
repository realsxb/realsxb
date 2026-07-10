# Hi, I'm Zeyu Shao (邵泽宇)

Computer Science undergraduate graduating in 2027, focused on reliable AI agents, retrieval systems, model routing, and developer tools.

I like turning probabilistic model behavior into systems that are testable, observable, and explicit about their limits: typed contracts, offline fixtures, deterministic traces, safety gates, and gated real-service integrations.

## Featured projects

### [Vic3 Agent Harness](https://github.com/realsxb/vic3-agent-harness)

Offline-first, byte-reproducible Agent benchmark and main-loop harness integrating GraphRAG retrieval, Graphiti temporal memory, DoT DAG planning, tool constraints, and SLM/LLM routing.

- Ports-and-adapters design with mock/fake defaults and gated real backends.
- Dependency-aware DAG runtime with validation, repair, concurrency, and hard action enforcement.
- 227 tests passed and 6 gated-real tests skipped in the sanitized public snapshot.

### [Vic3 GraphRAG](https://github.com/realsxb/vic3-graphrag)

Auditable RAG system mapping Victoria 3 player slang to official mechanics through a reviewed concept graph and dual-source evidence.

- Lexical/exact retrieval plus an optional dual-view BGE-M3 semantic channel.
- Read-only MCP tools, late fusion, source references, and fallback/health guards.
- Public code snapshot contains synthetic tests only; raw community/wiki corpora and generated indexes are not distributed.

### [DoT Qwen Router](https://github.com/realsxb/dot-qwen-router)

DoT-inspired adaptive SLM/LLM routing with subtask decomposition, dependency DAGs, alpha-tree supervision, Qwen3 embeddings, and an AdapterMLP router.

- 4,289 labeled subtasks; validation accuracy 95.57%, macro-F1 0.7772.
- Reports class-aware metrics and a clearly bounded P3 evaluation (`n=35`).
- Separates CPU tests from optional GPU/model dependencies.

## Engineering interests

`AI agents` · `RAG / GraphRAG` · `temporal memory` · `MCP / JSON-RPC` · `DAG runtimes` · `SLM/LLM routing` · `evaluation` · `Python`

Portfolio: [buaahmjh.com/shaozeyv](https://buaahmjh.com/shaozeyv)
