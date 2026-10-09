# Hi, I'm Luan Dinh

Computer Science (AI) student at DePaul University and AI engineer who ships rigorously engineered systems. I'm building a self-growing, brain-inspired AI engine on spiking neural networks, local LLM infrastructure, and the agent-orchestration workflow behind them, including custom Claude Code skills and hooks that keep AI agents coordinated and verified.

Focus: honest metrics, tested code, software that ships.

## Projects

### Spiking Neural Data Lake (SNDL) · Python · private repo, available on request

- Brain-inspired AI engine that grows its own neurons: when its spiking network cannot solve a problem it adds neurons, passes them through a separate "liquid" reservoir network so they learn how they relate to what it already knows, then runs a sleep cycle that prunes and saves the result to one permanent data store it can recall from.
- System design: two cooperating networks inside a single durable data lake; a safety layer that sends every robot-arm (SO-101) command through one checked path with an emergency stop; and design rules checked automatically in CI.
- Built in parallel by a team of AI agents I direct: one engine component per agent on its own git branch, peer review before merge, one integrator, and a full test battery on every merged batch. The final milestone is a whole-engine test that removes each connection to prove it is needed.
- ~390 automated self-checks plus pytest; GitHub Actions CI on Ubuntu and Windows with free-threaded Python 3.14; 350+ tagged releases.

### [agent-board](https://github.com/PVLuanDinh/agent-board) · Claude Code skill · Python, open source (MIT)

- Claude Code skill that coordinates multiple AI agents across sessions and tools: append-only hash-chained message board, file claims, blind peer review, and an anti-gaming scorer that re-runs verification instead of trusting agent reports.
- Configures custom skills and harness hooks to improve AI workflows, e.g. a Stop hook that keeps a lead agent working instead of idling, installed into any Claude account with one idempotent command; stdlib-only with a reachable-red self-check suite.

### [Claude Odysseus Optimizer](https://github.com/PVLuanDinh/claude-odysseus-optimization) · Python

- Builds a unified, queryable knowledge graph across multiple codebases (god nodes, community detection, inferred cross-repo bridge edges) via AST parsing and static analysis.
- Returns scoped subgraphs sized for LLM context windows instead of raw file dumps.

### Claude Code Router · Local LLM infrastructure

- Self-hosted router that redirects AI-coding-client traffic to a local Ollama model instead of the cloud; installed globally as a CLI and run live for cost control and privacy.

### Agentic Build-Loop Engineering · Methodology

- Repeatable research → build → verify (CI) → ship loops, one safe slice per cycle: multi-agent orchestration routing subtasks by model tier, persistent cross-session memory, and knowledge-graph navigation. Nothing merges without passing the full CI gate.

## Skills

- **Languages:** Python (Advanced), Java, JavaScript/TypeScript, C++, SQL, Assembly
- **AI / Machine Learning:** neural networks from scratch, deep learning, TensorFlow, PyTorch, snnTorch, spiking neural networks & neuromorphic computing, surrogate-gradient training, STDP, NLP & chatbots, GPU/CUDA training, fp16 mixed precision
- **LLMs & Agents:** local LLM serving (Ollama), LLM request routing, retrieval-augmented context, multi-agent orchestration, custom AI skills & hooks (Claude Code), AI build loops, prompt engineering
- **Software Engineering:** system design & architecture, safety-critical control paths, stdlib-only tool design, GitHub Actions CI matrices, pytest, ruff, pre-commit, test-driven development, semantic versioning & releases, packaging (PyInstaller, Inno Setup), software product testing & QA
- **Web & APIs:** React, TypeScript, HTML, CSS, REST APIs, OpenAI API integration
- **Tooling:** Git/GitHub, knowledge graphs & static analysis, VS Code, Blender scripting (sketch → 3D), Adobe Creative Cloud

## Contact

Chicago, IL · reach me through [GitHub](https://github.com/PVLuanDinh)
