# Tameness Engineering

> **AI agents are not written. They are tamed.**

## What is Tameness Engineering?

**Tameness Engineering** is a proposed framework for building reliable AI agents by shaping their behavior over time.

Prompt engineering gives the model commands.  
Context engineering gives the model an environment.  
Harness engineering gives the model tools.  
Alignment engineering gives the model boundaries.  
**Tameness engineering gives the model habits.**

In real agent development, reliability rarely comes from one perfect prompt or one rigid set of constraints. It emerges through repeated observation, correction, reinforcement, and stabilization in a real environment.

## Core idea

Large language models are powerful, but their behavior is not fully deterministic. They can reason, plan, explain, imitate, use tools, and generate language — but these abilities are often “wild” before they are shaped into stable behavior.

Tameness Engineering is about turning raw capability into dependable agency.

It asks:

- When does the agent guess instead of verify?
- When does it overuse or underuse tools?
- When does it become overconfident?
- When does it lose the original goal in a long task?
- When should it ask, stop, refuse, verify, or escalate to a human?

The goal is not to weaken the model.  
The goal is to make its capability usable.

## The loop

Tameness Engineering follows an iterative loop:

```text
Observe -> Identify -> Correct -> Reinforce -> Stabilize -> Repeat
```

### 1. Observe

Watch the agent’s real behavior, not just its final answer.

Is it reasoning, or merely completing text?  
Is it verifying, or guessing?  
Is it following the workflow, or only imitating it?

### 2. Identify

Look for recurring failure patterns:

- hallucinated confidence
- tool misuse
- goal drift
- context neglect
- over-compliance
- premature execution
- failure to ask clarifying questions
- failure to stop at boundaries

### 3. Correct

Make small, careful changes.

Do not overfit the system with huge prompt patches. Adjust one thing at a time: context order, tool rules, checkpoints, examples, fallback behavior, or evaluation criteria.

### 4. Reinforce

When the agent behaves correctly, preserve that behavior.

A reliable action should become a default path.  
A good recovery pattern should become a habit.  
A useful workflow should become part of the agent’s operating environment.

### 5. Stabilize

The final goal is not a single successful run.

The goal is stable behavior across many real situations.

## Tameness vs. other engineering layers

| Layer | Main focus |
|---|---|
| Prompt Engineering | Commands |
| Context Engineering | Environment |
| Harness Engineering | Tools and execution framework |
| Alignment Engineering | Values and boundaries |
| **Tameness Engineering** | Behavioral habits under uncertainty |

## A simple metaphor

Harness engineering gives the horse a harness.  
Tameness engineering teaches the horse how to cooperate.

A harness can constrain movement.  
Tameness shapes behavior.

Both matter, but they are not the same.

## Why this matters

As AI agents gain access to tools, files, code, browsers, calendars, email, APIs, and enterprise systems, the key question changes:

It is no longer only:

> Can the model answer?

It becomes:

> Can the agent behave reliably?

Tameness Engineering is a way to think about that reliability problem.

## Suggested citation

If you refer to this concept, you can cite it as:

> Tameness Engineering: a framework for shaping AI agent behavior through iterative observation, correction, reinforcement, and stabilization. Proposed by [YOUR NAME], 2026.

## License

This repository is intended to be shared and cited. Suggested license: **CC BY 4.0** for text and diagrams, unless otherwise specified.
