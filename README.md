# Hi, I'm Zeyu Shao (邵泽宇)

Computer Science undergraduate graduating in 2027, focused on reliable AI systems, agents, retrieval, model routing, robotics, and developer tools.

I like turning probabilistic model behavior into systems that are testable, observable, and explicit about their limits: typed contracts, offline fixtures, deterministic traces, safety gates, and gated real-service integrations.

## Open-source contributions

**[CyberStrikeAI](https://github.com/AIPentest/CyberStrikeAI)** — Contributor

- Fixed a workflow save bug where confirming the metadata dialog did not resume saving, and added four behavioral regression tests.
- [PR #345](https://github.com/AIPentest/CyberStrikeAI/pull/345) · Merged upstream on Oct 8, 2026.

## Featured projects

### [Smart Campus Patrol Robot](https://github.com/realsxb/smart-campus-patrol-robot)

End-to-end intelligent patrol robot combining ROS Noetic, Spring Boot, Vue 3, MySQL, Kinect2, and YOLO for real-world campus security scenarios.

- Led a five-person course team as project lead and primary engineer, owning architecture, core implementation, cross-stack debugging, real-robot deployment, and acceptance.
- Built live mapping and localization, DB-backed waypoint annotation, multi-stop patrol scheduling, direct navigation, run control, teleoperation safety, and real-time dashboards.
- Integrated person and fire/smoke detection with anomaly popups, map markers, silence controls, active tracking, and patrol resumption.
- Verified through 358 backend tests, 52 frontend spec files, gated ROS builds, staged simulation acceptance, and Ubuntu real-robot testing.

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

`AI agents` · `RAG / GraphRAG` · `temporal memory` · `MCP / JSON-RPC` · `DAG runtimes` · `SLM/LLM routing` · `robotics / ROS` · `computer vision` · `evaluation` · `Python`

Portfolio: [buaahmjh.com/shaozeyv](https://buaahmjh.com/shaozeyv)
