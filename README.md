# example4.ai — xmp4 landing page

This repository hosts the source of the public landing page served at [**example4.ai**](https://example4.ai).

The single source file is [`index.html`](index.html) — a self-contained, zero-dependency page with embedded CSS and JavaScript (EN/IT i18n, typing animation, animated counters, dark theme). No build step. No framework. Edit and push.

## What xmp4 is

xmp4 is a hosted MCP server that gives AI coding agents the compiler's semantic view of 547 popular open-source libraries via SCIP. Real callers, real source, real hierarchy — in 3 tool calls. Free public endpoint at `https://mcp.example4.ai/mcp`.

- **Landing**: <https://example4.ai>
- **Public docs & quick-start**: <https://github.com/0ics-srls/lsai-xmp4.public>
- **Benchmark whitepaper (reproducible)**: <https://github.com/0ics-srls/lsai-xmp4.public/blob/main/docs/benchmarks/WHITEPAPER.md>
- **LSAI protocol**: <https://github.com/LadislavSopko/lsai-protocol>

## Files

| File | Purpose |
|---|---|
| `index.html` | Full landing page. Self-contained. Deployed to Hetzner host behind `example4.ai`. |
| `LICENSE` | Apache 2.0. |

## Deploy

The production host pulls `index.html` from this repository's default branch. Changes to this file are reflected on `example4.ai` by the deploy pipeline (managed separately).

## License

Apache 2.0 — see [LICENSE](LICENSE).
