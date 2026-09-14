# QuickBooks Plugin for Claude

Skills that turn your QuickBooks Online data into plain-language business insights.

> **Requires the QuickBooks connector.** Connect it at
> https://claude.ai/customize/connectors (sign in with your Intuit account). See
> [SETUP.md](./SETUP.md) for step-by-step instructions, including Claude Code.

## Skills

| Skill | What it does |
| --- | --- |
| `business-health-check` | A CFO-style briefing across Profit & Loss, Cash Flow, Balance Sheet, A/R Aging, and Sales reports: what's going well, what needs attention, and what changed. Read-only. |
| `industry-benchmark` | Compare your business — or any metric you provide — against regional and national industry peers by industry and location. Read-only. |
| `setup` | Guides you through connecting QuickBooks and troubleshooting the connection. |

Try prompts like:

- "How is my business doing this quarter?"
- "What should I be worried about in my financials?"
- "How does my profit compare to other restaurants in Texas?"

## Connecting QuickBooks

The skills use the QuickBooks connector from your Claude account. Connect it at
https://claude.ai/customize/connectors by signing in with your Intuit account and authorizing
access to your QuickBooks company. In Claude Code, sign in with your claude.ai account (`/login`)
so the connector is available in your sessions.

## Notes

- Both skills are read-only: they never create, modify, or send anything in QuickBooks.
- Output is an operational read of your QuickBooks data — not tax, legal, investment, or lending
  advice.

