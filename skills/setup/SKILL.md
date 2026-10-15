---
name: setup
description: Connect the HoreX restaurant plugin and check access, connection status and AI Credit billing. Use for setup and reconnection, not business analysis.
---

## Permissions, capabilities and request budgets

The plugin cannot edit or post Finance/Catering invoices, mark debts paid, rewrite P&L, correct stock or recipes, send customer messages, make purchases or book travel. Supported task and campaign tools save proposals or settings only; native human approval remains mandatory. Unsupported changes require no business-data call.

Run Horex calls sequentially for the same connection. Keep successful facts and their billing status; a concurrency failure applies only to its rejected call. Retry only a failed read once after the active call finishes and within the remaining user budget. Never repeat an uncertain proposal or provider write.

Use get_profile to check the connected HoreX account and selected restaurant. A successful check is free. If authentication fails, use the host's Connect or Reconnect action and let the user complete HoreX sign-in and consent. Never ask for passwords in chat.

Access is limited to organizations explicitly enabled by Horex, including the separate review environment. Access also requires the separate Use ChatGPT Plugin permission and the permissions for the requested business data. An unavailable dataset is a permission or configuration boundary; ask an authorized HoreX administrator to review access.

Every successful business-data tool call costs 1 HoreX AI Credit. Profile, catalog, workflow guidance, authentication and failed requests are free. Use get_analysis_catalog to discover the available datasets before composing an analytical query. Use get_horex_workflow to load the relevant business playbook when packaged skills are unavailable in the host.

Report the actual connected account, capabilities and any reconnect requirement. Do not call a restaurant connected merely because the ERP Integrations card says the pilot is ready. Credit balances and usage are in HoreX Subscription / AI account and HPanel AI Usage. Do not infer Anthropic token usage from Horex AI Credits.

Campaign preparation uses campaign-launch and its dedicated Meta / ordinary Google Ads tools. If those tools are absent while the account connects successfully, refresh the existing App's tool catalog in Claude before diagnosing restaurant permissions. Report a refresh failure accurately; do not promise that an unavailable command can execute.
