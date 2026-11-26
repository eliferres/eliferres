# Eli Ferres

I design and run agent-operated business systems end to end: finance automations, the data layer under them, a person's approval on live steps, and the monitoring that shows each run. I build tools too, but the systems are the main work. I started Ferres Technologies in July 2026.

## How I work

- **Discovery first.** I ask every question in one sitting and read the systems before I plan.
- **Switched off by default.** Every new write ships turned off, and a dated approval turns it on.
- **One record, one write.** The job writes each record once, however many times it runs.
- **A person approves every live step.** The system prepares each step, and a person says yes.

## Open source

fde-agent-skills is a skills library that holds the methods I use on production work, written as agent skills and subagent specs. The nineteen zero-dependency tools below come from the agent stack I run every day; each one installs in one line and ships with tests on Linux and macOS.

### Start here

- **[fde-agent-skills](https://github.com/eliferres/fde-agent-skills)**: production agent skills and subagent specs for safe writes, migrations, reviews, approvals and go-live.
- **[claude-code-guardrails](https://github.com/eliferres/claude-code-guardrails)**: hooks that refuse dangerous commands before they run.
- **[surface-audit](https://github.com/eliferres/surface-audit)**: a read-only audit of the sites and databases you run: headers, tables open to the public key, routes that answer without a session, secrets in client files.
- **[approval-wall](https://github.com/eliferres/approval-wall)**: keeps the approval card a bot sends to a phone from being forged by the text inside it.
- **[codex-hook-bridge](https://github.com/eliferres/codex-hook-bridge)**: runs the hooks you wrote for Claude Code under the Codex CLI.
- **[layout-ruler](https://github.com/eliferres/layout-ruler)**: measures rendered pages in headless Chrome and prints the pixels that are off.

**Agent infrastructure**

- **[session-continuity](https://github.com/eliferres/session-continuity)**: checkpoints that keep what a context summary drops.
- **[agent-memory-vault](https://github.com/eliferres/agent-memory-vault)**: plain-file memory for AI agents. No database, no embeddings.
- **[agent-eval-harness](https://github.com/eliferres/agent-eval-harness)**: blind two-arm evaluation for AI agent work.
- **[eval-alarm](https://github.com/eliferres/eval-alarm)**: regression alarms for prompts and skills, scored on fixed cases.
- **[routine-fleet](https://github.com/eliferres/routine-fleet)**: keeps scheduled AI routines honest.
- **[token-watchdog](https://github.com/eliferres/token-watchdog)**: flags the sessions that burn tokens for nothing, and says why.
- **[speed-watchdog](https://github.com/eliferres/speed-watchdog)**: an alarm the day your agent harness gets slower.
- **[ripple-wall](https://github.com/eliferres/ripple-wall)**: nothing closes until every copy of a config has moved.
- **[phone-body](https://github.com/eliferres/phone-body)**: one assistant at your desk and in your pocket.

**Frontend quality**

- **[a11y-bar](https://github.com/eliferres/a11y-bar)**: the accessibility rules a machine can decide from the files, with no browser.
- **[website-bar](https://github.com/eliferres/website-bar)**: grades a page against a named craft bar.
- **[design-bar](https://github.com/eliferres/design-bar)**: design taste written down until machines can hold the line.
- **[design-token-gate](https://github.com/eliferres/design-token-gate)**: fails the build on any hand-typed design value.
- **[motion-bar](https://github.com/eliferres/motion-bar)**: a static linter for UI motion, with exit codes for CI.

## What I've built

- **[Well Dealt](https://welldealt.com)**: a credit card answer engine that gives the honest answer, not the affiliate one.
- **[Ferres Tech](https://ferrestech.com)**: AI software for small businesses.
- **[Fivestarbuilt](https://fivestarbuilt.com)**: website rebuilds for highly rated local businesses.
- **[Ferris Legacy](https://ferrislegacy.com)**: a full website for a painting company.

## Private work

Data, systems and AI lead for a multi-brand consumer goods company, 2026 to now: I build accounting automations, a company data layer and an operations hub. The code is private.

Head of Operations, November 2024 to September 2026: day-to-day operations for a 40+ brand TikTok Shop company, from finance and billing to customer support and internal systems. The code is private.

→ Built the internal operating platform  
→ Built a customer support AI agent with human approval  
→ Built an automated affiliate and creator CRM  
→ Led the operations and customer support teams

## About

I have had an operations mind since I was 14 and have spent 8 years at startups. I have built internal software platforms and owned them end to end. I am AI native, with experience in operations, product, content and technology. My strengths are building agentic systems, management, communication and resourcefulness.

→ 2 Billion+ organic YouTube views  
→ 4 Million+ followers

[LinkedIn](https://linkedin.com/in/eliyahuferres) · [eliferres.com](https://eliferres.com)
