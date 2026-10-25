### Hi, I'm Lucas Barcellos 👋

Co-founder at a paid traffic agency in Brazil. I build the tools behind our media buying: lead routing, tracking, data pipelines and AI agents that decide (and act) on Google and Meta ads, judged by what happens in the CRM, not by platform conversions.

Most of this lives in private repositories. Here is what I work on:

**💬 AI sales agent for WhatsApp, Instagram and Messenger**
A multi-tenant product where an AI agent answers leads in the business's own voice and works the sale:
- Tool calling: shows store locations on a map, sends product and property cards from the live Meta catalog, books visits on Google Calendar / Meet and collects data through native WhatsApp Flows forms.
- Runs the pipeline: moves each lead through the company's own editable funnel, sets lead temperature from the conversation, schedules follow-ups and returns within business hours, and hands off to a human when needed.
- Learns from its own mistakes: generates and applies lessons automatically to improve its answers.
- Website chat widget that reuses the same brain, competitor "x-ray" with AI image analysis, and a live call copilot that reads meeting captions and suggests answers in real time.
- Team roles and access, prepaid credits per conversation, and a signed webhook that sends qualified leads to the client's CRM.

**🚀 Lead routing product**
Leads from Meta lead forms delivered to each client's CRM in real time, with field mapping, filters and per-CRM presets. Guided onboarding with automatic page connection, and a background reconciliation job that catches any lead the webhook missed. A standalone product with its own auth, database and tenants, running for real estate and auto dealer clients.

**📡 First-party tracking**
Built most of our tracking layer: event ingestion, server-side delivery with retries, CRM webhooks, domain verification, keyword and click-id capture, and "companies that visited" enrichment. Feeds Google offline conversions and the Meta Conversions API.

**🗄️ Data lake and analytics**
Pipelines that join ad platforms, CRMs and our own tracking into one model of the funnel (lead, contact, opportunity, sale). Regional intelligence with census data, company radar and AI search visibility (GEO) monitoring.

**🤖 Google Ads recommendation engine**
An engine that scores every lever against real CRM outcomes. A panel of 8 AI specialists (strategy, critic, results, data, auction, sales, creative, market) debates each recommendation with read access to live accounts, CRM and past lessons. It writes ad copy, plans the month, learns new rules from its own mistakes, and executes through the Google Ads API (validated first, with undo) or on screen through a browser agent when the API can't.

**🎯 Campaign and creative operations**
Automated campaign launch and evaluation on Meta and Google, creative performance ranking, and sales attribution from the CRM back to each ad.

**Stack:** TypeScript, Node.js, React, Postgres (Supabase), edge functions, Google Ads API, Meta Marketing / Conversions / WhatsApp Cloud / Instagram APIs, Claude.
