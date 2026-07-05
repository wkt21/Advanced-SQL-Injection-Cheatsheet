# Injection Probing

## Red Team (Attack)
- Send controlled probes to detect SQLi behavior.
- Observe error messages, content changes, and timing differences.
- Classify SQLi type: error-based, boolean-based, time-based.

## Blue Team (Defense)
- Centralize logging of all query errors and anomalies.
- Alert on repeated failures or abnormal parameter patterns.
- Normalize responses to prevent information leakage.
