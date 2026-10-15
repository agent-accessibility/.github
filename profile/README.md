# Agent Accessibility

**Give AI agents eyes and hands.**

AI agents today are powerful but blind. They can reason, write code, draft strategies, but they can't see your docs, navigate your environments, or use your tools unless someone hand-wires every integration. That's not an agent problem. That's an accessibility problem.

This started from a real problem. I was working on Azure, using coding agents daily (Claude Code, GitHub Copilot, Hermes), and they kept hitting the same wall: they couldn't access what they needed to do their job well. My docs, my environment, my context. Then I found the [Microsoft Learn MCP server](https://devblogs.microsoft.com/engineering-at-microsoft/how-we-built-the-microsoft-learn-mcp-server/) and something clicked. MS Learn solved it for their own docs. What if we generalized this for everything?

That's what Agent Accessibility is about. Not just knowledge retrieval. Making entire environments, documentation, compute, and eventually the physical world accessible to AI agents. Through open standards (MCP), local-first infrastructure, and plug-and-play experiences that work for enterprises and solo devs alike.

## Projects

| Project | What it does |
|---|---|
| [KMCP](https://github.com/agent-accessibility/KMCP) | Turn any doc source into an MCP endpoint. Hybrid search (BM25 + kNN), local embeddings, zero LLM cost at query time. `docker compose up` and go. |

## The bigger picture

KMCP tackles knowledge accessibility. That's step one. The roadmap goes wider:

- **Knowledge** - docs, wikis, PDFs, APIs, video transcripts, OCR for scanned content
- **Compute** - agents need to run things, not just read things
- **Environment** - your dev setup, your cloud infra, your CI/CD pipelines
- **Cross-agent sharing** - agents sharing context without vendor lock-in
- **Physical world** - hardware, devices, real-world actuation

If your agents can't see, reach, or navigate your world, they're not really agents. They're just LLMs with a nice UI.

## Get involved

- [GitHub Discussions](https://github.com/agent-accessibility/KMCP/discussions) for questions and ideas
- [Issues](https://github.com/agent-accessibility/KMCP/issues) for bugs and feature requests
- PRs welcome. See [CONTRIBUTING.md](https://github.com/agent-accessibility/KMCP/blob/main/CONTRIBUTING.md)

Built by [@hashwnath](https://github.com/hashwnath) · [LinkedIn](https://www.linkedin.com/in/sutharapuhashwanth/)
