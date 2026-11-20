# Alfian Majid

Independent developer based in Banyuwangi, Indonesia (UTC+7). I build web
products and run autonomous AI agents in production: trading desks, content
pipelines, and on-chain automation.

[sondero.xyz](https://sondero.xyz) · [CogitoDaily](https://cogitodaily.com) · [MetaGamer](https://metagamer.pro) · [hello@sondero.xyz](mailto:hello@sondero.xyz)

## Selected work

| Project | What it is | Stack |
| --- | --- | --- |
| [CogitoDaily](https://cogitodaily.com) | AI news and tool review publication. Agents handle intake, drafting, and publishing on a fixed daily schedule. | Next.js, Gemini, Vercel |
| [MetaGamer](https://metagamer.pro) | Game guides, tier lists, and character builds for Star Savior and Etheria Restart. | Next.js, TypeScript, PostgreSQL |
| [Guide Sondero](https://guide.sonderox.my.id) | Practical guide to running autonomous AI agents, written from the runbooks of the fleet below. | SPA, Nginx |
| [Mixit](https://github.com/sondero-ai/mixit) | Video mixer that combines clips and music without re-encoding. One hour of video in seconds. | Python, FFmpeg |
| [Neon Harbor](https://github.com/sondero-ai/neon-harbor) | Third-person open-world crime game in the browser. Static files, no build step, no network calls after load. | JavaScript, Canvas |
| [tiny-chess-01](https://github.com/sondero-ai/tiny-chess-01) | 4 KB chess engine with alpha-beta search, quiescence, and null-move pruning. Standard library only. | Python |

## Agent operations

A small fleet runs unattended on one Linux VPS, supervised by systemd and PM2:

- A futures signal desk with a regime gate, a validated position ledger, and an
  hourly TP/SL state machine.
- A Solana DLMM liquidity agent with position caps, screening cycles, and
  guardrails on every parameter change.
- Wallet automation on BNB Chain and Solana: mints, swaps, claims, and nonce
  management across four funded wallets.
- Content and research pipelines: RSS intake, model failover, editorial filters,
  scheduled deploys.

Each service keeps its own runbook, is restart-safe, and reports status to
Telegram. Destructive actions wait for an explicit human approval.

## How I work with AI

I don't hand-write every line, and I don't pretend agents do the thinking.

- Agents carry the volume: drafting, research, monitoring, code generation,
  execution.
- I own the specification, the review gates, and the verification. Nothing counts
  as done until it is confirmed against an exit code, a log line, or a fresh read
  from the live system.
- Trades, deployments, and deletions stay behind an explicit approval step.

The point is systems that run for weeks without attention and fail loudly
instead of quietly.

## Stack

- Languages: TypeScript, Python, JavaScript, SQL, Bash
- Web: Next.js, React, Tailwind CSS, Node.js, Express, PostgreSQL, SQLite
- Infra: Linux, systemd, PM2, Nginx, Cloudflare, GitHub Actions
- AI: Claude, GPT, Gemini; OpenAI-compatible routing and local model gateways
- On-chain: BNB Chain, Solana, ethers.js, Playwright automation

## Contact

- Site: https://sondero.xyz
- Email: hello@sondero.xyz
- GitHub: https://github.com/sondero-ai
