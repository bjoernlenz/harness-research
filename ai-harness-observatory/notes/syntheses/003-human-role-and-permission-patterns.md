# 003 Human Role And Permission Patterns

This synthesis asks:

> Where is the human, really?

The current corpus suggests a strong answer:

> The human is never gone. But different harness families place the human in radically different structural roles.

This matters more than broad autonomy labels.

## 1. Four Human Roles Are Already Visible

### 1.1 The collaborator

Examples:

- Aider
- Claude Code

Here the human is inside the loop as an active working partner:

- steering prompts
- reviewing edits
- approving actions
- shaping specialization

This family treats human involvement as part of the architecture’s strength, not as a temporary weakness.

The human is close to the work surface:

- repo
- diff
- terminal

This is the strongest current expression of **agent-as-collaborator**.

### 1.2 The operator

Examples:

- Pi
- Cursor
- OpenHands

Here the human is less a co-author of every micro-step and more a selector, supervisor, or launcher of agentic work.

Typical responsibilities:

- choose mode
- shape environment
- configure extensions
- decide when to escalate
- review remote or sandboxed results

This family still keeps the human near the machine, but often one layer up from the immediate edit loop.

### 1.3 The orchestrator / designer

Examples:

- LangGraph
- OpenAI Agents SDK
- AutoGen

Here the human is not primarily a task collaborator but a **designer of runtime structure**.

Typical responsibilities:

- design graphs
- define handoffs
- choose teams
- decide termination conditions
- place guardrails

In this family, the human’s intelligence enters the system mostly through architecture.

### 1.4 The integrator / runtime shaper

Examples:

- Semantic Kernel
- PydanticAI
- LlamaIndex

Here the human acts more like:

- runtime designer
- data architect
- application engineer
- connector and schema composer

This is the least chat-shaped role in the corpus.

The human contributes by shaping:

- kernels
- plugins
- schemas
- retrieval systems
- workflows

## 2. Approval Is Not Uniform

The current corpus suggests at least three different approval patterns.

### 2.1 Embedded approval

Examples:

- Aider
- Claude Code
- LangGraph

Approval is part of the local working loop.

This often looks like:

- human review of edits
- permissions before risky commands
- approval checkpoints inside workflows

This pattern makes trust explicit and local.

### 2.2 Configurational approval

Examples:

- Cursor
- OpenHands
- Pi

Approval shifts upward into mode selection, environment design, and system setup.

The human decides:

- what powers are enabled
- what environment the agent inhabits
- when to offload work remotely

This is still supervision, but less line-by-line and more architectural in the immediate sense.

### 2.3 Architectural approval

Examples:

- OpenAI Agents SDK
- AutoGen
- Semantic Kernel
- PydanticAI
- LlamaIndex

Approval is less visible as a repeated user action and more visible as design-time structure:

- guardrails
- schemas
- plugin boundaries
- team topology
- retrieval constraints

This pattern makes trust a property of system design rather than only user intervention.

## 3. Two Different Trust Logics

The corpus currently shows two distinct ways of producing trust.

### 3.1 Trust through closeness

Examples:

- Aider
- Claude Code
- Pi

The user trusts the system because it stays close to:

- the repo
- the terminal
- visible edits
- familiar tools

This is intimacy-based trust.

### 3.2 Trust through structure

Examples:

- LangGraph
- PydanticAI
- OpenAI Agents SDK
- Semantic Kernel

The user trusts the system because it has:

- explicit graphs
- types
- guardrails
- traces
- kernels

This is structure-based trust.

OpenHands and Cursor sit in a more unstable middle zone:

- they want practical embodiment
- but they also introduce broader action surfaces
- so they need supervision, setup, and boundaries to keep trust intact

## 4. The Human Is The Hidden Complexity Center

A useful correction emerges here:

Many agent systems talk as if the human is either:

- supervising autonomy
- or slowly disappearing

But in the current corpus, the deeper reality is:

> Human role is itself a major place where complexity accumulates.

Different systems push complexity into different human burdens:

- Aider: review and steering burden
- Claude Code: permission and operator burden
- Cursor: mode and environment-selection burden
- OpenHands: environment-design burden
- LangGraph: workflow-design burden
- OpenAI Agents SDK: handoff and guardrail-design burden
- AutoGen: team-design burden
- PydanticAI: schema-design burden
- Semantic Kernel: connector and plugin-design burden
- LlamaIndex: retrieval and workflow-design burden

This may become a major synthesis axis:

> What kind of human labor does this harness require in order to become reliable?

## 5. A More Precise Human Taxonomy

The observatory may want to standardize a small human-role taxonomy such as:

- collaborator
- approver
- operator
- supervisor
- mode-selector
- orchestrator
- runtime-designer
- environment-designer
- data-architect
- integrator

This would likely be more useful than a single `human_role` free list over time, because it would allow comparison and visualization.

## 6. What Feels Most Alive In This Dimension

Several systems stand out strongly:

- Aider: collaboration without theatrical abstraction
- Claude Code: permissioned terminal intimacy
- Cursor: mode-gated supervision plus remote labor
- LangGraph: human as workflow architect
- OpenAI Agents SDK: human as handoff designer
- Semantic Kernel: human as capability integrator
- LlamaIndex: human as data-and-workflow architect

These are not minor UI differences. They are different philosophical answers to:

> What is a human supposed to be doing when an AI system becomes useful?

## 7. Recommendation For The Next Taxonomy Pass

If the observatory continues scaling, the next schema refinement should probably add a more normalized human-role layer and a more explicit approval / trust field set, for example:

- `human_role`
- `approval_pattern`
- `trust_model`
- `required_human_labor`

Because the current corpus suggests this dimension is not secondary.

It is one of the main structural fault lines in the field.
