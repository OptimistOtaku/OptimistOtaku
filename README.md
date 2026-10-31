<p align="center">
	<img src="./assets/profile-banner.svg" width="100%" alt="Aditya Singh — Ideas into systems. AI systems, agent memory, and continual learning." />
</p>

<p align="center">
	<a href="https://recall-loop-demo.onrender.com"><img src="https://img.shields.io/badge/TRY%20IT-RECALL%20LOOP-141B2D?style=for-the-badge&logo=render&logoColor=141B2D&labelColor=8BE5D5" alt="Try Recall Loop on Render" /></a>
	<a href="https://github.com/OptimistOtaku/ego-gate/blob/main/ego_gate_paper.pdf"><img src="https://img.shields.io/badge/RESEARCH-EGO%20GATE-141B2D?style=for-the-badge&labelColor=C4B5FD" alt="Read the Ego Gate research preprint" /></a>
	<a href="https://github.com/kestra-io/blueprints/pulls?q=is%3Apr+is%3Amerged+author%3AOptimistOtaku"><img src="https://img.shields.io/badge/10%20PRs%20MERGED-KESTRA-1F232C?style=for-the-badge&logo=github&logoColor=200062&labelColor=CDC5FF" alt="Kestra milestone: 10 pull requests merged" /></a>
</p>

<p align="center">
	<a href="#-selected-builds">Projects</a> ·
	<a href="#-research--the-questions-behind-the-code">Research</a> ·
	<a href="#-milestones-with-evidence">Achievements</a> ·
	<a href="https://github.com/OptimistOtaku?tab=repositories">All repositories</a>
</p>

## 👋 I'm Aditya

I build AI systems and the interfaces that make them useful. I'm especially interested in **memory, uncertainty, and continual learning**: what should a system remember, when should it change its mind, and how can we inspect the evidence behind its decisions?

That curiosity takes me from coding-agent memory and simulated robot crews to motorsport telemetry and research experiments. I enjoy taking an idea all the way through **implementation, evaluation, and an experience people can explore**.

## 🚀 Selected builds

### Recall Loop / bunch
**Memory for coding agents. A knowledge space you can actually inspect.**

<a href="https://recall-loop-demo.onrender.com">
	<img src="https://raw.githubusercontent.com/OptimistOtaku/recall-loop/main/screenshots/observatory-public.png" width="100%" alt="bunch, the Recall Loop application: an interactive knowledge graph with memory and evidence panels" />
</a>

A local-first application for carrying useful knowledge between coding sessions. Explore an editable **3D knowledge graph**, correct memories, connect prerequisites and contradictions, and retrieve the source evidence behind a lesson.

**Python · FastAPI · SQLite · Qdrant Edge · Three.js · MCP**

