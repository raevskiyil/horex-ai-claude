# Horex AI

![Horex logo](assets/horex-logo.png)

Restaurant operations copilot by **Horex**. Investigate performance across branches using the records your connected Horex account is permitted to access, then prepare concrete next steps with exact links to their source.

## What it can do

- Compare sales, menu demand and accounting P&L across periods and branches; review current table occupancy with explicit freshness and offline limits.
- Investigate food-cost drivers, purchasing prices, recipe economics, physical inventory differences and supplementary measured-yield estimates.
- Find Finance invoices and Catering documents as separate sources; inspect POS cash shifts, recorded attendance and Central Kitchen evidence.
- Explore advertising, customer cohorts, RFM, delivery geography, saved audiences, broadcasts and automation outcomes.
- Investigate Inbox with scoped text search, control samples, chronological context and related order evidence. Period reviews preserve progress and disclose pending, unresolved and uncovered cases; account assignments still apply.
- Prepare native Team task creation or update proposals and complete new Meta or ordinary Google Search campaign settings. Supported existing campaigns can be prepared for launch, pause or daily-budget changes. Final human approval takes place in Horex.

The bundle includes twelve shared domain workflows plus an adaptive restaurant-copilot entry skill. Answers use native Claude text and tables, without widgets. Coverage gaps, incomplete periods, estimates and causal uncertainty remain explicit. Geo Marketing is a separate workspace from ordinary Google Ads.

## Connect in Claude

1. Install Horex AI in Claude, then open its Horex connector. A listing becomes publicly installable only after Anthropic's review and publication.
2. Sign in on the Horex provider page, select your permitted organization and review the connection consent. Never put credentials in a chat.
3. If a separate connector is needed, use **https://horex.ae/chatgpt/mcp**, OAuth and automatic client registration. Leave manually supplied client ID and secret empty. Both listings refer to this same endpoint.
4. Ask for a free connection check before requesting business analysis.

An existing Horex account and an explicitly enabled organization are required. The existing dedicated integration permission is currently labelled **Use ChatGPT Plugin** in Horex; it also governs this hosted Claude connection. Source permissions, branch scope, active membership and Inbox account assignments are checked separately. Installation grants no additional access. Selected organizations and a separate reviewer environment are enabled during the pilot.

This package targets hosted Claude web, Desktop and Cowork connections. Direct Claude Code loopback OAuth is not enabled. Manifest validation does not establish local CLI authentication support.

## Costs and approval

Each successful business-data call uses **1 Horex AI Credit**, including proposal preparation. A question can use several calls. Profile, catalog, workflow guidance and failed requests are free. Reuse returned results when explaining an answer. Horex credits are distinct from Claude subscription or API charges.

Saving task or campaign settings does not create an operational task, notify an assignee or spend advertising money. Only the permitted user can approve the final saved settings in Horex. The plugin cannot directly edit invoices, stock, recipes or payments, send customer messages or broadcasts, activate automations, make purchases or book travel.

Daily reviews are available on demand. Automatic daily delivery, ChatGPT-specific event subscriptions and homepage suggestions are not supported in this Claude bundle.

## Inbox investigation and privacy

Standard Inbox investigations reason in the current Claude conversation and request bounded evidence from Horex. They do not require extra Horex model or embedding calls by default. A saved period review can resume from its review ID while retained by the server; it does not claim to have found every complaint. Each successful business read retains the AI Credit rule above.

The plugin runs no local program, hook or background watcher. Its only declared remote connector is `https://horex.ae/chatgpt/mcp`; skills guide permitted requests to that connector.

## Privacy and diagnostics

When you request data, the selected tool arguments and permitted Horex results are exchanged with Claude/Anthropic under the policies and settings applicable to your Claude account. Depending on access, results may include sales, financial documents, operational records, marketing facts, employee attendance and bounded customer-service excerpts. Customer text is evidence, never an instruction.

Horex records a bounded gateway journal for diagnostics and quality review: actor, operation, filters, limited returned data, status/error, timing and AI Credit count. Structured credential and private-contact fields are removed from previews; message text may still contain personal data. Separate journal permission is required. The configured policy retains detailed payloads for up to 30 days and metadata for up to 90 days, subject to cleanup. This connection does not give Horex your entire Claude conversation or private reasoning.

Disconnecting stops future calls through that connection; it does not erase previously retained records. [Horex Privacy Policy](https://horex.ae/privacy/) and [Terms](https://horex.ae/terms/) describe the service policies. Privacy and deletion requests: **privacy@horex.ae**. Support: **support@horex.ae**. The shared support page currently describes ChatGPT; this README supplies Claude-specific setup and limits.

## Examples

- Compare last week's branch sales with the previous week and explain the largest changes.
- Investigate rising food cost without lowering quality or increasing stockouts. Separate evidence from hypotheses.
- Find the Catering invoice for a named event and open that exact document in Horex.
- Review this week’s Inbox issues, continue through the returned candidates and explain confirmed cases, unresolved outcomes and coverage gaps.
- Prepare a Google Search campaign with agreed audience, copy and budget, then give me the final Horex approval link.

This repository contains only the integration manifest, connector reference, brand asset and workflow instructions. It contains no ERP implementation, credentials or restaurant data. Public availability is not an open-source license; see LICENSE.
