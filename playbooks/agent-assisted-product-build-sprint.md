# Agent-assisted product build sprint

Workflow for using coding agents, skills, and MCP servers to ship faster as a solo founder.

## Goal

Move from idea to working product slice with less manual glue work:

- plan scope
- scaffold product
- build core feature
- test browser/mobile flow
- polish UI
- prepare launch assets
- ship and monitor

## Tool map

| Job | Tool |
| --- | --- |
| Coding agent | Codex, Claude Code, Gemini CLI, OpenCode, Qwen Code |
| Agent skills | awesome-claude-code, planning-with-files, Trail of Bits skills, NotFair |
| iOS/macOS build/test | XcodeBuildMCP |
| Browser QA | Playwright MCP |
| GitHub workflow | GitHub MCP Server |
| Fresh docs | Context7 |
| Design-to-code | Figma Context MCP |
| MCP discovery | MCP Servers, MCP Registry, awesome-mcp-servers |

## Sprint loop

### 1. Turn idea into build plan

Output:

- target user
- one painful job
- one paid action
- one MVP workflow
- explicit non-goals

Prompt:

```text
Act as a solo-founder product engineer.
Convert this idea into a 3-day MVP plan with one core workflow, one landing page, one onboarding path, and one monetization experiment.
Keep scope small enough for one developer using coding agents.
```

### 2. Create agent-readable project context

Add:

- `README.md`
- `AGENTS.md`
- `docs/product-brief.md`
- `docs/test-plan.md`
- `docs/launch-plan.md`

Agents work faster when product intent and test shape are explicit.

### 3. Build with one primary agent

Use Codex or Claude Code as main implementer.

Rules:

- one feature branch
- small commits
- tests before large refactor
- no new dependency unless it saves real time
- verify after every meaningful edit

### 4. Add MCP tools only where they remove bottlenecks

Use:

- Context7 when framework/API docs might be stale
- Figma Context MCP when translating design into UI
- Playwright MCP for browser flows and screenshots
- XcodeBuildMCP for iOS/macOS build, simulator, and test loops
- GitHub MCP for issues, PRs, labels, release notes

### 5. Mobile build loop

For iOS/macOS:

```text
Use XcodeBuildMCP to inspect schemes, build app, run tests, boot simulator, install app, launch app, capture logs, and report failures with exact fix locations.
```

For Android:

```text
Use CLI/Gradle logs, emulator screenshots, and Playwright/Appium-style checks where available. Keep crash logs and release signing steps documented.
```

### 6. Browser QA loop

Use Playwright MCP to verify:

- landing page loads
- signup works
- pricing CTA works
- empty states make sense
- mobile layout readable
- console has no critical errors

### 7. Launch asset loop

Use:

- Hyperframes for launch explainer
- OpenScreen for product demo
- Remotion/OpenShorts for shorts
- app screenshot tools for iOS/Android stores

### 8. Security and launch check

Use Trail of Bits skills or security-focused agent review for:

- secrets
- auth bypass
- payment webhooks
- unsafe file uploads
- prompt-injection surfaces
- dependency risk

### 9. Ship

Minimum launch package:

- live product URL
- demo video
- 3 screenshots
- changelog
- pricing page
- support channel
- first 7 days content calendar

## Output artifact

Each build sprint should produce:

- `product-brief.md`
- `implementation-plan.md`
- `test-plan.md`
- `qa-report.md`
- `launch-assets.md`
- `release-notes.md`

