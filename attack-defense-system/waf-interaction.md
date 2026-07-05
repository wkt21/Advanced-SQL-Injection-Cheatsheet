# WAF Interaction & Bypass Theory

## Red Team (Attack)
- Observe WAF blocking patterns and rate limits.
- Mutate payload structure to test filter robustness.
- Test encoding, spacing, and comment-based variations.

## Blue Team (Defense)
- Tune WAF with allow-lists and context-aware rules.
- Canonicalize inputs before inspection.
- Use anomaly-based detection instead of signature-only filtering.
