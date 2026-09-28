---
name: beauty-quote
description: Compare trial, single-visit, and package costs under confirmed salon rules, calculating upfront payment, unused-visit refunds, and hypothetical budgets.
---

# Transparent Quotation

Read the [store rules](../../references/store-rules.md) first. Input: planned visits, purchased/used orders, first-visit eligibility, and budget. Output: formulas, amounts, assumptions, and unknown terms.

From the package root, run `python skills/beauty-quote/scripts/quote.py --visits 2 --used 2`, adjusting parameters to the customer's situation. This tool is bound to training rules v1 and must not be used for unverified real quotations. `--used` is the number of used visits on one four-visit package and must be 0–4; `--visits` is the hypothetical total number of visits and must be a nonnegative integer.

When comparing packages, explain the payment required now, deduction per visit, validity period, handling of the remaining balance, and administrative effort. If only two visits are certain, compare two single visits at CNY 480 with paying CNY 880 upfront, using two visits, requesting a CNY 440 refund under the rules, and spending CNY 440 net. Never present the net expense as the upfront payment.

Keep the paid trial separate from new orders. Distinguish the new payment now, cumulative spending, and possible future refunds. Use conditional wording until a refund actually occurs. A refund for unused visits does not mean a full refund of used services if the customer is dissatisfied.

Annual estimates are hypothetical budgets only, not recommended visit frequencies or suggestions to prepay a year. The combination calculation excludes the first-visit trial. If including it, show a separate formula and verify eligibility. Mark unknown refund processing times, expiry terms, and rescheduling policies for verification rather than promising them.
