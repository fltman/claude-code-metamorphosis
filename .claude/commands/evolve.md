# /evolve - Advance Generations

Evolve all active timelines one generation.

## Usage

```
/evolve
/evolve --timeline=α
/evolve --auto
```

## Process

For each active timeline:

1. Evaluate fitness
2. Check early exit triggers
3. Check plasmid eligibility (spike > +20)
4. Apply mutations
5. Spawn next generation
6. Check governance thresholds

## Output

Shows fitness changes, mutations applied, terminated timelines, and created plasmids.
