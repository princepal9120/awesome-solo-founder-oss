# Trend-to-content engine

End-to-end workflow for finding current demand, turning it into content, and shipping launch assets.

## Goal

Use CLI-first research tools and agent skills to find trends across X, Reddit, Instagram, TikTok, YouTube, LinkedIn, and the web. Then convert those findings into posts, shorts, demos, and launch pages.

## Inputs

- Product URL or landing-page draft
- Target customer
- Pain point or niche
- Platforms to research
- Content goal: waitlist, users, feedback, revenue

## Tool map

| Source | Tool |
| --- | --- |
| Web + Reddit + X + YouTube + HN | `mvanhorn/last30days-skill` |
| X/Twitter | `public-clis/twitter-cli` |
| Reddit | `public-clis/rdt-cli` |
| Instagram | `princepal9120/ig-cli` |
| TikTok | `princepal9120/tkt-cli` |
| LinkedIn | `Linked-API/linkedin-cli` |
| Multi-source agent research | `Panniantong/Agent-Reach` |
| Demo video | `siddharthvaddem/openscreen` |
| Launch video | `heygen-com/hyperframes` |
| Shorts/UGC | `mutonby/openshorts`, `gyoridavid/short-video-maker`, `remotion-dev/remotion` |
| Scheduling | `gitroomhq/postiz-app`, `trypostit/trypost`, `inovector/mixpost` |

## Workflow

### 1. Pick seed query

Examples:

- "AI bookkeeping for freelancers"
- "founders hate app store screenshots"
- "developers need cheaper product analytics"
- "solo founder launch video workflow"

### 2. Pull recent conversations

Run last30days-style research first:

```bash
last30days "your seed query"
```

Expected output:

- repeating pains
- exact phrases people use
- high-engagement posts
- objections
- communities
- competitor mentions

### 3. Deep-dive per platform

Use platform CLIs:

```bash
twitter-cli search "your seed query"
rdt-cli search "your seed query"
ig-cli search "your seed query"
tkt-cli search "your seed query"
linkedin-cli search "your seed query"
```

Capture:

- hooks
- formats
- comments
- emotional language
- repeated questions
- proof screenshots

### 4. Score trend quality

| Signal | Score |
| --- | --- |
| People complain with urgency | 3 |
| People mention paid alternatives | 3 |
| Recent posts keep appearing | 2 |
| Comments ask for tool/template | 2 |
| Solo founder can build MVP quickly | 2 |
| Easy demo/video proof | 2 |

Good trend: 8+.

### 5. Convert trend into content angles

Create:

- X thread
- Reddit post
- LinkedIn post
- TikTok/Reels/Shorts script
- demo-video outline
- landing-page headline
- launch checklist

Template:

```text
Hook: [pain in user language]
Proof: [trend/source/example]
Build: [what product does]
Demo: [one visual moment]
CTA: [waitlist / try / comment / DM]
```

### 6. Create launch assets

- Use OpenScreen for polished product demo.
- Use Hyperframes for launch explainer video.
- Use Remotion/OpenShorts/short-video-maker for platform-native shorts.
- Use App Store screenshot tools if mobile app.

### 7. Schedule distribution

Use Postiz/TryPost/Mixpost:

- Day 1: pain post
- Day 2: build-in-public proof
- Day 3: short demo
- Day 4: Reddit feedback post
- Day 5: LinkedIn founder story
- Day 6: X thread with metrics
- Day 7: launch post with CTA

## Output artifact

Each trend research run should produce:

- `trend-summary.md`
- `content-calendar.md`
- `launch-video-brief.md`
- `reddit-post.md`
- `x-thread.md`
- `linkedin-post.md`
- `shorts-scripts.md`

## Agent prompt

```text
Research the last 30 days of conversations about: [topic].
Use Reddit, X, YouTube, Instagram, TikTok, LinkedIn, HN, and web where available.
Find repeated pains, high-engagement phrasing, competitor mentions, objections, and content hooks.
Return a ranked trend report, then convert top 3 trends into launch content for X, Reddit, LinkedIn, TikTok, Instagram Reels, and YouTube Shorts.
```
