# Semantic Kernel

## Essence

Semantic Kernel is a middleware-like agent framework that puts a shared kernel at the center of models, plugins, connectors, and agent capabilities.

## Architectural Worldview

This system assumes that useful AI applications need a central runtime spine. Instead of letting every tool and model integration sprawl independently, it routes capabilities through a kernel.

## Center of Gravity

Kernel composition, plugins, connectors, and shared runtime services.

## Complexity Lives In

- Plugin design
- Connector abstraction
- Kernel composition
- Cross-language integration

## Primary Substrate

- Kernel
- Plugins
- Connectors
- Services

## Trust Model

- Kernel-mediated capabilities
- Connector abstraction
- Runtime composition

## Memory Model

Memory is present, but not as the first dramatic architectural signal. The stronger signal is capability composition through a central runtime layer.

## Human Role

The human is a runtime designer and integrator composing services and plugins into a larger application.

## Playfulness / Surprise

The elegant move is how calmly infrastructural it is. The kernel becomes the cognitive spine, and agents start to look like one client of a broader composition layer.

## What It Makes Easy

- Integrating AI capabilities into application runtimes
- Standardizing access to services and plugins
- Building agent systems over a shared capability center

## What It Makes Awkward

- Getting a vivid visible agent loop immediately
- Pretending middleware complexity is not architecture

## Failure Modes

- Connector sprawl
- Plugin indirection
- Middleware heaviness

## What It Refuses

- Treating agent behavior as only prompt choreography
- Direct ad hoc integration with every service surface
- Separating capability composition from runtime architecture

## Core Tension

Its strength is giving the system a central programmable spine for capabilities. Its tradeoff is that this middleware-centric shape can feel more infrastructural than immediately agentic.

## Archetype

The Tool Router

## Representative For

- Kernel-centric agent middleware
- Plugin-and-connector capability spine

## Related Concepts

- [[kernel-as-cognitive-spine]]
- [[plugins-as-capabilities]]
- [[connector-abstraction]]
- [[middleware-for-agency]]

## Open Questions

- Where does Semantic Kernel feel most alive as an agent framework rather than as AI middleware?
- How much of the long-term architectural value comes from the kernel abstraction versus the surrounding connector ecosystem?

## Animal or Transport

Spider. It sits at a central hub, sensing and coordinating many connected strands of capability.

## Sources

- https://learn.microsoft.com/en-us/semantic-kernel/
- https://learn.microsoft.com/en-us/semantic-kernel/agents/kernel/
- https://learn.microsoft.com/en-us/semantic-kernel/concepts/semantic-kernel-components
