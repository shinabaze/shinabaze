# Shinabaze Ajiya

I build systems that run parts of a business on their own: AI agents and automations, AI video,
and on-chain infrastructure. I run DreamFoxVerse, an AI automation and content studio.

The repos below are small, clean rewrites of parts of systems I run in production. Each one runs
offline with no keys, and its README says what I learned building it.

| Repo | What it is |
|---|---|
| [n8n-production-kit](https://github.com/shinabaze/n8n-production-kit) | Four small tools for running n8n in production: model failover in a Code node, a webhook secret guard, a dry run that cannot write, a workflow linter. JavaScript |
| [llm-inbox-agent](https://github.com/shinabaze/llm-inbox-agent) | An email agent whose safety rules live in code, with an eval that always shows the baseline. Python |
| [resilient-rpc](https://github.com/shinabaze/resilient-rpc) | A JSON-RPC endpoint pool that bans each endpoint for as long as its error says, and keeps paid capacity for the calls that matter. JavaScript |
| [v3-ring-sizer](https://github.com/shinabaze/v3-ring-sizer) | A quoter for Uniswap V3 style pools that is exact or refuses, and a search for the trade size that earns the most. JavaScript |
| [claim-receipts](https://github.com/shinabaze/claim-receipts) | Checks that a source page really says the statistic you quote, and screenshots the passage with the number marked. Python |
| [keyframe-forensics](https://github.com/shinabaze/keyframe-forensics) | Measure how a video is cut and animated with ffmpeg alone: shot rhythm, holds on ones and twos, motion, sync. JavaScript |
| [email-send-gate](https://github.com/shinabaze/email-send-gate) | One Postgres function every email asks before it goes out: unsubscribes, bounces, cooldowns, no sales emails to paying customers. SQL |
| [brief-to-email](https://github.com/shinabaze/brief-to-email) | Turns a short JSON brief into an HTML email that holds up in Gmail, Outlook and on a phone, then checks size, alt text, preheader, strict MJML and https links. JavaScript |
| [agent-tools](https://github.com/shinabaze/agent-tools) | Small tools I give my coding agents: diagrams from JSON, editable decks, contrast and real-phone page checks, git hooks that keep every commit mine. JavaScript, Python |
| [polite-web-reader](https://github.com/shinabaze/polite-web-reader) | Reads web pages politely: robots.txt on every hop, one request at a time per host, a revalidating cache, and a bot check reported as blocked, not read as content. Python |
| [media-sorter](https://github.com/shinabaze/media-sorter) | Tidies a folder of renders and downloads by type and date, finds duplicates by content, plans before it moves, keeps an undo log, never deletes. Python |

**What I work on**

- **AI automation and agents.** n8n in production, LLM agents with evals that can't flatter them.
- **AI video.** An editing studio that measures cuts and timing instead of guessing them.
- **Web3 infrastructure.** RPC handling, quoting and sizing for on-chain systems.

Work and case studies: [portfolio.dreamfoxverse.com](https://portfolio.dreamfoxverse.com) ·
[LinkedIn](https://www.linkedin.com/in/shinabaze-ajiya-7b1049241)
