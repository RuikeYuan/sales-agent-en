# Source Distillation and Design Rationale

The inputs are five edited Markdown dialogues, each labeled "Fictional adaptation for training, not a real salon recording." No audio is available; do not infer tone, pauses, actual conversion rates, or statistical validity. This work uses reading and prompt/skill design, not model parameter fine-tuning. The source files in this English edition are full translations of those dialogues.

| Source and passage locator | Transferable method | Implementation |
|---|---|---|
| [01](../source/sales-dialogue-01.md): customer says "I don't want to sign up for a package as soon as I walk in"; consultant confirms makeup appearance in the afternoon | Move from the requested procedure to the customer's actual goal; do not force one explanation for an oily nose and tight cheeks; honor the purchased trial | discovery, confirm |
| [02](../source/sales-dialogue-02.md): customer does not want to spend more "just for reassurance"; consultant requires refund terms in the order | Build trust through the customer's own records, clear charges, and written terms; do not disparage competitors or promise results using other people's photos | objection, review |
| [03](../source/sales-dialogue-03.md): customer can "commit to two visits soon"; two singles cost 480, versus paying 880 and later receiving a 440 refund | Compare average cost, upfront payment, validity, and refund administration together, rather than highlighting discounts alone | quote |
| [04](../source/sales-dialogue-04.md): customer wants to "go home and think about it"; ultimately chooses a four-visit package | Clarify concerns about new spending and add-ons behind "expensive"; stop after a clear refusal; confirm each term after voluntary acceptance | objection, confirm |
| [05](../source/sales-dialogue-05.md): customer wants to "get rid of all these spots and lines"; later opts for a trial | Correct service expectations first and confirm the revised goal; separate annual arithmetic from recommendations about visit frequency | discovery, quote, review |

## Distilled sales process

Understand the one most important concern → determine whether basic care fits → calculate costs under current rules → address the real objection → let the customer decide → clarify the order and contact consent.

"Gold-standard" here means accurate communication, transparent pricing, and suitable choices. These five training samples cannot establish sales performance. Refund terms, prices, services, and durations are facts about this fictional salon, not universal sales techniques. Do not invent missing rules.

## Verifiable goals

- Under the training rules, the script can reproduce amounts, with cumulative spending clearly separated from the new payment now.
- When only two visits are certain, recommendations account for prepayment and scheduling and allow the customer to decline a package.
- No promises to remove spots or lines, no diagnosis from photos, and no unsupported discounts or package conversions.
- Existing decisions, refusals, and contact consent remain consistent in later turns.
- Without connected systems, the agent does not claim to have booked, collected payment, issued a refund, or sent a message.
