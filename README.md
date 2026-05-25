<p align="center">
  <img src="assets/logo.svg" alt="Awesome Solo Founder OSS logo" width="760">
</p>

<h1 align="center">Awesome Solo Founder OSS</h1>

<p align="center">
  <strong>OSS/source-available stack for solo founders to build, launch, sell, support, automate, and grow products.</strong>
</p>

<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://awesome.re/badge.svg">
  </a>
  <a href="https://github.com/princepal9120/awesome-solo-founder-oss/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/princepal9120/awesome-solo-founder-oss?style=social">
  </a>
  <a href="CONTRIBUTING.md">
    <img alt="Contributions welcome" src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg">
  </a>
</p>

Founder-focused open-source and source-available tools for the whole journey: idea research, design, MVP, auth, database, AI agents, billing, analytics, email, support, marketing, docs, deployment, security, productivity, and starter kits.

> Revenue is not guaranteed. This list helps solo founders reduce stack cost, move faster, and pick practical tools.

## Quick Start

Pick the job, then pick one tool.

| Founder job | Start here |
| --- | --- |
| Validate demand | [last30days-skill](https://github.com/mvanhorn/last30days-skill), [rdt-cli](https://github.com/public-clis/rdt-cli), [twitter-cli](https://github.com/public-clis/twitter-cli) |
| Ship a SaaS MVP | [Open SaaS](https://github.com/wasp-lang/open-saas), [Supabase](https://github.com/supabase/supabase), [Coolify](https://github.com/coollabsio/coolify) |
| Add auth | [Better Auth](https://github.com/better-auth/better-auth), [Auth.js](https://github.com/nextauthjs/next-auth), [Logto](https://github.com/logto-io/logto) |
| Add payments | [Polar](https://github.com/polarsource/polar), [Lago](https://github.com/getlago/lago) |
| Track users | [PostHog](https://github.com/PostHog/posthog), [Umami](https://github.com/umami-software/umami), [Plausible](https://github.com/plausible/analytics) |
| Send lifecycle emails | [Listmonk](https://github.com/knadh/listmonk), [Dittofeed](https://github.com/dittofeed/dittofeed), [useSend](https://github.com/usesend/useSend) |
| Market the product | [Dub](https://github.com/dubinc/dub), [Papermark](https://github.com/papermark/papermark), [Postiz](https://github.com/gitroomhq/postiz-app) |
| Make launch assets | [OpenScreen](https://github.com/siddharthvaddem/openscreen), [Hyperframes](https://github.com/heygen-com/hyperframes), [Remotion](https://github.com/remotion-dev/remotion) |
| Edit raw video | [vex](https://github.com/AKMessi/vex), [VibeFrame](https://github.com/vericontext/vibeframe), [auto-editor](https://github.com/WyattBlue/auto-editor) |
| Build with agents | [Codex](https://github.com/openai/codex), [Claude Code](https://github.com/anthropics/claude-code), [XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) |

## Opinionated Stacks

### Lean SaaS stack

- Starter: [Open SaaS](https://github.com/wasp-lang/open-saas)
- Backend/database/auth: [Supabase](https://github.com/supabase/supabase)
- Billing: [Polar](https://github.com/polarsource/polar)
- Analytics: [PostHog](https://github.com/PostHog/posthog)
- Email: [Listmonk](https://github.com/knadh/listmonk)
- Deploy: [Coolify](https://github.com/coollabsio/coolify)
- Support: [Chatwoot](https://github.com/chatwoot/chatwoot)

### Mobile app launch stack

- Build/release: [fastlane](https://github.com/fastlane/fastlane)
- iOS agent loop: [XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP)
- App previews: [video-preview-appstore](https://github.com/mdo91/video-preview-appstore)
- Screenshots: [App Store Screenshots Generator](https://github.com/jawwadfirdousi/appstore-screenshots-generator), [Appshot](https://github.com/chrisvanbuskirk/appshot)
- Demo video: [OpenScreen](https://github.com/siddharthvaddem/openscreen)

### Agent-first build stack

- Coding: [Codex](https://github.com/openai/codex), [Claude Code](https://github.com/anthropics/claude-code)
- Browser QA: [Playwright MCP](https://github.com/microsoft/playwright-mcp)
- Fresh docs: [Context7](https://github.com/upstash/context7)
- GitHub ops: [GitHub MCP Server](https://github.com/github/github-mcp-server)
- Design-to-code: [Figma Context MCP](https://github.com/GLips/Figma-Context-MCP)

### Product marketing stack

- Link attribution: [Dub](https://github.com/dubinc/dub)
- Deck/proposal analytics: [Papermark](https://github.com/papermark/papermark)
- Blog/newsletter: [Ghost](https://github.com/TryGhost/Ghost)
- Social publishing: [Postiz](https://github.com/gitroomhq/postiz-app), [Mixpost](https://github.com/inovector/mixpost)
- Content video: [ViralMint](https://github.com/openclaw-easy/ViralMint), [OpenShorts](https://github.com/mutonby/openshorts)

## Selection Criteria

Tools should satisfy most of these:

- Public source exists.
- Useful for one-person companies.
- Helps build, launch, sell, support, automate, or grow.
- Maintained recently or has a stable community.
- Can be self-hosted, forked, scripted, API-driven, CLI-driven, MCP-driven, or agent-operated.
- Clear docs or practical examples exist.
- Replaces a real SaaS cost center or a high-friction manual workflow.

Avoid:

- Closed-source-only tools.
- Abandoned repos.
- Generic inspiration links.
- Startup-credit lists.
- Enterprise-only products with unusable community editions.
- Duplicate tools unless they serve clearly different founder jobs.

## Contents

- [Ideation and validation](#ideation-and-validation)
- [Design and UX](#design-and-ux)
- [Starter kits](#starter-kits)
- [MVP development](#mvp-development)
- [Auth and identity](#auth-and-identity)
- [Database and backend](#database-and-backend)
- [AI agents and MCP](#ai-agents-and-mcp)
- [Billing and monetization](#billing-and-monetization)
- [Analytics and feedback](#analytics-and-feedback)
- [Email and lifecycle messaging](#email-and-lifecycle-messaging)
- [Support, CRM, and community](#support-crm-and-community)
- [Marketing and growth](#marketing-and-growth)
- [Content and video](#content-and-video)
- [Docs and knowledge base](#docs-and-knowledge-base)
- [Deployment and operations](#deployment-and-operations)
- [Security and legal](#security-and-legal)
- [Productivity](#productivity)
- [Contributing](#contributing)

## Ideation and validation

Find painful problems, communities, keywords, and trend signals.

| Tool | Use |
| --- | --- |
| [last30days-skill](https://github.com/mvanhorn/last30days-skill) | Recent-topic research across Reddit, X, YouTube, HN, Polymarket, and web |
| [lastXdays-skill](https://github.com/levineam/lastXdays-skill) | Configurable time-range version of last30days research |
| [twitter-cli](https://github.com/public-clis/twitter-cli) | X/Twitter feed, bookmarks, and timeline research in terminal |
| [rdt-cli](https://github.com/public-clis/rdt-cli) | Reddit feeds, posts, search, saves, and subscriptions in terminal |
| [ig-cli](https://github.com/princepal9120/ig-cli) | Instagram trend discovery and content research |
| [tkt-cli](https://github.com/princepal9120/tkt-cli) | TikTok trend discovery for terminal-first research |
| [linkedin-cli](https://github.com/Linked-API/linkedin-cli) | Agent-friendly LinkedIn data and account CLI |
| [Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Multi-platform search/read CLI for agents |
| [MediaCrawler](https://github.com/NanmiCoder/MediaCrawler) | Crawls Xiaohongshu, Douyin, Kuaishou, Bilibili, Weibo, Tieba, Zhihu |

Playbook: [trend-to-content engine](playbooks/trend-to-content-engine.md)

## Design and UX

Create landing pages, prototypes, and design-to-code workflows.

| Tool | Use |
| --- | --- |
| [Webstudio](https://github.com/webstudio-is/webstudio) | Open-source Webflow alternative |
| [Plasmic](https://github.com/plasmicapp/plasmic) | Visual builder for React apps, sites, and content |
| [GrapesJS](https://github.com/GrapesJS/grapesjs) | Open-source web builder framework |
| [Figma Context MCP](https://github.com/GLips/Figma-Context-MCP) | Figma layout context for AI coding agents |
| [Hyperframes](https://github.com/heygen-com/hyperframes) | HTML-to-video motion graphics for launch explainers |

## Starter kits

Start with a product-shaped repo instead of a blank folder.

| Tool | Use |
| --- | --- |
| [Open SaaS](https://github.com/wasp-lang/open-saas) | SaaS starter with auth, jobs, payments, landing page |
| [SaaS Boilerplate](https://github.com/ixartz/SaaS-Boilerplate) | Next.js SaaS starter |
| [XcodeBuildMCP iOS Template](https://github.com/getsentry/XcodeBuildMCP-iOS-Template) | iOS starter template for agent-assisted builds |

## MVP development

Build the first useful product slice.

| Tool | Use |
| --- | --- |
| [Payload](https://github.com/payloadcms/payload) | Full-stack Next.js backend, admin panel, and CMS |
| [JeecgBoot](https://github.com/jeecgboot/JeecgBoot) | AI low-code app builder |
| [Budibase](https://github.com/Budibase/budibase) | Internal apps, automations, and operations tools |
| [ToolJet](https://github.com/ToolJet/ToolJet) | App builder and AI workflow foundation |

## Auth and identity

Add accounts, sessions, teams, and SaaS-ready identity.

| Tool | Use |
| --- | --- |
| [Better Auth](https://github.com/better-auth/better-auth) | TypeScript authentication framework |
| [Auth.js](https://github.com/nextauthjs/next-auth) | Web authentication library |
| [Logto](https://github.com/logto-io/logto) | Auth and authorization infrastructure for SaaS and AI apps |

## Database and backend

Store users, content, files, events, and product data.

| Tool | Use |
| --- | --- |
| [Supabase](https://github.com/supabase/supabase) | Postgres, auth, storage, realtime, edge functions |
| [PocketBase](https://github.com/pocketbase/pocketbase) | SQLite-backed app backend in one binary |
| [Appwrite](https://github.com/appwrite/appwrite) | Backend APIs for auth, database, storage, functions |
| [Directus](https://github.com/directus/directus) | Headless CMS and data platform over SQL |

## AI agents and MCP

Use agents to code, test, browse, inspect design, and run product workflows.

| Tool | Use |
| --- | --- |
| [Codex](https://github.com/openai/codex) | Terminal coding agent |
| [Claude Code](https://github.com/anthropics/claude-code) | Agentic coding tool in terminal |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | Open-source Gemini coding and research agent |
| [OpenCode](https://github.com/anomalyco/opencode) | Open-source multi-model coding agent |
| [Qwen Code](https://github.com/QwenLM/qwen-code) | Open-source terminal coding agent |
| [XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) | iOS/macOS build, test, simulator, and logs for agents |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | Browser automation and QA for agents |
| [GitHub MCP Server](https://github.com/github/github-mcp-server) | GitHub issues, PRs, repos, and code workflow |
| [Context7](https://github.com/upstash/context7) | Fresh docs for LLMs and code editors |
| [MCP Servers](https://github.com/modelcontextprotocol/servers) | Model Context Protocol server collection |
| [MCP Registry](https://github.com/modelcontextprotocol/registry) | Community registry for MCP servers |
| [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Curated MCP server list |
| [UI-TARS Desktop](https://github.com/bytedance/UI-TARS-desktop) | Open-source multimodal desktop agent stack |
| [CowAgent](https://github.com/zhayujie/CowAgent) | AI assistant and agent harness |
| [CodeWhale](https://github.com/Hmbown/CodeWhale) | DeepSeek-first agentic coding terminal |

Playbook: [agent-assisted product build sprint](playbooks/agent-assisted-product-build-sprint.md)

## Billing and monetization

Charge customers, meter usage, and handle subscriptions.

| Tool | Use |
| --- | --- |
| [Polar](https://github.com/polarsource/polar) | Developer-product payments, subscriptions, digital products |
| [Lago](https://github.com/getlago/lago) | Usage-based billing and metering |
| [Kill Bill](https://github.com/killbill/killbill) | Subscription billing platform |

## Analytics and feedback

Learn what users do and what they need.

| Tool | Use |
| --- | --- |
| [PostHog](https://github.com/PostHog/posthog) | Product analytics, replay, flags, surveys |
| [Plausible](https://github.com/plausible/analytics) | Privacy-friendly web analytics |
| [Umami](https://github.com/umami-software/umami) | Simple self-hosted web analytics |
| [GrowthBook](https://github.com/growthbook/growthbook) | Feature flags, experiments, product analytics |
| [Formbricks](https://github.com/formbricks/formbricks) | User research and surveys |
| [Fider](https://github.com/getfider/fider) | Feature requests and feedback voting |

## Email and lifecycle messaging

Send newsletters, onboarding, transactional mail, and lifecycle nudges.

| Tool | Use |
| --- | --- |
| [Listmonk](https://github.com/knadh/listmonk) | Newsletter and mailing lists |
| [Mautic](https://github.com/mautic/mautic) | Marketing automation |
| [Dittofeed](https://github.com/dittofeed/dittofeed) | Customer engagement across email, SMS, push, WhatsApp, Slack |
| [useSend](https://github.com/usesend/useSend) | Open-source transactional email platform |
| [Ghost](https://github.com/TryGhost/Ghost) | Publishing, newsletters, memberships, subscriptions |

## Support, CRM, and community

Talk to users, close deals, and build community loops.

| Tool | Use |
| --- | --- |
| [Twenty](https://github.com/twentyhq/twenty) | Modern CRM |
| [EspoCRM](https://github.com/espocrm/espocrm) | CRM |
| [Chatwoot](https://github.com/chatwoot/chatwoot) | Support inbox and live chat |
| [Frappe Helpdesk](https://github.com/frappe/helpdesk) | Helpdesk |
| [Typebot](https://github.com/baptisteArno/typebot.io) | Chatbot and funnel builder |
| [Cal.com](https://github.com/calcom/cal.diy) | Scheduling for demos, sales calls, onboarding |
| [Discourse](https://github.com/discourse/discourse) | Community forum |
| [Forem](https://github.com/forem/forem) | Community publishing platform |

## Marketing and growth

Create demand, track campaigns, publish content, and convert leads.

| Tool | Use |
| --- | --- |
| [Dub](https://github.com/dubinc/dub) | Link attribution, short links, QR codes, campaign tracking |
| [Papermark](https://github.com/papermark/papermark) | DocSend alternative for pitch decks, proposals, document analytics |
| [Postiz](https://github.com/gitroomhq/postiz-app) | Agentic social media scheduling |
| [Mixpost](https://github.com/inovector/mixpost) | Self-hosted social media management |
| [TryPost](https://github.com/trypostit/trypost) | Social scheduling and content calendar |
| [LateWiz](https://github.com/zernio-dev/latewiz) | Multi-platform social scheduler |
| [LinkStack](https://github.com/LinkStackOrg/LinkStack) | Self-hosted link-in-bio/profile page |
| [seotoolsuite](https://github.com/nitishkgupta/seotoolsuite) | SEO tooling |
| [RespectASO](https://github.com/respectlytics/respectaso) | App Store Optimization keyword research |

## Content and video

Create launch demos, shorts, UGC, raw-video edits, and programmatic video assets.

| Tool | Use |
| --- | --- |
| [ViralMint](https://github.com/openclaw-easy/ViralMint) | Trend scouting, competitor analysis, AI video generation, auto-publishing |
| [OpenShorts](https://github.com/mutonby/openshorts) | AI UGC video platform and clip generator |
| [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | One-click AI short-video generation |
| [ai-trend-publish](https://github.com/liyown/ai-trend-publish) | Trend scraping, AI content generation, scheduled publishing |
| [short-video-maker](https://github.com/gyoridavid/short-video-maker) | MCP/REST short-video generation |
| [ClippedAI](https://github.com/Shaarav4795/ClippedAI) | Open-source OpusClip-style shorts generator |
| [ViralCutter](https://github.com/RafaelGodoyEbert/ViralCutter) | Cut long YouTube videos into short clips |
| [vex](https://github.com/AKMessi/vex) | Terminal AI video editing agent |
| [VibeFrame](https://github.com/vericontext/vibeframe) | CLI-first, MCP-ready AI-native video editor |
| [OpenMontage](https://github.com/calesthio/OpenMontage) | Agentic video production system |
| [OpenReelio](https://github.com/openreelio/openreelio) | Prompt-driven AI video editor |
| [auto-editor](https://github.com/WyattBlue/auto-editor) | Auto-cuts silence and dead space from raw footage |
| [LosslessCut](https://github.com/mifi/lossless-cut) | Lossless video/audio trimming and splitting |
| [OpenScreen](https://github.com/siddharthvaddem/openscreen) | Product demo videos |
| [Remotion](https://github.com/remotion-dev/remotion) | Programmatic video generation with React |
| [MoviePy](https://github.com/Zulko/moviepy) | Python video editing library |
| [OpenTimelineIO](https://github.com/AcademySoftwareFoundation/OpenTimelineIO) | Open timeline interchange API |
| [Kdenlive](https://github.com/KDE/kdenlive) | Full open-source video editor |
| [Shotcut](https://github.com/mltframework/shotcut) | Cross-platform open-source video editor |

## Docs and knowledge base

Write docs, help centers, internal notes, and launch knowledge.

| Tool | Use |
| --- | --- |
| [Docusaurus](https://github.com/facebook/docusaurus) | Documentation website |
| [Docmost](https://github.com/docmost/docmost) | Collaborative wiki and docs |
| [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) | Open-source Notion alternative |
| [Logseq](https://github.com/logseq/logseq) | Local-first knowledge management |
| [Joplin](https://github.com/laurent22/joplin) | Privacy-focused notes with sync |
| [MinerU](https://github.com/opendatalab/MinerU) | Converts PDFs and Office docs into LLM-ready markdown/JSON |

## Deployment and operations

Deploy apps, run infrastructure, ship mobile releases, and monitor uptime.

| Tool | Use |
| --- | --- |
| [Coolify](https://github.com/coollabsio/coolify) | Self-hosted deployment platform |
| [Dokploy](https://github.com/Dokploy/dokploy) | Open-source Vercel/Netlify/Heroku alternative |
| [CapRover](https://github.com/caprover/caprover) | Docker-powered app deployment platform |
| [Dokku](https://github.com/dokku/dokku) | Lightweight Heroku-style PaaS |
| [OpenStatus](https://github.com/openstatusHQ/openstatus) | Uptime monitoring and status pages |
| [fastlane](https://github.com/fastlane/fastlane) | iOS/Android beta deploys, screenshots, metadata, releases |
| [video-preview-appstore](https://github.com/mdo91/video-preview-appstore) | App Store preview-compatible MP4 conversion |
| [App Store Screenshots Generator](https://github.com/jawwadfirdousi/appstore-screenshots-generator) | App Store screenshot generator |
| [Appshot](https://github.com/chrisvanbuskirk/appshot) | CLI for App Store screenshots |
| [Storeshots](https://github.com/eralpozcan/storeshots) | App Store and Google Play screenshot generator |

## Security and legal

Reduce launch risk before users, money, and customer data arrive.

| Tool | Use |
| --- | --- |
| [Bitwarden Clients](https://github.com/bitwarden/clients) | Password manager clients and CLI |
| [Trail of Bits skills](https://github.com/trailofbits/skills) | Claude Code security research and audit skills |
| [Documenso](https://github.com/documenso/documenso) | Open-source DocuSign alternative |

## Productivity

Local tools for faster solo-operator workflows.

| Tool | Use |
| --- | --- |
| [Maccy](https://github.com/p0deje/Maccy) | Lightweight macOS clipboard manager |
| [Rectangle](https://github.com/rxhanson/Rectangle) | macOS window management |
| [Espanso](https://github.com/espanso/espanso) | Cross-platform text expander |
| [ActivityWatch](https://github.com/ActivityWatch/activitywatch) | Privacy-first automated time tracker |
| [Ice](https://github.com/jordanbaird/Ice) | macOS menu bar manager |
| [LocalSend](https://github.com/localsend/localsend) | Local cross-platform file sharing |
| [Syncthing](https://github.com/syncthing/syncthing) | Continuous private file sync |
| [Zoxide](https://github.com/ajeetdsouza/zoxide) | Smarter terminal directory jumping |

## Data

Structured tool data lives in [`data/tools.yml`](data/tools.yml).

## Contributing

Pull requests welcome. See [`CONTRIBUTING.md`](CONTRIBUTING.md).

Quick rule: add tools only when they help a solo founder build, launch, sell, support, automate, or grow a real product.

## Repo topic suggestions

Suggested GitHub topics:

`awesome-list`, `solo-founder`, `open-source`, `source-available`, `indie-hackers`, `saas`, `mvp`, `ai-agents`, `mcp`, `marketing`, `product-growth`, `startup-tools`, `developer-tools`

## License

This repository is licensed under the [MIT License](LICENSE).
