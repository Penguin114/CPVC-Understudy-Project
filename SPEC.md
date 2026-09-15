# TARGET: today's build

Thing: A one-page Java Data Structure Visualizer that accepts implementation and usage code, then animates the code’s actual execution.
Audience: First-year Computer Science students who want to understand program execution and debug their data-structure implementations visually.
Requirements: Support linked lists, stacks, queues, searching, and recursion. Include Start and Stop controls, require both code inputs, and use a clear modular architecture so new structures can reuse the existing execution, state-tracking, controls, and visualization resources.
Guardrails: Static browser code only; no external services, keys, accounts, runtime AI, or private data. Withhold visualization only for a definite compiler error or runtime exception. Preserve the example and publishing setup; work on a branch and wait for human review before shipping.
Experience: Keep two vertically stacked Java inputs on the left and the visualization on the right. Select a readable view for each concept, such as nodes and arrows, stack or queue lanes, recursive call frames, and search comparisons.
Test: I can run every supported concept, observe its actual state changes, stop a nonterminating execution, and verify that incomplete or exception-producing code shows no visualization. I can also add a new structure without rewriting the shared execution and interface systems.
