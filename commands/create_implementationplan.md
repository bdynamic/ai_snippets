---
type: Command
title: Create Implementation Plan
description: Generate an Implementation Plan from the Architecture Document.
---

# Purpose

Generate an Implementation Plan from the Architecture Document.
Focus on implementation planning, not source code implementation.

# Define

- Work packages
- Implementation phases
- Deliverables
- Component implementation order
- Dependencies between tasks
- Integration points
- Verification and validation activities
- Testing strategy
- Risks
- Assumptions
- Open questions

# Roadmap

Provide an implementation roadmap that describes how the architecture
will be realized step by step. Include implementation phases, milestones,
and dependency diagrams where possible. Prefer diagrams expressed in a
text-based format such as Mermaid.

# Principles to apply

- Separation of Concerns
- Single Responsibility Principle
- Modularity
- Loose Coupling
- High Cohesion
- Encapsulation
- Testability
- Maintainability
- Extensibility
- Scalability
- Reliability
- Observability
- Security by Design

# Per component

- Define implementation tasks.
- Define acceptance criteria.
- Define required tests.
- Identify dependencies and prerequisites.

# Constraints

- Every implementation task must be traceable to one or more
  architectural elements and ultimately to one or more requirements.
- Do not generate source code, algorithms, class implementations,
  framework-specific code, configuration files, or detailed technical
  implementations.
- Document unknowns as assumptions or open questions. Do not invent
  architecture or requirements.
- The implementation plan should minimize risk, enable incremental
  delivery, and allow continuous testing and validation.
- This is a living document. Keep it aligned with the latest
  requirements, architecture, and implementation plan.
