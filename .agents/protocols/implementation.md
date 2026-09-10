# Implementation Protocol

## Rule

Code follows specification. Specification follows product and educational decisions.

## Pipeline

APPROVED SPEC → PLAN → IMPLEMENT → TEST → REVIEW → FIX → VERIFY → COMMIT

## Before Coding

OpenCode must inspect:
- repository state
- relevant specification
- architecture
- dependencies
- existing tests

## During Coding

Do not:
- introduce unnecessary dependencies
- duplicate existing systems
- alter unrelated features
- weaken safety constraints
- invent requirements

## Verification

When applicable run:
- typecheck
- lint
- unit tests
- integration tests
- build
- manual smoke test

## Completion

Implementation is complete only when acceptance criteria pass, relevant tests pass, no known critical regression exists, and the diff has been reviewed.
