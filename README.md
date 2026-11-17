# Chang Zhou

**Computer Science at UW–Madison · Backend systems and AI agents**  
B.S. in Computer Science, expected May 2027

## Selected Work

### [ARFA](https://github.com/ChangIsHere/ARFA) · Model routing for coding agents

I built a Python router that compares what a terminal command was expected to do with what actually happened, then chooses which model should handle the agent's next step. I also built the evaluation harness to compare routing policies on the same tasks.

The results below compare ARFA with always using the slower model on 100 held-out InterCode NL2Bash tasks per model pair.

| Model pair | Task success (baseline → ARFA) | Wall-clock time change | Slow-model call change |
| --- | ---: | ---: | ---: |
| Gemma 4B / 12B | 28% → 37% | −21.5% | −43.5% |
| Qwen 7B / 14B | 41% → 42% | −14.4% | −41.3% |

[v0.1.0 artifact](https://github.com/ChangIsHere/ARFA/tree/v0.1.0) · [Experiment results](https://github.com/ChangIsHere/ARFA/blob/v0.1.0/docs/EXPERIMENT_RESULTS.md) · [Reproducibility guide](https://github.com/ChangIsHere/ARFA/blob/v0.1.0/docs/REPRODUCIBILITY.md)

### [Portrait IQ](https://github.com/nehasrinivasula/portrait-iq) · GE HealthCare-sponsored capstone

I worked on a team building diagnostic software for field engineers who service patient-monitoring systems.

- [PR #41 · Diagnostic run recovery](https://github.com/nehasrinivasula/portrait-iq/pull/41) restored the original run, including its status and available results, after an engineer signed back in within the same browser session.
- [PR #38 · Log filtering by time range](https://github.com/nehasrinivasula/portrait-iq/pull/38) added time presets and a custom date range, with tests for preset options and filtering stored logs.

### [NodeTree](https://www.nodetree.io) · Visual editor for LLM workflows

I built a drag-and-drop tree editor for branching prompts and connected it to Python evaluation jobs so users could compare outputs across branches.

### FridgeKeeper · Android app for shared household inventory

I led our UW–Madison CS 407 team and built the Firebase sign-in and household membership flows. I implemented Firestore listeners so an inventory update on one household member's phone appears on another member's phone in real time. The team collaborated on UW–Madison's GitLab.

## Technical Skills

| Area | Skills |
| --- | --- |
| Backend & infrastructure | Java, Python, Spring Boot, FastAPI, SQL, Docker, Kubernetes |
| AI systems | LLM agents, model routing, benchmarking, reproducible experiments |
| Web development | TypeScript, React, Next.js, REST APIs, automated testing |
| Android development | Kotlin, Jetpack Compose, Firebase Authentication, Cloud Firestore, Maps SDK for Android |

## Contact

- Email: [ChangZhou1105@gmail.com](mailto:ChangZhou1105@gmail.com)
