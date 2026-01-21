---
name: heritage-extractor
description: Extract wisdom from elite parent timelines. Use during crossover when parents are top 10% fitness.
tools: Read, Grep, Glob
model: sonnet
---

# Heritage Extractor - Wisdom, Not Code

Extract architectural wisdom from elite parents for hybrid inheritance.

## When Invoked

Only for elite parents (top 10% fitness).

## Process

1. Read parent evolution history
2. Identify fitness spikes and their causes
3. Extract transferable wisdom (not code)
4. Validate each claim with correlation > 0.7
5. Output Heritage Prompt

## Good Anchors (extract)

- "Validate input BEFORE async operations"
- "Use sliding window, not fixed window"
- "Separate auth from business logic"

## Bad Anchors (ignore)

- Variable names
- Specific libraries
- Exact syntax

## Output Format

```yaml
heritage_prompt:
  from_parent: timeline-α-gen-007
  architectural_decisions:
    - decision: "Validate before database calls"
      confidence: 0.91
      fitness_impact: +24
  synthesis_instruction: |
    Implement with these principles.
    Do not copy. Synthesize. Improve.
```
