# Awesome-Sales-Engagement-Platform-Sep

# Top Sales Engagement Platform (SEP) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Multi-Channel Sequences, Outreach Automation & Self-Hosted Engagement Platforms*  
**Last updated: October 2026**

This repository tracks notable **commercial sales engagement platforms** and **open-source projects** that automate multi-channel outreach — email sequences, LinkedIn actions, calling, and personalized follow-ups — to help sales teams book more meetings and engage prospects at scale.

**Examples** include Salesforce Sales Engagement, Salesloft, Outreach, Groove, Apollo.io, Yesware, Mixmax, Mailshake, Woodpecker, and Reply.io (the category leaders).

**Open-source emphasis**: Sales engagement is a rapidly growing open-source domain. **Linki** leads as a self-hosted LinkedIn and cold email AI SDR with multichannel campaigns, server-side LinkedIn login, and unified inbox . **Emareach** delivers production-grade email outreach with deliverability warm-up, SPF/DKIM/DMARC checks, and billing infrastructure . **OutreachPro** brings a complete self-hosted Instantly.ai clone with Claude AI personalization, Google Maps scraping, and CRM pipeline . **Signal** provides AI sales intelligence with buying signal detection, contact enrichment, and multi-step email sequences . **OpenOutreach** offers autonomous B2B lead discovery with licensed data and LLM qualification . **Radiant AI CRM** acts as an autonomous AI sales rep that analyzes pipeline and drafts next actions . **Mautic** delivers the deepest open-source marketing automation with visual campaign builder and lead scoring .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesloft](https://www.salesloft.com/)**  
  **The enterprise SEP standard** — multi-channel cadences, conversation intelligence, and revenue intelligence. **Best for enterprise sales teams**.

- **[Outreach](https://www.outreach.io/)**  
  **Leading sales engagement platform** — sequences, deal intelligence, and revenue operations. **Best for data-driven sales organizations**.

- **[Apollo.io](https://www.apollo.io/)**  
  **All-in-one sales intelligence and engagement** — 275M+ contact database, email sequences, and dialer. **Best for SMBs wanting data + outreach in one**.

- **[Groove](https://www.groove.co/)**  
  **Sales engagement for Salesforce** — native integration with Salesforce for activity capture and sequences. **Best for Salesforce-centric teams**.

- **[Yesware](https://www.yesware.com/)**  
  **Email engagement for Gmail and Outlook** — tracking, templates, and sequences. **Best for individual reps and small teams**.

- **[Mixmax](https://mixmax.com/)**  
  **Email engagement with scheduling** — sequences, polls, and meeting scheduling. **Best for Gmail power users**.

- **[Mailshake](https://mailshake.com/)**  
  **Cold email and sales engagement** — sequences, lead catcher, and phone dialer. **Best for cold outreach focused teams**.

- **[Woodpecker](https://woodpecker.co/)**  
  **Cold email automation** — sequences, A/B testing, and deliverability tools. **Best for agencies and SMBs**.

- **[Reply.io](https://reply.io/)**  
  **Multi-channel sales engagement** — email, LinkedIn, and calling sequences with AI SDR. **Best for multi-channel outreach**.

- **[Salesforce Sales Engagement](https://www.salesforce.com/)**  
  **Salesforce's native SEP** — cadences, email tracking, and Einstein AI integration. **Best for Salesforce customers**.

## Open-Source GitHub Projects

### Multi-Channel Outreach Platforms

- **[Linki](https://github.com/moaljumaa/linki)**  
  **Open-source AI SDR for B2B outreach**, open-source . **LinkedIn sequences, cold email, and lead enrichment — self-hosted, no per-seat pricing** . **Multichannel campaigns** — LinkedIn actions (visit, connect, message) and email actions in parallel within a single campaign sequence . **Server-side LinkedIn login** — headless authentication with pinned browser fingerprint, handles LinkedIn's real challenges including email/SMS codes and mobile-app device approval . **63% improvement in connection reliability** . **Sales Navigator import** and **Apollo.io enrichment** . **Unified inbox** with email + LinkedIn reply detection . **Best for teams wanting full LinkedIn + email outreach control**.

- **[Emareach](https://github.com/ritik-prog/emareach)**  
  **Production-grade, open-source AI email marketing platform with automation, campaigns, deliverability, analytics, and self-hosting** . **Campaigns** — sequences, scheduling, per-inbox sending limits, A/B templates . **Deliverability & warm-up** — mailbox warm-up with LLM-generated threads, spam→inbox recovery, SPF/DKIM/DMARC checks . **Inboxes** — connect Gmail/Outlook via OAuth or SMTP/IMAP app passwords . **Billing** — Razorpay (India) and Lemon Squeezy (international) plans . **Admin panel** — user, plan, warm-up, and infrastructure management . **Tech stack**: FastAPI, Next.js 15, MongoDB, Terraform/Caddy . **Best for production email outreach with billing and admin**.

- **[OutreachPro](https://socket.dev/npm/package/outreachpro)**  
  **AI-powered B2B sales engagement platform — self-hosted Instantly.ai clone**, MIT licensed . **Google Maps scraper** — find local businesses via Apify, auto-import leads . **Claude AI personalisation** — unique opening line per lead using business data . **Campaign sequences** — multi-step emails with delays, stop-on-reply, daily limits . **Unibox** — unified reply inbox with AI auto-labelling (Interested / Not now / Meeting) . **CRM pipeline** — Kanban from Prospect → Won, drag-and-drop, pipeline value . **Email warmup** — slow-ramp sending to build sender reputation . **6-language i18n** — EN / DE / FR / ES / IT / NL . **One Docker command to run** . **Best for self-hosted cold email with AI personalization**.

### AI Sales Intelligence & Outreach

- **[Signal](https://github.com/jay-sahnan/signal)**  
  **Open-source AI sales intelligence and outreach automation** — the open alternative to Clay, Apollo, and Outreach . **Signals engine** — authorable "recipes" that watch companies and surface buying triggers (hiring changes, funding news, product launches, review shifts) . **Contact enrichment** — pulls LinkedIn, GitHub, and company pages into a single profile . **Outreach sequences** — multi-step emails sent from your own Gmail with reply/bounce tracking . **Browser automation** — Browserbase + Stagehand for sites without APIs . **Own your data** — Postgres + RLS on your Supabase; bring your own LLM keys . **Tech stack**: Next.js 16, Supabase, Anthropic Claude, Tailwind CSS 4 . **Best for AI-powered signal-based outreach**.

- **[OpenOutreach](https://pypi.org/project/openoutreach/)**  
  **Autonomous lead discovery and qualification agent for B2B sales**, open-source . **Autonomous Lead Discovery** — LLM turns your product + objective into opening keywords, grows them by counting words appearing in accepted profiles . **A Reason Per Lead** — every qualified lead carries the LLM's written rationale for choosing it . **Licensed Discovery** — firmographic profiles from licensed provider (BetterContact Lead Finder), no scraping . **Built-in CRM** — Django Admin for browsing Leads, Companies and Deals . **Stateful Pipeline** — fully resumable, nothing scheduled in advance . **One-Command Install** — `uvx openoutreach find 10` . **Best for autonomous lead generation**.

- **[Radiant AI CRM](https://github.com/dylanmeyford/radiant-ai-crm-oss)**  
  **Open-source AI CRM that acts as an agent to proactively run sales**, open-source . **Connects to email and calendar** — no data entry, no manual syncing . **Analyzes every activity automatically** — emails, meetings, and interactions processed into actionable intelligence . **Joins and analyses every meeting** — extracts key insights, updates CRM automatically . **Processes every deal and drafts the next best action** . **Consumes files and playbooks** — learns your process and follows it . **Researches and enriches contacts and deals** . **Tech stack**: TypeScript, Express, MongoDB, Stripe, Nylas, React/Vite . **Best for autonomous AI-driven sales**.

### Email Marketing & Automation Foundations

- **[Mautic](https://github.com/mautic/mautic)**  
  **The world's largest open-source marketing automation platform**, GPL licensed with **10,532 GitHub stars, 3,453 forks, and 13 years of development** . **Used by 40,000+ companies** . **Features**: drag-and-drop campaign builder, email and landing page creation, contact management with lead scoring, segments, forms, and REST API . **The deepest automation builder in open source** — multi-step campaigns, conditional branches on opens and clicks, lead scoring . **Trade-off**: Heavy stack — web server, PHP-FPM, MySQL, cron, and queue; first installs commonly take days to tune  . **Best for comprehensive open-source marketing automation**.

- **[Listmonk](https://github.com/knadh/listmonk)**  
  **High-performance newsletter and mailing list manager**, AGPL-3.0 licensed with **23,200+ GitHub stars** . **Single Go binary** with Vue UI — minimal dependencies, only PostgreSQL required . **Send millions of emails from your own SMTP** with no per-subscriber pricing . **Subscriber management, campaign analytics, and segmentation** . **The de facto open-source newsletter alternative** — but **no built-in automation, drip sequences, or triggered emails**  . **Best for high-volume newsletters and mailing lists**.

### Additional Strong Open-Source Options

- **Zenvio** — Sales engagement platform with email outreach, WhatsApp/Instagram/Messenger team inbox, CRM, and visual automation builder .
- **reachgenie** — AI-powered sales automation with email campaigns, AI enrichment, and Bland AI call execution .
- **Gmail MCP Agent** — Open-source Gmail outreach and lead nurturing via MCP, with CSV-driven outreach and automated follow-up sequences .
- **opengtm** — AI-powered lead discovery, ICP scoring, and outreach sequences with Claude Code integration, MIT licensed .
- **b2b-lead-intelligence** — Python SDK for B2B company and decision-maker lead intelligence, open-source Apollo/Proxycurl alternative .
- **Linki** — Already listed. **Self-hosted LinkedIn + email AI SDR** .

**Frameworks for building custom SEP solutions**: Combine **Linki** for multi-channel LinkedIn + email outreach with server-side authentication and unified inbox . Use **Emareach** for production email campaigns with deliverability warm-up and billing infrastructure . Deploy **Signal** for AI-powered buying signal detection and signal-based outreach sequences . Integrate **Mautic** when deep marketing automation with visual campaign builder and lead scoring is required . Choose **Listmonk** for high-volume newsletter delivery with minimal operational overhead . Use **OutreachPro** for a complete self-hosted Instantly.ai alternative with Claude AI personalization . Note that true enterprise SEP with AI-powered conversation intelligence, real-time coaching, and vendor-supported SLAs (Salesloft, Outreach, Apollo.io) remains primarily commercial territory; open-source stacks provide strong multi-channel sequences, AI personalization, and deliverability foundations that require integration for complete sales engagement operations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Sales engagement platforms handle sensitive prospect data and may process PII. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA, CAN-SPAM, CASL).
- **Email deliverability requires IP reputation management** — self-hosted platforms must warm up IPs, configure SPF/DKIM/DMARC, and monitor blacklists. Commercial platforms provide managed deliverability .
- **LinkedIn automation carries account risk** — server-side login and human-like pacing reduce but do not eliminate the risk of account restrictions. Use responsibly and within LinkedIn's terms of service .
- **License considerations**: Linki is open-source , Emareach is open-source , OutreachPro uses MIT , Signal is open-source , Mautic uses GPL , and Listmonk uses AGPL-3.0 . Verify licensing against your use case before committing.
- The open-source ecosystem provides strong multi-channel sequences, AI personalization, and deliverability foundations, but **AI-powered conversation intelligence, real-time coaching, and vendor-supported SLAs** remain primarily commercial offerings.
