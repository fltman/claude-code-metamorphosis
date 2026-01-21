# /select - Choose Winner

End evolution and select winner for production.

## Usage

```
/select
/select --timeline=δ
/select --deploy
```

## Requirements

- Fitness > 85 (PRODUCTION threshold)
- CRITICAL Council review
- Majority human approval

## Process

1. Validate readiness
2. Trigger Critical review
3. Wait for humans (no timeout)
4. Archive to `data/winners/`
5. Record in Ledger
6. Optional deploy with revert window
