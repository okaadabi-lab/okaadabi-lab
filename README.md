### Oka Samdya Adabi

Software developer focused on web development, backend systems, automation, data and AI integration.
Based in Bekasi, Indonesia.

I build the software small service businesses run on: booking and payment flows, HR and payroll
backends, the automation that connects customer channels to those systems, and the data work that
keeps customer records usable. Most of my client work has been business websites, n8n automation
(chat admin, Instagram/TikTok replies, Telegram and WhatsApp integrations, HR and payroll
processes) and technical SEO. The repositories below are portfolio projects built to show how I
approach that work when there is room to do it properly.

#### Featured projects

| Project | What it is | Stack |
|---|---|---|
| [event-booking-system](https://github.com/okaadabi-lab/event-booking-system) | Booking and operations app for a decoration and venue rental business: quotes, double-booking prevention with row locks, deposits, role-based access. | PHP, Slim, MySQL, Twig |
| [hr-payroll-api](https://github.com/okaadabi-lab/hr-payroll-api) | REST API for attendance, overtime approval and payroll under Indonesian rules (PP 35/2021, BPJS), with idempotent runs, period locking and a transactional outbox. | PHP, Slim, MySQL, JWT, OpenAPI |
| [ai-support-service](https://github.com/okaadabi-lab/ai-support-service) | Support message service that answers only from a knowledge base, validates LLM output (no invented prices or promises) and escalates to a human. | TypeScript, Fastify, SQLite, Claude API |
| [omnichannel-inbox-automation](https://github.com/okaadabi-lab/omnichannel-inbox-automation) | n8n workflows joining WhatsApp, Instagram and Telegram into one pipeline, with signed webhooks, retries and tested Code-node logic. Calls the two services above. | n8n, JavaScript, MySQL |
| [customer-data-pipeline](https://github.com/okaadabi-lab/customer-data-pipeline) | Consolidates leads from spreadsheets, form exports and an API into one deduplicated customer table with lineage and a review queue. | TypeScript, SQLite |
| [seo-audit-crawler](https://github.com/okaadabi-lab/seo-audit-crawler) | Technical SEO crawler and CLI: 33 rules, run history, "what changed since last audit" report, CI gate. | TypeScript, Node.js |

#### Tech I work with

- **Backend:** PHP (Slim), Node.js / TypeScript (Fastify), REST API design, JWT, OpenAPI
- **Data:** MySQL / MariaDB, SQLite, SQL schema design, ETL and data cleaning
- **Frontend:** HTML, CSS, JavaScript, server-rendered UI, responsive and accessible layouts
- **Automation and AI:** n8n, webhooks, WhatsApp Cloud API, Instagram Messaging, Telegram Bot API, Claude API
- **Quality:** PHPUnit, Vitest, PHPStan, ESLint, GitHub Actions
- **SEO:** technical audits, structured data, sitemaps and crawlability

#### How these were built

I use AI assistants (Claude) as part of my development workflow, the same way I use a linter or
a debugger. Design decisions, trade-offs and limitations are written down in each repository, and
I can walk through any of them.

#### Contact

oka.s.adabi@gmail.com
