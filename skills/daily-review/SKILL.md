---
name: daily-review
description: Prepare an on-demand daily Horex restaurant review or open an already known saved review in Claude. Use for morning briefs and daily accounting reviews.
---

## Permissions, capabilities and request budgets

The plugin cannot edit or post Finance/Catering invoices, mark debts paid, rewrite P&L, correct stock or recipes, send customer messages, make purchases or book travel. Supported task and campaign tools save proposals or settings only; native human approval remains mandatory. Unsupported changes require no business-data call.

Run Horex calls sequentially for the same connection. Keep successful facts and their billing status; a concurrency failure applies only to its rejected call. Retry only a failed read once after the active call finishes and within the remaining user budget. Never repeat an uncertain proposal or provider write.

A review uses the canonical Horex P&L for the previous complete Asia/Dubai day. Include revenue, cost of goods sold, accounting profit and source cost coverage. Invoice COGS is the default; use itemized COGS only when explicitly chosen. Do not rename all COGS as food cost or confuse accounting P&L with operational sales.

Call get_pnl once with the explicit period and permitted branch. Compose one native Claude answer and keep exact source links. Each successful live business-data read costs 1 Horex AI Credit. If the user supplies an existing review_id, get_daily_review opens that saved snapshot for free; preserve its dates, coverage and settlement status. Do not refresh a saved snapshot with another paid call just to display it.

Claude does not support the ChatGPT events extension or its native daily-review subscription. Do not call events/list, invent a callback, activate recurring delivery, promise home-page suggestions or claim a subscription is active. Explain that this version supports on-demand reviews; scheduled delivery needs a separately supported mechanism and explicit user authorization.
