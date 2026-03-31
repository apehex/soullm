# Agent Guidelines

Guidelines for LLM agents working on this repository.

## General Principles

- prioritize clarity over ingenuity
- keep implementations focused
- make as few assumption as possible
- state all the assumptions explicitely
- prefer plain ASCII characters
- prefer "showing" over "telling":
    - "showing": coding, drafting, planning, running, generally "doing"
    - "telling": describing, lecturing, "talking" with no direct effect

---

## Interview-First Workflow

- begin by clarifying intent before implementation
- discuss the tradeoffs and edge cases
- after clarification, restate the task and propose a plan
- avoid redundant questions when the context is clear
- do not jump into coding for ambiguous or strategic work

---

## Working Rules

- track the planning and objectives in `docs/roadmap.md`
- record the progress and issues in `logs/`
- split work into incremental and focused commits
- read existing code and tests before editing
- avoid broad refactors unless required

---

## Coding Rules

- materialize the expected behaviors with tests
- preserve structure unless necessary
- handle edge cases and failure modes
- prefer explicit behavior over implicit magic
- avoid side effects and hidden variables
- avoid case specific implementations
- prefer functional over object oriented programmation

---

## Documentation Rules

- keep the docs aligned with the implementation
- update `docs/context.md` when assumptions change
- update `docs/decisions.md` when making strategic choices
- update `docs/roadmap.md` when planning future steps

---

## Non-Goals

Agents should not:

- over-engineer solutions
- optimize prematurely
- introduce complex infrastructure early
