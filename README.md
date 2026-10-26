### Adrian Capraru

Builder-operator. Takes AI systems from first commit to production and runs them, for finance, accounting and operations teams. Ex-FinTech COO, founder of 3Descu, Co-Founder of Systemartis. Based in Romania, working across the EU, UK and US.

**Proof**

- Took an Irish accountancy firm's 20-module multi-tenant SaaS from first commit to live production in 10 days, behind 3,000+ automated checks and an 87-point smoke test on every deploy. Its AI bills reader scores 99.8% field accuracy on a synthetic test corpus at under one cent per document, EU-hosted.
- Finance automations in daily production: Xero prepayment journals for a tour operator, validated 107/107 against the bookkeeper's own entries before go-live; HubSpot-to-Xero invoicing across 3 legal entities and 4 currencies, live since April 2026 with 212+ invoices.
- Founded 3Descu in 2022 with 5 printers in an apartment; now 200+ printers, an ISO 9001:2015 certified company, 2,000+ orders from 1,600+ buyers in 30 countries. Built its quoting platform solo with AI coding agents: 929 commits, ~400 merged PRs, 120+ release checkers running ~260K assertions.
- Upwork Top Rated, 100% Job Success: 22 contracts, every rated contract five stars.

**Selected work**

- [3descu-mcp-quote](https://github.com/cadi27tech/3descu-mcp-quote) - public MCP server that gives Claude and ChatGPT real factory prices. In the [official MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=3descu) as `io.github.cadi27tech/3descu-quote`.
- [ai-agent-guardrails](https://github.com/cadi27tech/ai-agent-guardrails) - Claude Code hooks written after real incidents with AI coding agents: fail-loud parsing, look-before-OCR evidence, state that survives context compaction.
- [3descu-social-agent](https://github.com/cadi27tech/3descu-social-agent) - EUR 0/month publisher on GitHub Actions and the Meta Graph API that posts a full quarter's calendar on time and never backfills a missed post.
- [real-estate-ai-analyzer](https://github.com/cadi27tech/real-estate-ai-analyzer) - Streamlit investment analyzer with LLM market notes ([live demo](https://real-estate-ai-analyzer.streamlit.app/)).
- Merged MCP directory PRs: [TensorBlock #4125](https://github.com/TensorBlock/awesome-mcp-servers/pull/4125), [mcpHQ #325](https://github.com/mcpHQ/awesome-mcp-servers/pull/325), [punkpeye/awesome-remote-mcp-servers #2201](https://github.com/punkpeye/awesome-remote-mcp-servers/pull/2201), [toolsdk-ai #930](https://github.com/toolsdk-ai/toolsdk-mcp-registry/pull/930).

Most client work (accounting practices, hospitality, B2B software, an EU-hosted reporting platform for the Dutch education sector) is private. Write-ups at [cadi27tech.github.io](https://cadi27tech.github.io).

**Build principles**

- Human in the loop by design: agents propose, people approve; money-moving actions are confirm-first, and dry runs come before live runs.
- Evals and regression gates: golden test sets, validation against the humans' own numbers, nothing ships without its checks green.
- Audit trails: every write is logged and idempotent, so it can be replayed or reversed.
- AI coding agents under review: parallel agents in git worktrees, hooks that turn claims into evidence, a human merging every PR.
- EU data residency and tenant isolation where client data is involved.

**Contact:** [LinkedIn](https://www.linkedin.com/in/adriancapraru27/) - [cadi27tech.github.io](https://cadi27tech.github.io)
