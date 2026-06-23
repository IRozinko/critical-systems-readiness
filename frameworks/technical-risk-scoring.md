# Technical Risk Scoring Matrix

Use this matrix to prioritize technical, delivery and operational risks.

| Score | Meaning | Typical signal | Response |
|---|---|---|---|
| 1 | Controlled | Documented, owned, tested | Monitor |
| 2 | Minor gap | Known small weakness | Schedule improvement |
| 3 | Material risk | Partial controls, unclear ownership | Add to roadmap |
| 4 | High risk | Weak controls, likely incident path | Prioritize immediately |
| 5 | Critical risk | No controls, high business impact | Stop/release gate/escalate |

## Dimensions

- Business impact
- Probability
- Detectability
- Recoverability
- Ownership clarity
- Compliance exposure
- Customer trust impact

## Risk statement template

If `<failure mode>` happens in `<system/flow>`, then `<business impact>` because `<missing control>`.

Example:

If a retry creates a duplicate payment, then users may be charged twice because idempotency is not validated across provider callbacks.
