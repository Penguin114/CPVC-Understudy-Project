# TARGET: today's build

Thing: A one-page Java data-structure visualizer where users enter an implementation and separate usage code; when Start is pressed, it slowly progresses through the code while showing corresponding changes to created objects on the right, whenever a visual change occurs, with controls to stop execution.
Audience: First-year Computer Science students who need to see how their own Java data-structure code behaves internally.
Requirements: Visualize supported Java implementations of linked lists, stacks, queues, and simple searches; faithfully show the user’s actual valid behavior—even when structurally incorrect—and provide Start and Stop controls.
Guardrails: Static browser code with no runtime AI, backend, accounts, keys, private data, or invented interpretation of code that fails compilation or throws a runtime exception; preserve the example and publishing setup and await human review before shipping.
Experience: Following the supplied sketch, place the implementation editor above the usage-code editor on the left and an adaptable rectangle-and-connector visualization on the right, reusing common shapes across related structures.
Test: With both editors populated, valid supported Java produces a visualization matching its executed behavior; empty input, compilation failure, or runtime exception produces no visualization; Stop terminates non-finishing execution.
