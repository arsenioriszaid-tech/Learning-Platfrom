# Decision 0001 — Project Foundation

## Status

Accepted

## Decision

Learning-Platfrom will be developed as a dedicated learning environment for children approximately 5–8 years old.

The platform initially focuses on supplemental and enrichment learning rather than claiming to replace school.

## Initial Educational Scope

The project will investigate:
- foundational academics
- reasoning
- problem solving
- curiosity
- communication
- creativity
- metacognition
- practical life skills
- character development
- religious learning as a separately governed track

## Architecture Principle

General education and religious education may coexist within the same product ecosystem, but their content governance and source-of-truth systems must remain distinct.

## AI Principle

AI will primarily support research, curriculum design, content generation, QA, software development, and orchestration.

Unrestricted AI interaction with children is excluded from the initial MVP.

## Development Principle

Hermes acts as the orchestrator.

OpenCode acts as the implementation agent.

Specialist agents provide research, curriculum, UX, safety, and adversarial review.

## MVP Principle

The MVP should validate learning quality before scale.

The first version should favor a small number of high-quality lessons, a small number of projects, a parent layer, and measurable learning outcomes over a large content library.

## Unresolved Questions

- exact target age segmentation
- educational philosophy
- initial curriculum scope
- religious curriculum scope
- technology stack
- product identity
- monetization
- deployment architecture
