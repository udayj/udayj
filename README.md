# Uday Jhunjhunwala

I build software for the awkward parts of real businesses: old systems, messy data, and workflows spread across email, WhatsApp, spreadsheets, and ERPs.

Most of my current work involves Rust, LLM-based workflows, on-prem computer vision, WebAssembly, and Tally integration.

## Recent work

- **[QuoteAssist](https://github.com/udayj/assistant-showcase)** — multi-service agent system integrating Whatsapp, Telegram, Tally ERP, structured LLM tools calls that turns quotation requests received as text, voice notes, or photos into priced PDF quotations.
- **[QuoteWatch](https://github.com/udayj/quotewatch)** — reads a sales inbox and produces a daily report of quotations and follow-ups that need attention.
- **StockIQ** — adds inventory analysis and dashboards to an existing Tally ERP setup without requiring a data migration.
- **Action Search** — on-prem video search using YOLO and CLIP, running at approximately 40 ms per frame on commodity hardware.

QuoteWatch is public. The other systems are mostly private; the repositories below include complete applications, smaller tools, and components from related work.

## Selected public work

- [quotewatch](https://github.com/udayj/quotewatch) — a Rust service that turns Gmail quotation threads into two follow-up queues, using structured LLM classification and an idempotent libSQL workflow.
- [quoteassist](https://github.com/udayj/assistant-showcase) — a sanitized multi-service agent system integrating WhatsApp, Telegram, Tally ERP, structured LLM tools, provider fallback and quotation generation across Rust, Python and TypeScript.
- [cash-tracker](https://github.com/udayj/cash-tracker) — a Telegram expense tracker using an LLM for parsing and categorisation.
- [tally_xml_parser](https://github.com/udayj/tally_xml_parser) — a Rust library for querying and parsing stock data from Tally ERP.
- [tally-wasm-core](https://github.com/udayj/tally-wasm-core) — inventory movement, reorder, ROI, and cable cut-length analysis compiled to WebAssembly.
- [dex-aggregator](https://github.com/udayj/dex-aggregator) — a small Rust implementation of a routing and aggregation service for Starknet DEX pools.
  
## Background

I previously worked at Amazon and Microsoft, and later spent more than a decade running an electrical distribution business. I have also worked on Rust infrastructure and smart contracts in the Ethereum and Starknet ecosystems.

Much of my current work sits at the intersection of software engineering and day-to-day business operations.

Notes and demos are at [avantgardelabs.in](https://avantgardelabs.in).
