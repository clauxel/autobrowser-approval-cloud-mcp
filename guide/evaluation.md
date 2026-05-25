# Evaluation Guide

Use this page to evaluate whether AutoBrowser Approval Cloud fits a real workflow.

## What To Test

- AI agent browser approval MCP
- AutoBrowser Approval Cloud
- AutoBrowser Approval Cloud documentation
- AutoBrowser Approval Cloud remote MCP
- autobrowserapproval server card

## Expected Evidence

- Open AutoBrowser Approval Cloud and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://autobrowserapproval.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call request_page_approval with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://autobrowserapproval.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=autobrowserapproval_public_docs&utm_content=evaluation_checkout
