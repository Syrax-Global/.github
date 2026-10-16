# Security policy

## Reporting a vulnerability

Report suspected vulnerabilities privately to **security@syrax.global**. Do not open a
public issue, and do not disclose the detail publicly until we have responded.

Please include what you found, how to reproduce it, and what you believe the impact
is. If you have a proof of concept, say so rather than attaching exploit code in the
first message.

**Response times**

| Stage | Our commitment |
|---|---|
| Acknowledgement | Within 24 hours of receipt, with a reference number |
| Initial triage (scope, plausibility, initial severity) | Within 72 hours of receipt |
| Status updates | At least every 7 days until the report is resolved |

## What we ask

- Do not access, modify or delete data that is not yours.
- Do not run denial-of-service tests, spam, or social-engineering attempts.
- Give us reasonable time to remediate before disclosing.

## Scope

This policy covers the software in this repository. Findings in third-party
dependencies should be reported upstream as well as to us.

## ⛔ Never include a credential in a report

If you believe you have found an exposed key, token, password or recovery phrase,
**do not paste the value**. Tell us where you found it and send a SHA-256
fingerprint of it instead. We will identify it from that.
