# Eli Ferres

I'm a forward-deployed engineer and design systems builder. I sit inside a business, find the work still done by hand, and ship the software that replaces it, to a bar I can name and a machine can grade.

Ten years in startups, most recently as Head of Product and Operations at a creator-commerce company. I started in operations, fell for design, learned systems the hard way, and ended up running teams. Self-taught: one college course for the basics, then something like 4,000 commits across dozens of projects with AI as my pair. Before software I spent seven years growing gaming content brands past a billion views.

The idea under all of it: write the taste down until a machine can hold the line. My app defines its own design language, and a gate reads those rules and fails any build that ships a hand-typed value. Same rule for my code and my memory.

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

- **[Well Dealt](https://welldealt.com)**: a credit card answer engine that does the math and gives the honest answer, not the affiliate one.
- **[Fulcrus](https://fulcrus.com)**: AI readiness assessments for businesses, plus the client infrastructure behind it (per-client repos, playbooks, deploy rails).
- **[Fivestarbuilt](https://fivestarbuilt.com)**: website rebuilds for highly rated local businesses, from lead sourcing to the finished site.
- **[Ferris Legacy](https://ferrislegacy.com)**: full website for a painting company.
- **Zireael**: my personal AI operating system. Persistent memory, enforcement hooks, scheduled routines, and a 24/7 Telegram agent. The twelve repos above are pieces of it.

Built daily with Claude Code. Happy to talk through any of it: [LinkedIn](https://linkedin.com/in/eliyahuferres)
