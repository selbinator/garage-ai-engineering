# garage-ai-engineering
The thesis of this repo is that useful AI systems should be engineered from the simplest architecture that can reliably solve the problem.

That means using the smallest sufficient model, and preferring deterministic methods before generative ones. Rules, search, structured retrieval, classifiers and conventional software should do the work when they can. Larger models, agents and more complex orchestration should be introduced only when simpler approaches demonstrably fail.

Complexity should therefore be evidence-driven. Each additional component must solve a measured limitation, not simply reflect current AI fashion. The objective is not to maximise model size or architectural sophistication, but to maximise useful capability per unit of cost, latency, operational burden and risk.

Enterprise AI also requires governed access. Retrieval and generation must respect source permissions, ownership and security boundaries rather than treating all available information as equally accessible.

Failure must be measurable. Systems should expose where retrieval, reasoning, generation or validation fail, and provide enough instrumentation to improve them systematically.

The result is an engineering approach focused on economical, explainable and progressively scalable AI systems rather than impressive but fragile demonstrations.


## Project Map

Garage AI Engineering is an incremental programme. Each project must produce independently useful, defensible engineering evidence before the next layer of complexity is added.

Repositories are created when implementation starts. Planned work is deliberately shown here before it is built; Planned does not mean implemented or demonstrated.

| Module | Repository | Engineering evidence | Status |
| --- | --- | --- | --- |
| 0 | `garage-ai-engineering` | Portfolio index, engineering principles, common standards and reproducible workbench | 🚧 In progress |
| 1 & 5 | `sow-review` | End-to-end AI application evolving into the flagship SOW Review product | 🟡 Planned |
| 2 | `transformer-from-scratch` | Tokenisation, attention, training and inference implemented from first principles | 🟡 Planned |
| 3 | `training-evaluation-lab` | Reproducible training experiments, evaluation and failure analysis | 🟡 Planned |
| 4 | `lora-qlora-finetuning` | Fine-tuning an open model with measured before/after performance | 🟡 Planned |
| 6 | `retrieval-rag-benchmark` | Direct, metadata, lexical and vector retrieval compared using common evaluation data | 🟡 Planned |
| 7 | `ai-decision-router` | Explicit routing and orchestration using deterministic and model-based decisions | 🟡 Planned |
| 8 | `MCP-adaptor` | Model Context Protocol Adaptor and REST/MCP Parity benchmark | 🟡 Planned |
| 9 | `decisiontrace-evals` | Evaluation, traceability, regression testing and release gates | 🟡 Planned |
| 10 | `secure-ai-deployment` | Production-style serving, security, telemetry and operational controls | 🟡 Planned |
| 11 | `garage-cloud` | Container Infrastructure as Code on multiple recycled hardware devices, stack mapped to major cloud providers | 🟡 Planned |
| 12 | `brownfield-ai-rescue-drill` | Repair Broken AI stack in 8 hour drill| 🟡 Planned |
| 13 | `garage-inference-cluster` | Multi-node local inference, routing, saturation and graceful degradation | 🟡 Planned |
| 14 | `model-cost-governor` | Quality, latency and cost-aware model routing | 🟡 Planned |
| 15 | `fde-capstone` | Customer-style discovery, implementation, deployment and handover | 🟡 Planned |

## Programme progression

The programme progresses from a working application through model mechanics, training, fine-tuning, retrieval, orchestration, evaluation, production deployment and systems engineering to a Forward Deployed Engineer capstone.

Complexity is earned through measurement rather than assumed in advance.
