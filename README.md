<h1 align="center">Aditya Singh</h1>
<p align="center"><strong>AI systems · Agent memory · Open-source engineering</strong></p>
<p align="center">Building systems that remember what matters, reason with evidence, and keep working when conditions change.</p>

<p align="center">
	<a href="https://github.com/kestra-io/blueprints/pulls?q=is%3Apr+is%3Amerged+author%3AOptimistOtaku"><img src="https://img.shields.io/badge/10%20PRs%20MERGED-KESTRA-1F232C?style=for-the-badge&logo=github&logoColor=200062&labelColor=CDC5FF" alt="Kestra contribution milestone: 10 pull requests merged" /></a>
</p>

I'm **Aditya**, also known as **OptimistOtaku**. I build AI applications and explore how intelligent systems select memories, handle uncertainty, and recover from failure. My work spans continual-learning experiments, graph-backed agents, edge memory, and Rust performance improvements in open source.

## Open source, with results

### Kestra — reliable workflows and data engineering

Contributed merged blueprints for database integrity, recoverable ingestion, portable search, and reproducible Python environments.

- **[PostgreSQL integrity audits](https://github.com/kestra-io/blueprints/pull/4929):** detect foreign-key violations after imports that bypass triggers, with read-only checks and retained audit evidence.
- **[SFTP → PostgreSQL ingestion](https://github.com/kestra-io/blueprints/pull/4635):** commit records and a processing ledger together, handle replays, and archive source files only after commit.
- **[Verified offline Python bundles](https://github.com/kestra-io/blueprints/pull/4811):** build a hash-verified wheelhouse and prove installation in a fresh environment with networking disabled.
- **[Portable SQLite search](https://github.com/kestra-io/blueprints/pull/4853):** build FTS5 catalogs and independently reopen them to verify integrity and search results.

[Explore my merged Kestra contributions →](https://github.com/kestra-io/blueprints/pulls?q=is%3Apr+is%3Amerged+author%3AOptimistOtaku)

### Cap — Rust performance work

Merged improvements to caption projection, keyboard-event indexing, style resolution, and 3D camera-track sampling.

| Contribution | Measured result |
| --- | --- |
| [Caption synchronization](https://github.com/CapSoftware/Cap/pull/2956) | **5.61× faster** for a one-hour source trimmed to 60 four-second clips |
| [Keyboard-overlay regeneration](https://github.com/CapSoftware/Cap/pull/2751) | **15.79 ms → 8.35 ms** for the one-hour / 60-clip API benchmark |
| [Style resolution](https://github.com/CapSoftware/Cap/pull/2957) | **2.82× faster** inactive lookups with 200 style segments |

These are scoped local benchmarks with methodology and regression checks in the linked PRs; they measure the affected operations, not overall editor FPS.

## Selected projects

### [GREG](https://github.com/OptimistOtaku/greg) · Agents with shared graph memory

A prototype robot crew coordinating through **FalkorDB**, with evidence, task dependencies, capabilities, and action receipts stored in a shared graph. Includes a **Gemini → MCP → validated actions** loop and a React/Three.js mission-control interface.

Three recorded live-model demonstrations completed all seven objectives, including blocked-corridor and robot-outage scenarios, in a synthetic orbital station.

[Watch the demo](https://github.com/OptimistOtaku/greg/releases/tag/v0.1.0-demo) · [Architecture](https://github.com/OptimistOtaku/greg/blob/main/docs/product.md) · [Evaluation evidence](https://github.com/OptimistOtaku/greg/blob/main/artifacts/gemini-evaluation.json)

### [SIETCH](https://github.com/OptimistOtaku/Sietch) · Memory when the connection disappears

An edge-memory prototype for simulated rovers and drones using **Qdrant Edge, local vision-language models, and semantic + spatial retrieval**. Robots retain observations and conclusions locally, then prioritize what to transmit under tight communication budgets.

Includes evidence-linked recall, signed commands, fleet deduplication, and a SQLite write-ahead log for recovering unflushed memory.

### [PITWALL](https://github.com/OptimistOtaku/trackshift-26) · Motorsport decisions under uncertainty

A Formula 1 telemetry and strategy project built with **FastF1 and statistical learning**, presented through an offline interactive console. Models lap pace, fresh-tyre value, and the traffic conditions that can make an undercut fail.

My role: **AI & Telemetry Engineer**—physics identification, telemetry pipelines, and model benchmarking. The repository reports **12% lower lap-pace RMSE than persistence** on its reused evaluation set, with uncertainty intervals and evaluation limits documented.

### [Ego Gate](https://github.com/OptimistOtaku/ego-gate) · What is worth remembering?

My continual-learning research preview explores replay selection using **uncertainty and influence signals**. Includes a preprint, a small class-incremental experiment, per-seed results, and comparisons against replay baselines.

Part of **The Stimulus**, my longer-term exploration of selective learning and memory. Current evidence is a small-scale proof of concept.

[Read the preprint](https://github.com/OptimistOtaku/ego-gate/blob/main/ego_gate_paper.pdf) · [Inspect the experiments](https://github.com/OptimistOtaku/ego-gate/tree/main/experiments)

### [aegis-env](https://github.com/OptimistOtaku/aegis-env) · Training agents to respond to AI safety incidents

A Python reinforcement-learning environment for simulated incident response: triage anomalies, contain cascading failures, patch affected components, and validate recovery. Includes adversarial log noise, operational side effects, a FastAPI interface, and a deterministic baseline.

## Tools I work with

**Languages:** Python · Rust · TypeScript · JavaScript · SQL  
**AI & data:** continual-learning experiments · agent tooling / MCP · FalkorDB · Qdrant · PostgreSQL · DuckDB · SQLite  
**Applications & infrastructure:** React · Next.js · FastAPI · Three.js · Docker · Kestra

## What I'm exploring

How should an agent decide what to remember, when to revise a belief, and when to ask for help?

That question connects my interests in **continual learning, uncertainty calibration, agent safety, and human–AI interaction**—and the systems I build to test them.

[Explore my repositories →](https://github.com/OptimistOtaku?tab=repositories)