[**↗ Try the Render demo**](https://recall-loop-demo.onrender.com) · [Source](https://github.com/OptimistOtaku/recall-loop) · [Deployment checks](https://github.com/OptimistOtaku/recall-loop/blob/main/evaluation/deployment.json)

<sub>The hosted demo uses isolated sample data. Free hosting may sleep; demo edits are temporary.</sub>

<table>
<tr>
<td width="50%" valign="top">
<h3>🛰️ GREG</h3>
<a href="https://github.com/OptimistOtaku/greg"><img src="https://raw.githubusercontent.com/OptimistOtaku/greg/main/artifacts/orbital-station.png" width="100%" alt="GREG's orbital station simulation and mission-control interface" /></a>
<p><strong>Shared knowledge. Distributed action.</strong></p>
<p>A simulated robot crew with shared graph memory: task dependencies, observations, evidence, and recovery actions live in FalkorDB. Gemini agents act through validated MCP tools.</p>
<p><code>Python</code> <code>FalkorDB</code> <code>MCP</code> <code>React / Three.js</code></p>
<p><a href="https://github.com/OptimistOtaku/greg">Explore the project ↗</a> · <a href="https://github.com/OptimistOtaku/greg/releases/tag/v0.1.0-demo">Watch demo</a></p>
</td>
<td width="50%" valign="top">
<h3>🔭 SIETCH</h3>
<a href="https://github.com/OptimistOtaku/Sietch"><img src="https://raw.githubusercontent.com/OptimistOtaku/Sietch/main/docs/img/hero.jpg" width="100%" alt="SIETCH's simulated Mars rover and scout drone with a memory interface" /></a>
<p><strong>Memory when the signal disappears.</strong></p>
<p>Edge memory for simulated rovers and drones. Local models recall observations by meaning and location, then choose what deserves the limited bandwidth back to mission control.</p>
<p><code>Qdrant Edge</code> <code>Local VLMs</code> <code>Python</code> <code>Three.js</code></p>
<p><a href="https://github.com/OptimistOtaku/Sietch">Explore the project ↗</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🏎️ PITWALL</h3>
<p><strong>Race strategy, with uncertainty in view.</strong></p>
<p>Formula 1 telemetry, lap-pace forecasts, tyre-value models, and undercut analysis in an offline interactive console. My role: <strong>AI &amp; Telemetry Engineer</strong>, covering physics identification, data pipelines, and benchmarking.</p>
<p><code>Python</code> <code>FastF1</code> <code>Statistical learning</code></p>
<p><a href="https://github.com/OptimistOtaku/trackshift-26">Explore the project ↗</a></p>
</td>
<td width="50%" valign="top">
<h3>🛡️ aegis-env</h3>
<p><strong>A training ground for AI incident response.</strong></p>
<p>A reinforcement-learning environment where agents triage anomalies, contain cascading failures, patch components, and validate recovery—with adversarial logs and operational side effects.</p>
<p><code>Python</code> <code>FastAPI</code> <code>Reinforcement learning</code></p>
<p><a href="https://github.com/OptimistOtaku/aegis-env">Explore the project ↗</a></p>
</td>
</tr>
</table>

## 🧠 Research · the questions behind the code

### Ego Gate — what is worth remembering?

My research preview explores **uncertainty- and influence-based replay selection** for continual learning: deciding which experiences to retain under a fixed memory budget.

Part of **The Stimulus**, my longer-term exploration of selective learning. The repository includes a preprint, a small class-incremental experiment, per-seed results, and replay-baseline comparisons. Current evidence is a small-scale proof of concept.

[![Read the preprint](https://img.shields.io/badge/READ%20THE%20PREPRINT-EGO%20GATE-C4B5FD?style=for-the-badge&labelColor=141B2D)](https://github.com/OptimistOtaku/ego-gate/blob/main/ego_gate_paper.pdf)
[![Explore experiments](https://img.shields.io/badge/EXPLORE-EXPERIMENTS-8BE5D5?style=for-the-badge&logo=github&logoColor=white&labelColor=141B2D)](https://github.com/OptimistOtaku/ego-gate/tree/main/experiments)

**Questions I keep returning to:** How do we reduce forgetting? How should an agent represent doubt? How can people inspect and correct an AI system's memory?

## ✨ Milestones with evidence

| Work | Result |
| --- | --- |
| 🧩 **Recall Loop / bunch** | Published a [Render demo](https://recall-loop-demo.onrender.com), with recorded checks for hybrid search, graph editing, and visitor isolation. |
| 🛰️ **GREG** | [Three live-model demonstrations](https://github.com/OptimistOtaku/greg/blob/main/artifacts/gemini-evaluation.json) completed **7/7 objectives each**, including corridor blockage and robot failure in authored simulation scenarios. |
| 🏎️ **PITWALL** | Reported **12% lower lap-pace RMSE** than persistence across 6,831 scored laps on a [reused evaluation set](https://github.com/OptimistOtaku/trackshift-26#-validated-benchmark-results). |
| ⚡ **Cap** | A merged Rust optimization delivered **5.61× faster caption synchronization** in the [one-hour / 60-trimmed-clip local benchmark](https://github.com/CapSoftware/Cap/pull/2956). |

## 🛠️ My toolkit

<p>
	<img src="https://skillicons.dev/icons?i=python,rust,ts,js,react,nextjs,fastapi,threejs,postgres,sqlite,docker,git&perline=6" alt="Python, Rust, TypeScript, JavaScript, React, Next.js, FastAPI, Three.js, PostgreSQL, SQLite, Docker, and Git" />
</p>

**AI & data:** agent tooling / MCP · Qdrant · FalkorDB · DuckDB · continual-learning experiments  
**Engineering:** API design · data workflows · performance profiling · interactive visualization

---

**🌱 Giving back:** I contribute workflow blueprints to [Kestra](https://github.com/kestra-io/blueprints/pulls?q=is%3Apr+is%3Amerged+author%3AOptimistOtaku) and Rust performance improvements to [Cap](https://github.com/CapSoftware/Cap/pulls?q=is%3Apr+is%3Amerged+author%3AOptimistOtaku).

<p align="center"><strong>Curious about memory, learning, and the systems we can build around them.</strong><br /><a href="https://github.com/OptimistOtaku?tab=repositories">Explore my work ↗</a></p>
