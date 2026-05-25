<p align="center">
  <img src="assets/logo.svg" alt="Awesome Solo Founder OSS logo" width="760">
</p>

<h1 align="center">Awesome Solo Founder OSS</h1>

<p align="center">
  <strong>Open-source stack for solo founders to build, launch, distribute, monetize, support, and automate polished products.</strong>
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

Open-source and source-available tools for solo founders building polished internet businesses.

Goal: help one person move from idea to shipped product, distribution, support, and revenue without buying a giant SaaS stack.

> Not a guarantee of revenue. This repo maps practical tools and workflows that can help a solo founder reach serious revenue targets.

## Quick start

- Need MVP fast? Start with [Open SaaS](https://github.com/wasp-lang/open-saas), [Supabase](https://github.com/supabase/supabase), or [PocketBase](https://github.com/pocketbase/pocketbase).
- Need launch video? Use [Hyperframes](https://github.com/heygen-com/hyperframes) or [OpenScreen](https://github.com/siddharthvaddem/openscreen).
- Need faster building with agents? Use [Codex](https://github.com/openai/codex), [Claude Code](https://github.com/anthropics/claude-code), [XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP), and [Playwright MCP](https://github.com/microsoft/playwright-mcp).
- Need content trends? Use [last30days-skill](https://github.com/mvanhorn/last30days-skill), [twitter-cli](https://github.com/public-clis/twitter-cli), [rdt-cli](https://github.com/public-clis/rdt-cli), [ig-cli](https://github.com/princepal9120/ig-cli), and [tkt-cli](https://github.com/princepal9120/tkt-cli).
- Need distribution? Use [Postiz](https://github.com/gitroomhq/postiz-app), [TryPost](https://github.com/trypostit/trypost), or [Mixpost](https://github.com/inovector/mixpost).
- Need productivity base layer? Use [Maccy](https://github.com/p0deje/Maccy), [Rectangle](https://github.com/rxhanson/Rectangle), [Espanso](https://github.com/espanso/espanso), and [ActivityWatch](https://github.com/ActivityWatch/activitywatch).
- Need product marketing? Use [Dub](https://github.com/dubinc/dub), [Papermark](https://github.com/papermark/papermark), [Typebot](https://github.com/baptisteArno/typebot.io), [Ghost](https://github.com/TryGhost/Ghost), and [GrowthBook](https://github.com/growthbook/growthbook).
- Need monetization? Use [Polar](https://github.com/polarsource/polar), [Lago](https://github.com/getlago/lago), or [Kill Bill](https://github.com/killbill/killbill).

## Contents

- [Why this list exists](#why-this-list-exists)
- [Similar repos researched](#similar-repos-researched)
- [Selection rules](#selection-rules)
- [Founder lifecycle map](#founder-lifecycle-map)
- [Core stack](#core-stack)
  - [Build MVP](#build-mvp)
  - [Deploy and operate](#deploy-and-operate)
  - [Analytics and product learning](#analytics-and-product-learning)
  - [Marketing and distribution](#marketing-and-distribution)
  - [UGC and content engine](#ugc-and-content-engine)
  - [Agentic raw-video editing](#agentic-raw-video-editing)
  - [Product launch assets](#product-launch-assets)
  - [iOS/Android app launch assets](#iosandroid-app-launch-assets)
  - [AI coding agents and MCP](#ai-coding-agents-and-mcp)
  - [Trend discovery](#trend-discovery)
  - [Sales, CRM, and support](#sales-crm-and-support)
  - [Billing and monetization](#billing-and-monetization)
  - [Docs, website, and polish](#docs-website-and-polish)
  - [Productivity and solo-operator tools](#productivity-and-solo-operator-tools)
  - [Automation and AI-agent operations](#automation-and-ai-agent-operations)
- [Agent-readiness score](#agent-readiness-score)
- [Suggested folder expansion](#suggested-folder-expansion)
- [Contributing](#contributing)

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
- Is active enough to trust for founder workflows.
- Is better than adjacent options for at least one clear solo-founder job.

Avoid:

- Closed-source-only tools.
- Pure inspiration/motivation links.
- Abandoned repos with no clear maintenance path.
- Enterprise-only tools with unusable community edition.

## Founder lifecycle map

1. [Idea and validation](#trend-discovery)
2. [Build MVP](#build-mvp)
3. [Ship infrastructure](#deploy-and-operate)
4. [Analytics and feedback](#analytics-and-product-learning)
5. [Marketing and distribution](#marketing-and-distribution)
6. [UGC and content engine](#ugc-and-content-engine)
7. [Agentic raw-video editing](#agentic-raw-video-editing)
8. [Product launch assets](#product-launch-assets)
9. [iOS/Android app launch assets](#iosandroid-app-launch-assets)
10. [AI coding agents and MCP](#ai-coding-agents-and-mcp)
11. [Trend discovery](#trend-discovery)
12. [Sales, CRM, support](#sales-crm-and-support)
13. [Billing and monetization](#billing-and-monetization)
14. [Docs, polish, trust](#docs-website-and-polish)
15. [Productivity and solo-operator tools](#productivity-and-solo-operator-tools)
16. [Automation and AI-agent operations](#automation-and-ai-agent-operations)

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
| [dittofeed/dittofeed](https://github.com/dittofeed/dittofeed) | Customer engagement automation across email, SMS, push, WhatsApp, Slack |
| [dubinc/dub](https://github.com/dubinc/dub) | Link attribution, short links, campaigns |
| [papermark/papermark](https://github.com/papermark/papermark) | DocSend alternative for pitch decks, proposals, analytics |
| [baptisteArno/typebot.io](https://github.com/baptisteArno/typebot.io) | Chatbot/funnel builder for lead capture and onboarding |
| [TryGhost/Ghost](https://github.com/TryGhost/Ghost) | Blog, newsletter, memberships, subscriptions |
| [webstudio-is/webstudio](https://github.com/webstudio-is/webstudio) | Open-source Webflow alternative for landing pages |
| [payloadcms/payload](https://github.com/payloadcms/payload) | Headless CMS for marketing sites and content ops |
| [growthbook/growthbook](https://github.com/growthbook/growthbook) | Feature flags, A/B tests, conversion experiments |
| [calcom/cal.diy](https://github.com/calcom/cal.diy) | Scheduling for sales calls, demos, onboarding |
| [documenso/documenso](https://github.com/documenso/documenso) | Open-source DocuSign alternative for proposals/contracts |
| [discourse/discourse](https://github.com/discourse/discourse) | Community forum for product-led growth |
| [forem/forem](https://github.com/forem/forem) | Community publishing platform |
| [LinkStackOrg/LinkStack](https://github.com/LinkStackOrg/LinkStack) | Link-in-bio/profile page for social campaigns |
| [nitishkgupta/seotoolsuite](https://github.com/nitishkgupta/seotoolsuite) | SEO tooling |
| [respectlytics/respectaso](https://github.com/respectlytics/respectaso) | App Store Optimization keyword research |

For social scheduling, see [UGC and content engine](#ugc-and-content-engine). For app-store assets, see [iOS/Android app launch assets](#iosandroid-app-launch-assets).

### UGC and content engine

Tools for repeatable content across TikTok, Instagram/Reels, YouTube/Shorts, X, LinkedIn, and Reddit.

| Project | Use | Platforms |
| --- | --- | --- |
| [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app) | Social scheduling, AI content ops, MCP/API surface | TikTok, Instagram, YouTube, X, LinkedIn, Reddit, Threads, Bluesky, Mastodon, Pinterest, Discord, Slack |
| [trypostit/trypost](https://github.com/trypostit/trypost) | Social scheduling and content calendar | Instagram, Facebook, LinkedIn, X, TikTok, YouTube, Pinterest, Threads, Bluesky, Mastodon |
| [inovector/mixpost](https://github.com/inovector/mixpost) | Self-hosted Buffer-style social media management | Multi-platform social publishing |
| [zernio-dev/latewiz](https://github.com/zernio-dev/latewiz) | Open-source scheduler powered by Zernio API | Instagram, TikTok, YouTube, X, LinkedIn, Facebook, Pinterest, Threads, Bluesky, Snapchat, Telegram, Discord, Slack |
| [mutonby/openshorts](https://github.com/mutonby/openshorts) | AI UGC video platform, clip generator, YouTube Studio | TikTok, Instagram Reels, YouTube Shorts |
| [openclaw-easy/ViralMint](https://github.com/openclaw-easy/ViralMint) | Trend scouting, competitor analysis, AI video generation, auto-publishing | YouTube, TikTok, Douyin |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | One-click AI short-video generation | TikTok, Reels, Shorts |
| [liyown/ai-trend-publish](https://github.com/liyown/ai-trend-publish) | Trend scraping, AI content generation, scheduled publishing | X/Twitter, web, WeChat |
| [RafaelGodoyEbert/ViralCutter](https://github.com/RafaelGodoyEbert/ViralCutter) | Cut long YouTube videos into viral short clips | TikTok, Instagram Reels |
| [gyoridavid/short-video-maker](https://github.com/gyoridavid/short-video-maker) | MCP/REST short-video creation for agents | TikTok, Instagram Reels, YouTube Shorts |
| [Shaarav4795/ClippedAI](https://github.com/Shaarav4795/ClippedAI) | Open-source OpusClip-style shorts generator | YouTube Shorts, TikTok |
| [sw-aka/Short-Video-Creator](https://github.com/sw-aka/Short-Video-Creator) | AI captions and background videos | YouTube Shorts, TikTok, Instagram Reels, Snapchat Spotlight |
| [remotion-dev/remotion](https://github.com/remotion-dev/remotion) | Programmatic video generation with React | Platform-neutral video assets |

### Agentic raw-video editing

Tools that can edit or transform existing/raw footage, ideally through CLI, MCP, scripts, or inspectable timelines.

| Project | Use | Best for |
| --- | --- | --- |
| [AKMessi/vex](https://github.com/AKMessi/vex) | Terminal AI video editing agent with FFmpeg, Whisper, and tool calls | Natural-language edits on raw footage |
| [vericontext/vibeframe](https://github.com/vericontext/vibeframe) | CLI-first, MCP-ready AI-native video editor | Agent-driven video workflows |
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | Agentic video production system with pipelines, tools, and skills | Full production orchestration |
| [openreelio/openreelio](https://github.com/openreelio/openreelio) | Prompt-driven AI video editor for Shorts and long-form | AI-assisted timeline editing |
| [WyattBlue/auto-editor](https://github.com/WyattBlue/auto-editor) | CLI editor that automatically cuts silence/dead space | Fast cleanup of raw talking-head footage |
| [mifi/lossless-cut](https://github.com/mifi/lossless-cut) | Lossless video/audio trimming and splitting | Rough cuts without re-encoding |
| [debarch777/AI-Video-Editor](https://github.com/debarch777/AI-Video-Editor) | LLM + transcript-driven raw talking-head clip editor | Captioned social clips from raw video |
| [AcademySoftwareFoundation/OpenTimelineIO](https://github.com/AcademySoftwareFoundation/OpenTimelineIO) | Timeline interchange API | Agent-readable edit decisions |
| [Zulko/moviepy](https://github.com/Zulko/moviepy) | Python video editing library | Scripted/agent-created edits |
| [mltframework/mlt](https://github.com/mltframework/mlt) | Multimedia framework behind NLEs | Programmatic timeline rendering |
| [KDE/kdenlive](https://github.com/KDE/kdenlive) | Full open-source NLE | Manual finishing after agent rough cut |
| [mltframework/shotcut](https://github.com/mltframework/shotcut) | Cross-platform open-source video editor | Manual polish and export |

### Product launch assets

Tools for launch videos, product demos, screenshots, and polished campaign assets.

| Project | Use |
| --- | --- |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | Agent-friendly HTML-to-video launch videos |
| [siddharthvaddem/openscreen](https://github.com/siddharthvaddem/openscreen) | Free product demo videos, Screen Studio alternative |
| [heygen-com/hyperframes-launch-video](https://github.com/heygen-com/hyperframes-launch-video) | Hyperframes launch-video example |
| [heygen-com/hyperframes-launches](https://github.com/heygen-com/hyperframes-launches) | Open-source production launch-video compositions |
| [coleam00/hyperframes-ai-video-generation](https://github.com/coleam00/hyperframes-ai-video-generation) | URL-to-polished AI-voiced HyperFrames short workflow |
| [openclaw-easy/ViralMint](https://github.com/openclaw-easy/ViralMint) | Trend scouting, competitor analysis, AI video generation, auto-publishing |

For app-store screenshots and preview videos, see [iOS/Android app launch assets](#iosandroid-app-launch-assets).

### iOS/Android app launch assets

Tools for App Store / Google Play launch videos, screenshots, previews, and release automation.

| Project | Use | App launch job |
| --- | --- | --- |
| [mdo91/video-preview-appstore](https://github.com/mdo91/video-preview-appstore) | Convert screen recordings into App Store preview-compatible MP4s | iOS App Preview video |
| [eralpozcan/storeshots](https://github.com/eralpozcan/storeshots) | App Store and Google Play screenshot generator with device mockups | iOS/Android store screenshots |
| [jawwadfirdousi/appstore-screenshots-generator](https://github.com/jawwadfirdousi/appstore-screenshots-generator) | Browser-based App Store screenshot generator | iOS screenshots |
| [chrisvanbuskirk/appshot](https://github.com/chrisvanbuskirk/appshot) | CLI for App Store screenshots | iOS screenshot automation |
| [fastlane/fastlane](https://github.com/fastlane/fastlane) | Automate beta, deploy, screenshots, metadata, and release flow | iOS/Android release ops |
| [siddharthvaddem/openscreen](https://github.com/siddharthvaddem/openscreen) | Product demo screen recordings without watermark | Mobile app demo video |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | HTML-to-video launch explainers | App launch explainer |
| [remotion-dev/remotion](https://github.com/remotion-dev/remotion) | Programmatic videos with React | Store/social promo videos |

### AI coding agents and MCP

Tools that help solo founders build faster with coding agents, product-specific skills, and MCP servers.

| Project | Use | Best for |
| --- | --- | --- |
| [openai/codex](https://github.com/openai/codex) | Terminal coding agent | Building, refactoring, tests, docs |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Agentic coding tool in terminal | Codebase work, git workflows, product iteration |
| [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | Open-source Gemini agent in terminal | Large-context coding and research |
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | Open-source coding agent | Multi-model terminal development |
| [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) | Open-source terminal coding agent | Local/remote coding workflows |
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | Curated Claude Code skills, hooks, commands, plugins | Finding agent skills faster |
| [trailofbits/skills](https://github.com/trailofbits/skills) | Claude Code security audit skills | Security review before launch |
| [OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files) | Persistent markdown planning skill | Agent project planning |
| [nowork-studio/NotFair](https://github.com/nowork-studio/NotFair) | Claude Code skills for SEO, GEO, Google Ads, Meta Ads | Growth and marketing ops |
| [getsentry/XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) | MCP server/CLI for iOS and macOS builds | iOS/macOS build, test, simulator automation |
| [getsentry/XcodeBuildMCP-iOS-Template](https://github.com/getsentry/XcodeBuildMCP-iOS-Template) | Scaffold template for iOS app projects | Faster iOS app starts |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | Browser automation MCP server | QA, screenshots, web testing |
| [github/github-mcp-server](https://github.com/github/github-mcp-server) | Official GitHub MCP server | Issues, PRs, repos, code workflow |
| [upstash/context7](https://github.com/upstash/context7) | Up-to-date docs for LLMs and AI code editors | Fresh framework/API docs |
| [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) | Figma layout context for coding agents | Design-to-code |
| [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | MCP server collection | Agent capability discovery |
| [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) | Community MCP registry service | Finding MCP servers |
| [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | Curated MCP server list | Picking agent integrations |

Playbook: [agent-assisted product build sprint](playbooks/agent-assisted-product-build-sprint.md)

### Trend discovery

Tools for finding what people are already talking about before writing content.

| Project | Use | Sources |
| --- | --- | --- |
| [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | Agent skill for recent-topic research and synthesis | Reddit, X, YouTube, Hacker News, Polymarket, web |
| [levineam/lastXdays-skill](https://github.com/levineam/lastXdays-skill) | Configurable time-range version of last30days research | Same pattern, variable date window |
| [public-clis/public-clis](https://github.com/public-clis/public-clis) | CLI catalog for public web services | Multiple platforms |
| [public-clis/twitter-cli](https://github.com/public-clis/twitter-cli) | Terminal-first Twitter/X feed, bookmarks, timeline research | X/Twitter |
| [public-clis/rdt-cli](https://github.com/public-clis/rdt-cli) | Terminal-first Reddit feed, post, search, upvote, save workflow | Reddit |
| [princepal9120/ig-cli](https://github.com/princepal9120/ig-cli) | Instagram CLI for trend discovery workflow | Instagram |
| [princepal9120/tkt-cli](https://github.com/princepal9120/tkt-cli) | TikTok trend discovery CLI | TikTok |
| [Linked-API/linkedin-cli](https://github.com/Linked-API/linkedin-cli) | Agent-friendly LinkedIn account/data CLI | LinkedIn |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Multi-platform search/read CLI for agents | Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu |
| [NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler) | Social platform crawler for posts, videos, comments, and trend research | XiaoHongShu, Douyin, Kuaishou, Bilibili, Weibo, Tieba, Zhihu |

Playbook: [trend-to-content engine](playbooks/trend-to-content-engine.md)

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

### Productivity and solo-operator tools

Local productivity tools that make one founder faster before any SaaS stack exists.

| Project | Use | Why solo founders care |
| --- | --- | --- |
| [p0deje/Maccy](https://github.com/p0deje/Maccy) | Lightweight macOS clipboard manager | Reuse prompts, snippets, links, launch copy |
| [rxhanson/Rectangle](https://github.com/rxhanson/Rectangle) | macOS window management | Faster coding/research/demo layout |
| [espanso/espanso](https://github.com/espanso/espanso) | Cross-platform text expander | Reusable support replies, prompts, snippets |
| [ActivityWatch/activitywatch](https://github.com/ActivityWatch/activitywatch) | Privacy-first automated time tracker | Know where founder time leaks |
| [jordanbaird/Ice](https://github.com/jordanbaird/Ice) | macOS menu bar manager | Less visual noise while building |
| [AppFlowy-IO/AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) | Open-source Notion alternative | Product docs, CRM-lite, launch planning |
| [logseq/logseq](https://github.com/logseq/logseq) | Local-first knowledge management | Research notes and founder memory |
| [laurent22/joplin](https://github.com/laurent22/joplin) | Privacy-focused notes with sync | Cross-device notes and docs |
| [localsend/localsend](https://github.com/localsend/localsend) | Local cross-platform file sharing | Move screenshots/videos/assets quickly |
| [syncthing/syncthing](https://github.com/syncthing/syncthing) | Continuous file sync | Private sync for assets and notes |
| [bitwarden/clients](https://github.com/bitwarden/clients) | Password manager clients and CLI | Secrets hygiene for founder ops |
| [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide) | Smarter `cd` command | Faster terminal navigation |

### Automation and AI-agent operations

| Project | Use |
| --- | --- |
| [activepieces/activepieces](https://github.com/activepieces/activepieces) | Workflow automation, MCP, AI agents |
| [n8n-io/n8n](https://github.com/n8n-io/n8n) | Workflow automation with native AI features |

## Opinionated default stack

If a solo founder wants the shortest path, start here. These are active OSS/source-available defaults with strong solo-founder leverage.

| Job | Default pick | Why this over adjacent options |
| --- | --- | --- |
| MVP backend | [Supabase](https://github.com/supabase/supabase) | Broadest full-stack path: Postgres, auth, storage, edge |
| Tiny MVP backend | [PocketBase](https://github.com/pocketbase/pocketbase) | Smallest setup for quick validation |
| SaaS starter | [Open SaaS](https://github.com/wasp-lang/open-saas) | Auth, jobs, payments, landing path in one starter |
| Deploy | [Coolify](https://github.com/coollabsio/coolify) | Strong self-hosted Vercel/Heroku alternative |
| Product analytics | [PostHog](https://github.com/PostHog/posthog) | Analytics, replay, surveys, flags in one product |
| Simple web analytics | [Umami](https://github.com/umami-software/umami) | Lightweight and easy to self-host |
| Email list | [Listmonk](https://github.com/knadh/listmonk) | Fast newsletter/list management |
| Social distribution | [Postiz](https://github.com/gitroomhq/postiz-app) | Strong multi-platform scheduling plus agent/MCP surface |
| Trend research | [last30days-skill](https://github.com/mvanhorn/last30days-skill) | Best single agent workflow for recent demand research |
| Reddit research | [rdt-cli](https://github.com/public-clis/rdt-cli) | Terminal-first Reddit discovery |
| X research | [twitter-cli](https://github.com/public-clis/twitter-cli) | Terminal-first X discovery |
| Launch video | [Hyperframes](https://github.com/heygen-com/hyperframes) | Agent-friendly HTML-to-video workflow |
| Product demo | [OpenScreen](https://github.com/siddharthvaddem/openscreen) | Open Screen Studio-style demos |
| iOS/macOS agent loop | [XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) | Agent can build, test, run simulator |
| Coding agent | [Codex](https://github.com/openai/codex) + [Claude Code](https://github.com/anthropics/claude-code) | Strong terminal-agent combo for iteration and review |
| Docs | [Docusaurus](https://github.com/facebook/docusaurus) | Stable docs/marketing content path |
| Payments | [Polar](https://github.com/polarsource/polar) | Strong developer-product monetization fit |
| Productivity | [Maccy](https://github.com/p0deje/Maccy) + [Espanso](https://github.com/espanso/espanso) | Prompt/snippet reuse loop |

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
