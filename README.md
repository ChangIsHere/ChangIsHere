# Chang Zhou

**Computer Science at UW–Madison · Backend systems and AI agents**  
B.S. in Computer Science, expected May 2027

## Selected Work

### [ARFA](https://github.com/ChangIsHere/ARFA) · Model routing for coding agents

I led the design, implementation, and evaluation of a router that uses the result of a terminal command to choose the model for the next step. I built the evaluation harness to compare routing policies on the same tasks and measure both task success and end-to-end cost.

On **100 held-out InterCode NL2Bash tasks**, the Gemma 4B/12B pairing used **43.5% fewer calls to the slower model** and **21.5% less wall-clock time**, with task success **9 percentage points higher** than the always-slow baseline. The trade-offs varied across model pairings.

[v0.1.0 artifact](https://github.com/ChangIsHere/ARFA/tree/v0.1.0) · [Experiment results](https://github.com/ChangIsHere/ARFA/blob/v0.1.0/docs/EXPERIMENT_RESULTS.md) · [Reproducibility guide](https://github.com/ChangIsHere/ARFA/blob/v0.1.0/docs/REPRODUCIBILITY.md)

### [Portrait IQ](https://github.com/nehasrinivasula/portrait-iq) · GE HealthCare-sponsored capstone

I worked on a team building diagnostic software for field engineers who service patient-monitoring systems. Two of my merged contributions:

- [PR #41 · Diagnostic run recovery](https://github.com/nehasrinivasula/portrait-iq/pull/41) — restored the original diagnostic run, including its status and results, after signing back in within the same browser session.
- [PR #38 · Time-range filtering](https://github.com/nehasrinivasula/portrait-iq/pull/38) — added time presets and a custom calendar range, with tests for validation and UTC conversion.

### [NodeTree](https://www.nodetree.io) · Visual workspace for research

Contributed to a visual editor that lets users organize research and AI-assisted work in branching trees.

## Technical Focus

- **Backend & systems** · Python, Java, FastAPI, Spring Boot, SQL, Docker, Kubernetes
- **AI & evaluation** · LLM agents, model routing, benchmarking, reproducible experiments
- **Product engineering** · TypeScript, React, Next.js, API integration, automated testing

## Contact

- Email: [ChangZhou1105@gmail.com](mailto:ChangZhou1105@gmail.com)
