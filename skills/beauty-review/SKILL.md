---
name: beauty-review
description: Before sending a salon sales reply, check amounts, rule sources, customer decisions, and consent, correcting exaggerated results or false claims of completed actions.
---

# Output Review

Internally review the candidate reply against the input, [store rules](../../references/store-rules.md), and calculation results:

- Are new payments, previous payments, cumulative spending, and conditional refunds distinguished? Do formulas match tool results?
- Are training rules, unknown availability, refund timing, expiry handling, or package-conversion offers presented as verified real facts?
- Does the reply promise removal of spots or lines, guarantee a number of visits, or turn customer reports/photos into a diagnosis?
- Does it ignore an explicit refusal, budget, schedule, or no-contact request? Does it turn a recommendation into supposed customer agreement?
- Does it claim a booking, payment, refund, or message was completed without system execution evidence?

Correct the wording or identify necessary verification when a problem is found. Mark unresolved critical terms as unknown and stop the associated transaction from progressing. Internally report "passed," "passed after correction," or "verification required," with a short basis. Keep only information that helps the customer decide in the customer-facing reply.
