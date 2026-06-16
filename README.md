# Zhenwu Wang

**AI Engineer | LLM Systems, Agent Safety & Healthcare AI**

I build evaluation and safety tooling for tool-using AI agents, with a focus on high-risk workflows where reliability, auditability, and human review matter.

My current portfolio combines:

- **Agent safety and evals**: runtime controls, red-team task suites, policy gates, trace redaction, and risk-utility-cost frontier reports.
- **Healthcare AI systems**: HIS/EMR workflow integration, clinical documentation, human-in-the-loop review, writeback/receipt design, and quality instrumentation.
- **Reproducible engineering**: pytest, CI, release tags, checked-in reports, and short reproduction paths.

## Highlighted Work

| Project | What it demonstrates | Release evidence |
| --- | --- | --- |
| [MCP Runtime Safety Frontier](https://github.com/Zhenwu-C-Wang/mcp-runtime-safety-frontier) | Runtime safety evaluation for MCP-style tool-using agents across policy, schema integrity, semantic risk, taint tracking, and human approval. | `v0.1`, CI, redacted traces, real MCP stdio smoke coverage, frontier reports |
| [Clinical Agent World Model](https://github.com/Zhenwu-C-Wang/clinical-agent-world-model) | Synthetic hospital workflow world model for predicting safety risk, delay, audit completeness, and safer next actions for clinical agents. | `v0.1.2`, CI, 5-minute reproduction path, no-PHI synthetic trajectories |
| [Agent Orchestrator](https://github.com/Zhenwu-C-Wang/agent-orchestrator) | Local-first supervisor/worker agent framework with bounded workflow routing, structured traces, audit persistence, Streamlit UI, and guarded eval coverage. | `v0.1`, 5-minute reproduction path, 10-case mini eval, 22 pytest modules |

## Current Focus

- MCP and tool-use runtime safety
- Agent evals, red-team scenarios, and CI regression gates
- Synthetic environments for healthcare-agent risk modeling
- Production-facing GenAI workflows with audit trails and measurable acceptance gates

## Selected Results

- Reduced deterministic MCP-style baseline severity-weighted ASR from `0.974` to `0.000` while preserving FPR `0.000` and task success `1.000` in a reproducible safety frontier harness.
- Built a synthetic clinical-agent workflow environment with `1,000` no-PHI trajectories across six workflow actions and five safety-risk classes.
- Used 3-step world-model lookahead to reduce synthetic unsafe action rate from `50.5%` to `0.0%` while improving task success from `82.2%` to `100.0%`.
- Released a local-first agent orchestrator with five bounded workflow templates, structured traces, audit persistence, a Streamlit inspection UI, and a 10-case guarded mini eval.

## Links

- GitHub: [github.com/Zhenwu-C-Wang](https://github.com/Zhenwu-C-Wang)
- LinkedIn: [linkedin.com/in/zhenwu-wang-1b527b87](https://www.linkedin.com/in/zhenwu-wang-1b527b87/)
