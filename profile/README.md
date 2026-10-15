# Agent Accessibility

**Making knowledge accessible to AI agents.**

Your docs live in Confluence, Notion, S3, GitHub repos, PDFs, internal wikis. Your AI agents can't see any of it.

This started from a real problem. I was working on Azure, using coding agents daily (Claude Code, GitHub Copilot, Hermes), and they kept hitting the same wall: they couldn't access the documentation they needed to do their job well. Then I found the [Microsoft Learn MCP server](https://devblogs.microsoft.com/engineering-at-microsoft/how-we-built-the-microsoft-learn-mcp-server/) and something clicked. MS Learn solved it for their own docs. What if we generalized this for everyone?

That's the idea behind Agent Accessibility: give AI agents eyes and hands so they can actually navigate your knowledge. Not through expensive LLM reranking pipelines, not through proprietary APIs, but through open standards (MCP) and local-first infrastructure that any dev can spin up.

## Projects

| Project | What it does |
|---|---|
| [KMCP](https://github.com/agent-accessibility/KMCP) | Turn any doc source into an MCP endpoint. Hybrid search (BM25 + kNN), local embeddings, zero LLM cost at query time. `docker compose up` and go. |

## Where this is going

KMCP is the first project, not the last. The thesis is broader than docs:

- More source types, deeper ingestion (OCR, video transcripts, API specs)
- Compute accessibility (agents need to run things, not just read things)
- Cross-agent knowledge sharing without vendor lock-in
- Eventually, the physical world too

If your agents are flying blind, they're not really agents. They're just LLMs with a nice UI.

## Get involved

- [GitHub Discussions](https://github.com/agent-accessibility/KMCP/discussions) for questions and ideas
- [Issues](https://github.com/agent-accessibility/KMCP/issues) for bugs and feature requests
- PRs welcome. See [CONTRIBUTING.md](https://github.com/agent-accessibility/KMCP/blob/main/CONTRIBUTING.md)

Built by [@hashwnath](https://github.com/hashwnath)
