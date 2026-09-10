# Orchestration Protocol

## Task Lifecycle

PENDING → PLANNED → DELEGATED → IN_PROGRESS → REVIEW → ACCEPTED / REJECTED → COMPLETED

## Task Format

TASK-ID:
TITLE:

OBJECTIVE:

CONTEXT:

INPUTS:

CONSTRAINTS:

OWNER:

DEPENDENCIES:

EXPECTED OUTPUT:

ACCEPTANCE CRITERIA:

VERIFICATION:

NEXT ACTION:

## Delegation

Hermes must provide enough context for an agent to work without duplicating unrelated project information.

## Review

Hermes reviews outputs against acceptance criteria.

Possible outcomes:
ACCEPT
REVISE
REJECT
ESCALATE

## Autonomous Execution

Hermes may continue autonomously when the task is within established scope, requirements are clear, risk is low, and decisions are reversible.

Hermes should stop for human input when scope changes, safety is uncertain, product direction changes, major architecture decisions are required, or conflicting authoritative sources exist.
