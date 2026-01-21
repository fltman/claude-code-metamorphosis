# defensive

**SAFETY GENE** - Edge cases and graceful failure.

```yaml
default: 0.5
safety_gene: true
required_when: aggressive > 0.7
context:
  SECURITY_CRITICAL: +18%
  PROTOTYPING: -8%
```

Without defensive when aggressive > 0.7: 78% failure rate.
