# Awesome-Limited-Partners-LPS-Portfolio-Management

## Top Limited Partners (LPs) Portfolio Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on LP Reporting, Fund Accounting Integration & Investor Portal Experiences*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Limited Partner (LP) Portfolio Management**. These tools help General Partners manage investor relationships, deliver capital account statements, distribute K-1s and notices, and provide LPs with self-service access to performance data and fund documents.

**Examples** include Carta, Juniper Square, Allvue Systems, Vessel, Dynamo Software, FundCount, eFront, iLevel, Burgiss, and Hemrock (the category leaders).

**Open-source emphasis**: This section is expanded with every major active project for self-hosting, custom LP reporting, and transparent fund accounting — ideal for emerging managers prioritizing data sovereignty, developers building fund operations platforms, and firms avoiding per-seat enterprise pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Carta](https://carta.com/)**  
  LP Portal positioned as an easy-to-navigate experience where LPs sign subscription documents, view investment-level performance, access vetted financial reports, and receive K-1s and distributions with one login [citation:1]. Extends cap table and fund administration capabilities for VC and PE firms. Strong investor workflow for digital subscription documents and self-serve document access [citation:8]. Validate where "system of record" lives for accounting-backed statements if you have strict close and audit workflows [citation:1].

- **[Juniper Square](https://www.junipersquare.com/)**  
  Connected investor experience with publish controls and engagement insight. Shortlist for primary goal of connected LP experience with governance and security posture [citation:1].

- **[Allvue Systems](https://www.allvuesystems.com/)**  
  Configurable, white-labeled portal that integrates with CRM and fund accounting. Suite-style option combining investor portal capabilities, fund accounting, and portfolio monitoring [citation:15]. Strong for firms wanting one vendor to cover multiple operational layers including portal distribution and back-office reporting [citation:1].

- **[Vessel](https://vessel.co/)**  
  AI-powered investor relations and fund management platform designed specifically for PE and VC fund managers. Founded by former LPs, built as an end-to-end system for the entire GP-LP lifecycle rather than a portal or CRM layered over legacy data [citation:8]. Unified real-time LP portal showing all funds, SPVs, co-investments, and managed accounts in one place with up-to-date balances, documents, and notices [citation:8].

- **[Dynamo Software](https://www.dynamosoftware.com/)**  
  Configurable platform for alternative asset managers combining deal management, research, portfolio monitoring, and investor relations. End-to-end coverage of deals, portfolios, and investor relations in one environment [citation:8]. Highly configurable workflows and fields. LP portal experience is solid but less of a key differentiator than some newer UX-focused platforms [citation:8]. Shortlist for branded data room style portal with tax documentation workflows [citation:1].

- **[FundCount](https://fundcount.com/)**  
  Portal publishing positioned as part of reporting workflow with portal integration with accounting engine [citation:1]. Start here if you need statements and investor reporting to reconcile to the accounting system of record [citation:1]. Tax documentation features emphasized for investor experience and seasonality workflows.

- **[eFront (BlackRock)](https://www.efront.com/)**  
  Investment Café is an investor relations portal layer for alternatives reporting. Cloud-based investor portal designed to simplify reporting requests by centralizing documents and giving investors secure access anytime [citation:15]. Best for VC and private markets managers needing modern portal for secure distribution of quarterly reports, statements, and notices in complex alternatives environments [citation:15].

- **[iLevel (S&P Global)](https://www.spglobal.com/)**  
  Specialized in portfolio data capture, performance analysis, and reporting. Manages fund-of-funds and multi-asset structures with granular data models. Often used alongside other investor relations tools that provide the LP portal. Ideal for large managers needing deep analytics and transparency rather than a polished LP experience [citation:8].

- **[Burgiss](https://www.burgiss.com/)**  
  Private capital data, analytics, and reporting platform for institutional investors and fund managers.

- **[Hemrock](https://www.hemrock.com/)**  
  Open-source portfolio reporting app with fund accounting, LP reporting, and MCP server. Apache 2.0 licensed, self-hostable. Built by a fund CFO for funds, SPVs, and angel investors [citation:2][citation:9].

## Open-Source GitHub Projects

- **[Hemrock Portfolio](https://github.com/hemrock/portfolio)**  
  **Open-source, self-hostable platform for running your investment firm in one place.** Apache 2.0 licensed [citation:9]. Four products: **Portfolio Reporting** (turn founder updates into structured metrics and LP reporting), **Investment Workflow** (deal pipeline and memo drafting), **LP Reporting** (capital account statements, fund-branded portal with AI analyst answering from LP's own materials), and **Fund Operations** (double-entry ledger per vehicle, bank feed import, calls and distributions, compliance calendar) [citation:12]. Accounting module uses **plain text files for journal entries** making data easy to import/export and AI-friendly [citation:2]. **MCP server** allows Claude or ChatGPT to access portfolio data with authentication [citation:2]. Self-host on Postgres and Node runtime with your own AI provider (Anthropic, OpenAI, OpenRouter, or self-hosted model) [citation:9][citation:12]. No per-seat fees.

- **[OpenGP](https://github.com/vivan1211/opengp)**  
  **Open-source AI intelligence platform for private equity** — AGPL-3.0 alternative to Rogo, Hebbia, and BlueFlame [citation:20]. Self-hosted multi-tenant platform for PE firms, fund managers, and family offices. Every AI answer grounded in your documents with clickable citations; everything runs in **your own AWS account** — data never leaves your cloud. Features **Cited AI chat (RAG)** over data room and portfolio, **Data room** with server-side parsing (OCR + tables), chunking, embeddings, hybrid retrieval (pgvector + full-text + rerank), **Portfolio analytics** (deal explorer, MOIC/IRR/DPI KPIs, sector/geography breakdowns, AI chart builder), **Model Builder** (describe analysis, writes and runs code in isolated sandbox, returns editable Excel models), **LP inbox** (email question to workspace, get cited draft answer; AI never emails LPs directly), **Multi-tenant & white-label** with per-workspace branding and Postgres row-level security [citation:20]. Full Terraform infrastructure (~77 resources) deployable into your AWS account. 2,200+ tests with CI on every PR [citation:20].

### Additional Strong Open-Source Options

- **Open-Source Captable** — TypeScript alternative to Carta, Pully, AngelList with 567+ GitHub stars. Manages cap tables and convertible notes for startups and funds [citation:10][citation:16].
- **Maybe Finance** — Open-source personal finance and wealth management platform (AGPL-3.0) originally commercial, now self-hostable. Investment tracking, net worth monitoring, multi-currency support, portfolio analysis, financial advisor access [citation:11].
- **Rotki** — Open-source, self-hosted portfolio manager, accounting, and analytics tool (AGPL-3.0). Privacy-focused with local encrypted data storage. Portfolio overview across platforms, PnL reports, transaction decoding [citation:4][citation:19]. Commercial licensing available for SaaS use [citation:19].
- **LibreFolio** — Self-hosted, open-source financial portfolio tracker. Tracks stocks, ETFs, crypto, bonds, and loans across multiple brokers with automated pricing, FX conversion, and technical analysis. Open cost basis (FIFO/WAC) and ROI (TWRR/MWRR) formulas at runtime [citation:5][citation:18].
- **ERPNext** — Full open-source ERP with accounting, CRM, and project management modules adaptable for fund operations and LP reporting [citation:6].
- **Odoo Community** — Open-source ERP with accounting, CRM, and document management modules for investment firm operations [citation:6].

**Frameworks for building custom systems**: Combine **Hemrock Portfolio** for portfolio reporting, LP statements, and fund accounting with MCP access, **OpenGP** for AI-native data room intelligence and cited RAG over fund documents, **Open-Source Captable** for cap table and convertible note management, and **ERPNext** or **Odoo** for general accounting and CRM workflows to build a complete self-hosted LP portfolio management stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- LP portfolio management tools handle sensitive financial data and investor communications. **LP reporting must be validated against fund accounting records** — discrepancies in capital account statements, K-1s, or performance metrics can have legal and tax consequences. AI-generated reports and analyses must be reviewed by qualified finance professionals before distribution to LPs.
- Self-hosted open-source solutions require proper security hardening, data encryption, backup strategies, and compliance with fund administration regulations.

---

**Made for fund managers, investor relations teams, fund accountants, and developers building LP portfolio management platforms.**  
Let's make LP portfolio management more open, transparent, and manager-friendly.
