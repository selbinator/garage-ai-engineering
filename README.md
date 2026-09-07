# garage-ai-engineering
The thesis of this repo is that useful AI systems should be engineered from the simplest architecture that can reliably solve the problem.

That means using the smallest sufficient model, and preferring deterministic methods before generative ones. Rules, search, structured retrieval, classifiers and conventional software should do the work when they can. Larger models, agents and more complex orchestration should be introduced only when simpler approaches demonstrably fail.

Complexity should therefore be evidence-driven. Each additional component must solve a measured limitation, not simply reflect current AI fashion. The objective is not to maximise model size or architectural sophistication, but to maximise useful capability per unit of cost, latency, operational burden and risk.

Enterprise AI also requires governed access. Retrieval and generation must respect source permissions, ownership and security boundaries rather than treating all available information as equally accessible.

Failure must be measurable. Systems should expose where retrieval, reasoning, generation or validation fail, and provide enough instrumentation to improve them systematically.

The result is an engineering approach focused on economical, explainable and progressively scalable AI systems rather than impressive but fragile demonstrations.
