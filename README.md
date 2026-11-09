# Skavio LLC — practical tools for documents, automation and USDC payments

**New company MCP access (9 November 2026):** [Agent Tools Dashboard](https://getskavio.com/agent-tools/dashboard.html) now supports **Continue with Skavio account** for a verified main Skavio login, or a separate company registration. Existing Agent Tools companies must explicitly link both logged-in accounts; a matching email alone is not enough. Generate a company API key and connect to **`https://getskavio.com/agent-tools/mcp`**. The older `/processing/mcp` remains operator-provisioned, and the two company credit wallets are **not merged**. [Agent Tools documentation](https://getskavio.com/agent-tools/docs.html). Real external paid MCP processing and delivery remain unverified.

**Production apps and hosted developer APIs.** We focus on small businesses, independent developers and AI agents that need useful outputs rather than complex infrastructure.

[Website](https://getskavio.com/?utm_source=github&utm_medium=profile&utm_campaign=usdc_launch_20261023) · [Payment Proof](https://getskavio.com/proof/?utm_source=github&utm_medium=profile&utm_campaign=usdc_launch_20261023) · [x402 APIs](https://getskavio.com/x402/?utm_source=github&utm_medium=profile&utm_campaign=usdc_launch_20261023) · [Developer docs](https://getskavio.com/x402/docs/?utm_source=github&utm_medium=profile&utm_campaign=usdc_launch_20261023)

**One-time option:** [Verify one USDC payment for **0.25 USDC** and download the PDF proof](https://getskavio.com/proof/?utm_source=github&utm_medium=profile&utm_campaign=proof_oneoff_025_oct26). No monthly subscription required. A 7-day free trial and recurring merchant plans are also available.

**Try Payment Proof without creating an account:** [interactive 60-second simulated payment demo](https://getskavio.com/proof/demo?utm_source=github&utm_medium=profile&utm_campaign=usdc_nosignup_demo_oct26). No wallet or real funds required.

## Accept native USDC for a business — without Stripe

**[Skavio Payment Proof](https://getskavio.com/proof/?utm_source=github&utm_medium=profile&utm_campaign=usdc_launch_20261023)** helps independent merchants create payment links and sales invoices, check on-chain settlement and export business payment evidence. Merchants retain control of their receiving wallets. Trial access is **7 days**, with paid plans starting at **9 native Circle USDC / 30 days** and manual wallet-approved renewals.

- Supported merchant receiving networks: Base, Polygon PoS, Arbitrum and Solana.
- Separate sales invoices, blockchain evidence and accounting CSV exports.
- REST API, signed webhooks, Python and TypeScript SDKs for custom integrations.
- **[Step-by-step merchant guide (English)](https://github.com/skavio-eu/skavio-payment-proof-api/blob/main/guides/accept-usdc-without-stripe.md)** · **[USDC-Zahlungen ohne Stripe (Deutsch)](https://github.com/skavio-eu/skavio-payment-proof-api/blob/main/guides/usdc-zahlungen-ohne-stripe.md)**

## AI agents: verify USDC with x402 pay-per-call

**[Skavio x402 + MCP](https://getskavio.com/x402/?utm_source=github&utm_medium=profile&utm_campaign=x402_launch_20261023)** offers hosted verification services charged in **native USDC on Base**:

| Endpoint | USDC / call | Output |
| --- | ---: | --- |
| Verify payment | **0.02** | On-chain USDC transfer evidence |
| Match transfer | **0.03** | Expected recipient and exact amount |
| Generate evidence PDF | **0.05** | Timestamped blockchain transaction record |

Free discovery; paid calls require a **wallet-enabled x402 client**. Standard MCP clients do not sign payments. No wallet seed phrases or private keys are accepted.

- **[Try the free HTTP 402 challenge](https://github.com/skavio-eu/skavio-agent-tools/blob/main/guides/verify-usdc-with-x402.md)**
- Hosted MCP: `https://getskavio.com/mcp`
- [MCP setup for Cursor and Claude Desktop](https://github.com/skavio-eu/skavio-agent-tools/blob/main/MCP_CLIENT_SETUP.md)
- [x402 OpenAPI](https://getskavio.com/x402/openapi.json)

## Documents and transcription

- [PDF, OCR and business-document MCP](https://getskavio.com/processing/docs/mcp/?utm_source=github&utm_medium=profile&utm_campaign=document_tools_20261023) — authenticated processing credits, independent of public x402 calls.
- [Skavio Transcribe](https://getskavio.com/transcribe/?utm_source=github&utm_medium=profile&utm_campaign=document_tools_20261023) — audio/video to editable transcripts.
- [Skavio Meeting](https://getskavio.com/meeting/?utm_source=github&utm_medium=profile&utm_campaign=document_tools_20261023) — recordings, transcripts and reviewable action summaries.
- [File Toolbox](https://getskavio.com/convert/?utm_source=github&utm_medium=profile&utm_campaign=document_tools_20261023) — PDF and everyday file operations.

**Contact for a limited pilot or integration:** [support@getskavio.com](mailto:support@getskavio.com?subject=Skavio%20integration%20pilot)

> **Payment safety:** native Circle USDC is network-specific. A verified blockchain transfer record is not a legal identification or a tax invoice. Customers approve all wallet transfers themselves. No claim of independently completed merchant mainnet acceptance or guaranteed earnings is made.

Skavio LLC · [getskavio.com](https://getskavio.com/?utm_source=github&utm_medium=profile&utm_campaign=usdc_launch_20261023)
