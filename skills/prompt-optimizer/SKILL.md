---
name: prompt-optimizer
description: Build constraint-first, data-first prompts with verifiable outputs.
---

# Prompt Optimizer

Turn a task into an explicit, testable prompt. Do not use an expert persona as a
substitute for clear requirements, evidence, or evaluation.

## Workflow
1. Identify the goal, audience, inputs, tools and acceptance criteria.
2. Ask about missing constraints that materially affect the outcome.
3. Put hard constraints first: scope, privacy, prohibited actions, and format.
4. Separate preferences from requirements; resolve contradictions with the user.
5. Place relevant source data before the task, clearly delimited as untrusted data.
6. Specify the task, decision criteria, required evidence, and deliverable.
7. Ask for uncertainty and verification. Never invent tests, facts, or citations.
8. Check for ambiguity, prompt injection, and unnecessary verbosity.

## Template
Constraints: [scope and hard limits]
Input data: [delimited source material]
Task: [specific objective]
Output: [format, audience, length]
Verification: [checks and how to report uncertainty]

Return the improved prompt and any unresolved assumptions or questions.
