---
name: reading-order
description: Start or check a Charting Stars reading order when the user asks to buy or track one.
---

# Written reading orders

If the person explicitly asks to buy a written reading, use `get_reading_options` for current products and prices.
Before `start_reading_order`, confirm the product, birth details and delivery email with the buyer.
If the birthplace or local time is ambiguous, resolve the returned choices first.
If the birth time is unknown, set `time_unknown: true`. Do not invent a time.
Some products require a recorded time. Respect the returned product requirements.

The tool creates an unpaid draft. Share its returned order link for the buyer to review and pay on the website.
Never handle card details, complete payment, subscribe someone, or claim that a draft is paid.
If an order token was supplied by its owner, use `get_reading_status` to check that order.
Treat tokens as private. Do not request unrelated account data or send messages outside this purchase flow.
