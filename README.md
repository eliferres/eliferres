# Eli Ferres

I'm a forward-deployed engineer and design systems builder that sits inside a business, finds any bit of manual work, and then ships replacement software to a named bar and a machine-gradable standard.

I've spent ten years at startups doing end-to-end ship lines, mostly most recently as Head of Product and Operations at a creator-commerce company. I cut my teeth in operations, relished in the process of design, learned the rigors of systems, and rose to team leadership. I'm self-taught, mostly because I picked up only the basics of software from a college course and learned it all by shipping something like 4000 commits to tens of projects with only artificial intelligence as my pair. Before software I spent seven years growing gaming content brands past a billion views.

It all comes down to one central idea: write the taste down until a machine can hold the line. That's why my app defines its own design language and any build that would ship incorrect token gate fails under a handful of rules I've written, not code written by me at some specific point in the past, but code that checks against the same grain that makes my app feel the way it does. No hand-typed hex values anywhere in sight. It's the same rule that governs my code and my memory.

## Open source

Twelve pieces of the system my AI assistant runs on, released as standalone zero-dependency repos. All twelve are public. Start with the two design-systems tools, then the memory vault.

- **[design-token-gate](https://github.com/eliferres/design-token-gate)**: fails the build on any hand-typed design value. Ladders read from the tokens file, a debt list that only shrinks.
- **[motion-bar](https://github.com/eliferres/motion-bar)**: a static linter for UI motion. Named rules for duration, easing, frequency, and reduced motion, with exit codes for CI.
- **[agent-memory-vault](https://github.com/eliferres/agent-memory-vault)**: plain-file memory for AI agents. A router note, one home per topic, newest wins.
- **[session-continuity](https://github.com/eliferres/session-continuity)**: checkpoints for AI agents that keep the decisions, paths, and dead ends a summary drops.
- **[claude-code-guardrails](https://github.com/eliferres/claude-code-guardrails)**: deterministic hooks that refuse dangerous commands before they run, with a liveness harness that proves the guards still block.
- **[ripple-wall](https://github.com/eliferres/ripple-wall)**: a fail-closed wall for config drift. Nothing closes until every mapped copy moves or carries a written reason.
- **[design-bar](https://github.com/eliferres/design-bar)**: design taste written down until machines and strangers can hold the line. Rulebook, checkers, slop scanner, review panel.
- **[website-bar](https://github.com/eliferres/website-bar)**: grades a page against a named craft bar. One JSON config, a deterministic report, exit codes for CI.
- **[agent-eval-harness](https://github.com/eliferres/agent-eval-harness)**: blind two-arm evaluation for AI agent work. Hidden tests, an anonymized judge, a four-legged ship verdict.
- **[routine-fleet](https://github.com/eliferres/routine-fleet)**: keeps scheduled AI routines honest. A twin-run guard, a watchdog for silent deaths, parity against the live scheduler.
- **[speed-watchdog](https://github.com/eliferres/speed-watchdog)**: a speed meter for agent harnesses. Median timings, frozen baselines, an alarm the day something gets slower.
- **[phone-body](https://github.com/eliferres/phone-body)**: one brain, two bodies. The same assistant at your desk and in your pocket, synced through a plain-file vault.

## What I've built

Most of it lives in private repos.

<details>
<summary><b>The full list</b></summary>

**Inside a creator-commerce company (2025 to 2026)**

- **Operations platform**: the internal app the company runs on. Revenue analytics, cash reconciliation, automated billing, capacity planning, brand KPIs, and role-based access for the whole team.
- **Affiliate platform**: affiliate deals tracked end to end, from signed contract through deal pipeline to payout and reserve accounting, driven by events from the contract, banking, and billing systems, with full audit trails.
- **Design system**: one design language the app itself defines, a token gate that fails any build carrying a hand-typed value, and high-fidelity prototypes that are the spec engineering builds against.
- **AI operating layer**: reconciliation agents, daily briefs, and automations in use across every department.
- **Marketing site**: the company's public site, one platform story told three ways (brands, agencies, creators), copy grounded in real meeting transcripts.

**Client and personal builds**

- **[Ferris Legacy](https://ferrislegacy.com)**: full website for a painting company.
- **[Well Dealt](https://welldealt.com)**: a credit card answer engine that does the math and gives the honest answer, not the affiliate one.
- **[Fulcrus](https://fulcrus.com)**: AI readiness assessments for businesses, plus the client infrastructure behind it (per-client repos, playbooks, deploy rails).
- **[Fivestarbuilt](https://fivestarbuilt.com)**: website rebuilds for highly rated local businesses, from lead sourcing to the finished site.
- **Zireael**: my personal AI operating system. Persistent memory, enforcement hooks, scheduled routines, and a 24/7 Telegram agent. One brain, synced across machines, with review gates that hold every build to a minimum 9 out of 10 on design and code.
- **Market dashboard**: multi-source market intelligence (options flow, prediction markets, live pricing) with entry-signal scoring.
- **Finance dashboard**: every account, one view, reconciled automatically.
- **App starter**: a reusable production-grade platform layer (auth, tenants, deploy rails) so every new product starts at mile ten.

</details>

Built daily with Claude Code. Happy to talk through any of it: [LinkedIn](https://linkedin.com/in/eliyahuferres)
