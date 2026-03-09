# hire-from-claude 🤖

> Hire devs, designers & marketers from inside Claude or Cursor — without switching tabs.

**[RevolutionAI](https://www.revolutionai.io)** is an MCP-native freelance marketplace built for SaaS founders who live in their AI tools.

## The problem

Building a startup means constantly context-switching:
- Need a dev? → Open Upwork, post job, wait days
- Need a designer? → Jump to Dribbble or Fiverr
- Need a marketer? → LinkedIn, emails, calls

Every switch kills your flow. You're supposed to be building, not bouncing between 10 tabs.

## The solution

Stay in Claude. Just say what you need:

```
"Claude, I need a landing page designer. Budget $2K, timeline 5 days."
```

RevolutionAI handles the search, match, and hire — directly from your AI workspace.

## How it works (MCP integration)

Add RevolutionAI to your Claude or Cursor MCP config:

```json
{
  "mcpServers": {
    "revolutionai": {
      "command": "npx",
      "args": ["-y", "@revolutionai/mcp-server"]
    }
  }
}
```

Then in Claude:
- `hire_developer` — post a dev task and get matched instantly
- `hire_designer` — find designers filtered by style, budget, timeline  
- `hire_marketer` — connect with marketers who know SaaS growth
- `search_talent` — browse available talent by skill/rate

## Post a job in 5 minutes

- **Project/freelance work** → [revolutionai.io/plan-project](https://www.revolutionai.io/plan-project)
- **Full-time or contract hire** → [revolutionai.io/plan-job](https://www.revolutionai.io/plan-job)

No account needed to browse. AI-assisted job posting takes under 5 minutes.

## Why founders use RevolutionAI

- **Stay in flow** — don't leave your AI workspace to find talent
- **3 months free** — zero platform fees for the first 90 days (W26 YC founders)
- **All roles** — devs, designers, marketers, writers, ops — not just AI engineers
- **Stripe Connect** — payments handled, no invoicing back-and-forth
- **$15K MRR, 42 clients** — live and growing

## Current traction

| Metric | Value |
|--------|-------|
| MRR | $15K |
| Paying clients | 42 |
| Talent on platform | Active marketplace |
| Payment processing | Stripe Connect live |

## Links

- 🌐 [revolutionai.io](https://www.revolutionai.io)
- 📋 [Post a project](https://www.revolutionai.io/plan-project)
- 💼 [Post a job](https://www.revolutionai.io/plan-job)
- 📚 [Blog](https://www.revolutionai.io/blog)

## Contributing

Found a bug or want to improve the MCP integration? PRs welcome.

---

*Built for founders who ship fast. Questions? [hello@revolutionai.io](mailto:hello@revolutionai.io)*
