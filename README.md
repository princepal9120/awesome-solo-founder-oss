# Awesome Solo Founder OSS

Open-source and source-available tools for solo founders building polished internet businesses.

Goal: help one person move from idea to shipped product, distribution, support, and revenue without buying a giant SaaS stack.

> Not a guarantee of revenue. This repo maps practical tools and workflows that can help a solo founder reach serious revenue targets.

## Why this list exists

Most startup lists mix paid tools, courses, credits, communities, and generic advice.

This list focuses on:

- OSS or source-available tools
- solo-founder useful workflows
- polished product building
- GTM, marketing, support, billing, analytics
- tools AI agents can operate through CLI, API, config, docs, or browser

## Similar repos researched

| Repo | Focus | Gap this repo fills |
| --- | --- | --- |
| [mezod/awesome-indie](https://github.com/mezod/awesome-indie) | Indie maker resources | Broad resources, not OSS-tool-stack first |
| [iAmCorey/awesome-indie-hacker-tools](https://github.com/iAmCorey/awesome-indie-hacker-tools) | Indie hacker tools | Useful, but mixed tool list, less lifecycle scoring |
| [KrishMunot/awesome-startup](https://github.com/KrishMunot/awesome-startup) | Startup resources | Broad startup resources, not solo + OSS execution stack |
| [xcomptek/awesome-saas-boilerplates](https://github.com/xcomptek/awesome-saas-boilerplates) | SaaS boilerplates | Strong build phase, not full business lifecycle |
| [EinGuterWaran/awesome-opensource-boilerplates](https://github.com/EinGuterWaran/awesome-opensource-boilerplates) | Open-source boilerplates | Build starter focus, not GTM/support/revenue |
| [open-saas-directory/awesome-saas-directory](https://github.com/open-saas-directory/awesome-saas-directory) | OSS SaaS projects | Directory angle, not founder operating system |
| [toofast1/awesome-micro-saas](https://github.com/toofast1/awesome-micro-saas) | Micro-SaaS stack | Good adjacent angle; this repo narrows to OSS + agent-ready |

## Selection rules

Good fit:

- Helps solo founder build, launch, sell, support, or grow.
- Has public source.
- Can be self-hosted, forked, scripted, or agent-operated.
- Has clear docs or usable examples.
- Replaces expensive SaaS cost center.

Avoid:

- Closed-source-only tools.
- Pure inspiration/motivation links.
- Abandoned repos with no clear maintenance path.
- Enterprise-only tools with unusable community edition.

## Founder lifecycle map

1. Idea and validation
2. Build MVP
3. Ship infrastructure
4. Analytics and feedback
5. Marketing and distribution
6. Sales, CRM, support
7. Billing and monetization
8. Docs, polish, trust
9. Automation and AI-agent operations

## Core stack

### Build MVP

| Project | Use |
| --- | --- |
| [supabase/supabase](https://github.com/supabase/supabase) | Backend, auth, database, storage |
| [appwrite/appwrite](https://github.com/appwrite/appwrite) | Backend platform |
| [pocketbase/pocketbase](https://github.com/pocketbase/pocketbase) | Tiny backend for fast MVPs |
| [wasp-lang/open-saas](https://github.com/wasp-lang/open-saas) | Free SaaS starter with auth, jobs, payments |
| [ixartz/SaaS-Boilerplate](https://github.com/ixartz/SaaS-Boilerplate) | Next.js SaaS boilerplate |

### Deploy and operate

| Project | Use |
| --- | --- |
| [coollabsio/coolify](https://github.com/coollabsio/coolify) | Self-hosted Vercel/Heroku alternative |
| [Dokploy/dokploy](https://github.com/Dokploy/dokploy) | Deployment platform |
| [caprover/caprover](https://github.com/caprover/caprover) | App deployment platform |
| [dokku/dokku](https://github.com/dokku/dokku) | Lightweight Heroku-style PaaS |
| [openstatusHQ/openstatus](https://github.com/openstatusHQ/openstatus) | Uptime monitoring and status pages |

### Analytics and product learning

| Project | Use |
| --- | --- |
| [PostHog/posthog](https://github.com/PostHog/posthog) | Product analytics, session replay, flags, surveys |
| [plausible/analytics](https://github.com/plausible/analytics) | Privacy-friendly web analytics |
| [umami-software/umami](https://github.com/umami-software/umami) | Simple web analytics |
| [Openpanel-dev/openpanel](https://github.com/Openpanel-dev/openpanel) | Product and web analytics |
| [formbricks/formbricks](https://github.com/formbricks/formbricks) | User research and surveys |

### Marketing and distribution

| Project | Use |
| --- | --- |
| [mautic/mautic](https://github.com/mautic/mautic) | Marketing automation |
| [knadh/listmonk](https://github.com/knadh/listmonk) | Newsletter and mailing lists |
| [usesend/useSend](https://github.com/usesend/useSend) | Transactional email platform |
| [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app) | Social media scheduling |
| [trypostit/trypost](https://github.com/trypostit/trypost) | Social media scheduling |
| [nitishkgupta/seotoolsuite](https://github.com/nitishkgupta/seotoolsuite) | SEO tooling |
| [respectlytics/respectaso](https://github.com/respectlytics/respectaso) | App Store Optimization keyword research |
| [jawwadfirdousi/appstore-screenshots-generator](https://github.com/jawwadfirdousi/appstore-screenshots-generator) | App Store screenshots |

### Sales, CRM, and support

| Project | Use |
| --- | --- |
| [twentyhq/twenty](https://github.com/twentyhq/twenty) | Modern CRM |
| [espocrm/espocrm](https://github.com/espocrm/espocrm) | CRM |
| [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot) | Customer support inbox and live chat |
| [frappe/helpdesk](https://github.com/frappe/helpdesk) | Helpdesk |
| [getfider/fider](https://github.com/getfider/fider) | Feature requests and feedback voting |
| [OpnForm/OpnForm](https://github.com/OpnForm/OpnForm) | Form builder |
| [heyform/heyform](https://github.com/heyform/heyform) | Form builder |

### Billing and monetization

| Project | Use |
| --- | --- |
| [polarsource/polar](https://github.com/polarsource/polar) | Developer payments, subscriptions, digital products |
| [getlago/lago](https://github.com/getlago/lago) | Usage-based billing |
| [killbill/killbill](https://github.com/killbill/killbill) | Subscription billing platform |

### Docs, website, and polish

| Project | Use |
| --- | --- |
| [facebook/docusaurus](https://github.com/facebook/docusaurus) | Documentation website |
| [docmost/docmost](https://github.com/docmost/docmost) | Knowledge base |
| [withastro/astro](https://github.com/withastro/astro) | Marketing/docs website framework |
| [plasmicapp/plasmic](https://github.com/plasmicapp/plasmic) | Visual builder for React |
| [GrapesJS/grapesjs](https://github.com/GrapesJS/grapesjs) | Web page builder framework |

### Automation and AI-agent operations

| Project | Use |
| --- | --- |
| [activepieces/activepieces](https://github.com/activepieces/activepieces) | Workflow automation, MCP, AI agents |
| [n8n-io/n8n](https://github.com/n8n-io/n8n) | Workflow automation with native AI features |

## Agent-readiness score

Use this when adding tools:

| Score | Meaning |
| --- | --- |
| 5 | CLI/API/docs/docker; agent can install, configure, and run workflows |
| 4 | API/docs good; minor manual setup |
| 3 | Browser-first; agent can operate but setup is slower |
| 2 | Good product, weak automation surface |
| 1 | Mostly manual |

## Suggested folder expansion

- `data/tools.yml` — structured database
- `playbooks/` — founder workflows
- `agent-recipes/` — OpenClaw/Codex/Claude/Cursor workflows
- `templates/` — launch copy, app store copy, pricing checklist

## Contributing

PRs welcome. Add tools with:

- repository URL
- license
- category
- best founder stage
- agent-readiness score
- reason it helps solo founders

